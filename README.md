<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&text=Expectation%20Decider&fontAlign=50&fontAlignY=40&color=gradient" />
</p>

### Probability & Statistics Based Student Performance Prediction Model

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Statistics](https://img.shields.io/badge/Statistics-Probability-red?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy)
![SciPy](https://img.shields.io/badge/SciPy-Statistical%20Analysis-blue?style=for-the-badge&logo=scipy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?style=for-the-badge)

<h2 align="center">🌐 Connect With Me</h2>

<p align="center">
  <a href="https://www.instagram.com/ghost_6927/?hl=en" target="_blank">
    <img src="https://skillicons.dev/icons?i=instagram" height="60" alt="Instagram"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/ghost-patel-0267663b7/" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" height="60" alt="LinkedIn"/>
  </a>
</p>

---

# 📌 Table of Contents

<table>
<tr>
<td valign="top" width="65%">

- 🎯 [Project Overview](#project-overview)
- 🎯 [Project Objectives](#project-objectives)
- 🚀 [Features](#features)
- 📊 [Dataset Attributes](#dataset-attributes)
- 📂 [Project Structure](#project-structure)
- 🧠 [Statistical Concepts Used](#statistical-concepts-used)
- 🔬 [Technologies Used](#technologies-used)
- ⚙️ [Installation](#installation)
- ▶️ [How to Run](#how-to-run)
- 📈 [Visualizations](#visualizations)
- 📋 [Sample Results](#sample-results)
- 📚 [Learning Outcomes](#learning-outcomes)
- 💡 [Future Improvements](#future-improvements)
- 👨‍💻 [Author](#author)
- ⭐ [Support](#support)
- 🏆 [Final Conclusion](#final-conclusion)

</td>

<td valign="top" align="right">

<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="400"/>

</td>
</tr>
</table>

---

<a name="project-overview"></a>
# 🎯 Project Overview

The **Expectation Decider** is a Probability and Statistics project designed to analyze student academic performance and estimate the likelihood of passing a competitive mathematics examination.

The model uses student-related factors such as:

- Study Hours
- Attendance Percentage
- Group Discussion Participation
- Previous Test Scores

to perform statistical analysis and derive meaningful probability-based insights.

This project demonstrates practical applications of Probability Theory, Random Variables, Probability Distributions, Conditional Probability, Contingency Tables, and Bayes Theorem using Python.

---

<a name="project-objectives"></a>
# 🎯 Project Objectives

The objectives of this project are:

- Generate and analyze student performance data.
- Apply probability concepts to real-world scenarios.
- Understand random variables and probability distributions.
- Calculate empirical and theoretical probabilities.
- Analyze relationships between variables.
- Use Bayes Theorem for prediction.
- Visualize statistical patterns using charts.
- Develop data-driven decision-making skills.

---

<a name="features"></a>
# 🚀 Features

✅ Synthetic Dataset Generation

✅ Probability Analysis

✅ Empirical Probability

✅ Theoretical Probability

✅ Random Variable Modeling

✅ Binomial Distribution

✅ Mean & Variance Calculation

✅ Venn Diagram Analysis

✅ Contingency Tables

✅ Joint Probability

✅ Marginal Probability

✅ Conditional Probability

✅ Independence Testing

✅ Bayes Theorem Application

✅ Data Visualization

✅ CSV Export

---

<a name="dataset-attributes"></a>
# 📊 Dataset Attributes

| Feature | Description |
|----------|-------------|
| study_hours | Number of study hours per week |
| attendance | Attendance percentage |
| group_discussion | Participation in group discussions |
| previous_test_score | Marks obtained in previous test |
| final_exam_pass | Pass or Fail result |

---

<a name="project-structure"></a>
# 📂 Project Structure

```text
Expectation-Decider/
│
├── expectation_decider.py
├── expectation_decider_dataset.csv
├── README.md
│
├── charts/
│   ├── pass_fail_chart.png
│   ├── attendance_histogram.png
│   └── study_vs_score.png
│
└── requirements.txt
```

---

<a name="statistical-concepts-used"></a>
# 🧠 Statistical Concepts Used

This project demonstrates core Probability and Statistics concepts through practical Python implementation.

---

## 1️⃣ Probability

Probability measures the likelihood that an event will occur.

### Formula

```math
P(E)=\frac{Favorable\ Outcomes}{Total\ Outcomes}
```

### Example

Suppose:

- 120 students pass
- Total students = 200

```math
P(Pass)=\frac{120}{200}
```

```math
P(Pass)=0.60
```

Meaning:

There is a **60% chance** that a randomly selected student passes.

### Example from Project

Probability that a student passes the final exam.

### Python Code

```python
P_pass = (
    df["final_exam_pass"] == "Pass"
).mean()

print(P_pass)
```

### How the Code Works

```python
df["final_exam_pass"] == "Pass"
```

Creates a Boolean series:

```text
True
False
True
True
...
```

Internally Python treats:

```text
True = 1
False = 0
```

Therefore:

```python
.mean()
```

Calculates:

```math
\frac{Number\ of\ Passes}
{Total\ Students}
```

which gives the probability of passing.

### Sample Output

```text
0.60
```

Meaning:

Approximately **60% of students passed the exam**.

---

## 2️⃣ Empirical Probability

Empirical probability is calculated using observed data.

### Formula

```math
P(E)=\frac{Number\ of\ Times\ Event\ Occurred}{Total\ Observations}
```

### Example

Suppose:

- 120 students pass
- Total students = 200

```math
P(Pass)=\frac{120}{200}
```

```math
P(Pass)=0.60
```

Meaning:

The observed probability of passing is **60%**.

### Example from Project

Calculate pass probability using generated student data.

### Python Code

```python
empirical_probability = P_pass

print(empirical_probability)
```

### How the Code Works

`P_pass` already contains the proportion of students who passed.

### Sample Output

```text
0.60
```

---

## 3️⃣ Theoretical Probability

Theoretical probability is calculated mathematically before observing data.

### Formula

```math
P(E)=\frac{Favorable\ Outcomes}{Total\ Possible\ Outcomes}
```

### Example

Weekend days:

- Saturday
- Sunday

Total days:

- 7

```math
P(Weekend)=\frac{2}{7}
```

```math
P(Weekend)=0.2857
```

Meaning:

There is a **28.57% chance** of selecting a weekend day.

### Example from Project

Theoretical probability example.

### Python Code

```python
theoretical_probability = 2 / 7

print(theoretical_probability)
```

### How the Code Works

Python divides 2 by 7.

### Sample Output

```text
0.2857
```

---

## 4️⃣ Random Variable

A random variable assigns numerical values to outcomes.

### Formula

```math
X = Number\ of\ students\ passing\ among\ 3\ selected\ students
```

### Example

Possible values:

```text
0,1,2,3
```

### Example from Project

Students passing among 3 selected students.

### Python Code

```python
p = P_pass
n_students = 3

distribution = pd.DataFrame({
    "X": range(4),
    "P(X=x)": [
        binom.pmf(x, n_students, p)
        for x in range(4)
    ]
})

print(distribution)
```

### How the Code Works

Calculates probabilities for:

```text
P(X=0)
P(X=1)
P(X=2)
P(X=3)
```

### Sample Output

```text
X   P(X=x)
0   0.064
1   0.288
2   0.432
3   0.216
```

---

## 5️⃣ Probability Distribution

Shows all possible values of a random variable and their probabilities.

### Formula

```math
P(X=x)=\binom{n}{x}p^x(1-p)^{n-x}
```

### Example

Find probability that exactly 2 out of 3 students pass.

### Python Code

```python
binom.pmf(2, 3, 0.60)
```

### How the Code Works

Calculates:

```math
P(X=2)
```

using Binomial Distribution.

### Sample Output

```text
0.432
```

---

## 6️⃣ Mean of Random Variable

Average expected outcome.

### Formula

```math
\mu=np
```

### Example

```math
(3)(0.60)=1.8
```

### Python Code

```python
mean_x = n_students * p

print(mean_x)
```

### How the Code Works

Multiplies trials by success probability.

### Sample Output

```text
1.8
```

---

## 7️⃣ Variance of Random Variable

Measures spread of outcomes.

### Formula

```math
\sigma^2=np(1-p)
```

### Example

```math
(3)(0.60)(0.40)
```

```math
0.72
```

### Python Code

```python
variance_x = n_students * p * (1 - p)

print(variance_x)
```

### Sample Output

```text
0.72
```

---

## 8️⃣ Venn Diagram Analysis

Used to analyze overlapping groups.

### Example

Set A:

```text
Study Hours > 10
```

Set B:

```text
Attendance > 80%
```

### Python Code

```python
A = df["study_hours"] > 10
B = df["attendance"] > 80

only_A = np.sum(A & ~B)
only_B = np.sum(~A & B)
both = np.sum(A & B)
neither = np.sum(~A & ~B)
```

### How the Code Works

Calculates overlap between study habits and attendance.

---

## 9️⃣ Contingency Table

Compares two categorical variables.

### Example from Project

Group Discussion vs Final Result.

### Python Code

```python
contingency_table = pd.crosstab(
    df["group_discussion"],
    df["final_exam_pass"]
)

print(contingency_table)
```

### How the Code Works

Counts students in each category combination.

---

## 🔟 Joint Probability

Probability of two events occurring together.

### Formula

```math
P(A \cap B)
```

### Example

Student participates in group discussion and passes.

### Python Code

```python
joint_probability = len(
    df[
        (df["group_discussion"] == "Yes")
        &
        (df["final_exam_pass"] == "Pass")
    ]
) / len(df)
```

### Sample Output

```text
0.45
```

---

## 1️⃣1️⃣ Marginal Probability

Probability of a single event.

### Formula

```math
P(A)
```

### Example

Probability of passing.

### Python Code

```python
marginal_probability = len(
    df[df["final_exam_pass"] == "Pass"]
) / len(df)
```

### Sample Output

```text
0.60
```

---

## 1️⃣2️⃣ Conditional Probability

Probability of an event given another event.

### Formula

```math
P(A|B)=\frac{P(A\cap B)}{P(B)}
```

### Example

Probability of passing given group discussion participation.

### Python Code

```python
conditional_probability = (
    len(
        df[
            (df["group_discussion"] == "Yes")
            &
            (df["final_exam_pass"] == "Pass")
        ]
    )
    /
    len(df[df["group_discussion"] == "Yes"])
)
```

### Sample Output

```text
0.75
```

---

## 1️⃣3️⃣ Independent vs Dependent Events

### Formula

```math
P(A\cap B)=P(A)P(B)
```

### Example

Check whether group discussion affects passing.

### Python Code

```python
left_side = joint_probability

right_side = (
    (df["group_discussion"] == "Yes").mean()
    *
    (df["final_exam_pass"] == "Pass").mean()
)
```

### How the Code Works

Compares actual joint probability against expected probability.

---

## 1️⃣4️⃣ Bayes Theorem

Used for prediction.

### Formula

```math
P(Pass|H)=\frac{P(H|Pass) \cdot P(Pass)}{P(H)}
```

### Example

Predict probability of passing with high attendance.

### Python Code

```python
P_H_given_Pass = 0.70
P_H_given_Fail = 0.40
P_H = 0.60

P_Pass_given_H = (
    P_H_given_Pass * P_Pass
) / P_H
```

### Sample Output

```text
0.7778
```

Meaning:

Students with high attendance have approximately **77.78% probability of passing**.

---

## 1️⃣5️⃣ Data Visualization

Visual representations help identify trends and relationships.

### Bar Chart

```python
df["final_exam_pass"].value_counts().plot(
    kind="bar"
)
plt.show()
```

### Histogram

```python
plt.hist(
    df["attendance"],
    bins=10
)
plt.show()
```

### Scatter Plot

```python
plt.scatter(
    df["study_hours"],
    df["previous_test_score"]
)
plt.show()
```

### How the Code Works

- Bar Chart → Pass vs Fail comparison
- Histogram → Attendance distribution
- Scatter Plot → Relationship between study hours and scores

---

<a name="technologies-used"></a>
# 🔬 Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib

---

<a name="installation"></a>
# ⚙️ Installation

```bash
git clone https://github.com/yourusername/Expectation-Decider.git
```

```bash
cd Expectation-Decider
```

```bash
pip install numpy pandas scipy matplotlib
```

---

<a name="how-to-run"></a>
# ▶️ How to Run

```bash
python expectation_decider.py
```

---

<a name="visualizations"></a>
# 📈 Visualizations

The project generates:

### Pass vs Fail Distribution

```text
Bar Chart
```

### Attendance Distribution

```text
Histogram
```

### Study Hours vs Previous Test Score

```text
Scatter Plot
```

---

<a name="sample-results"></a>
# 📋 Sample Results

| Metric | Value |
|----------|---------|
| Pass Probability | 0.60 |
| Attendance >80% | 0.45 |
| Group Discussion Participation | 0.60 |
| Conditional Probability | 0.75 |
| Bayes Prediction | 0.7778 |

---

<a name="learning-outcomes"></a>
# 📚 Learning Outcomes

After completing this project, you will understand:

- Probability Theory
- Statistical Inference
- Random Variables
- Probability Distributions
- Conditional Probability
- Bayes Theorem
- Data Visualization
- Statistical Decision Making

---

<a name="future-improvements"></a>
# 💡 Future Improvements

- Machine Learning Prediction Models
- Logistic Regression
- Student Risk Analysis
- Interactive Dashboard
- Web Application Deployment
- Real Educational Data Integration

---

<a name="author"></a>
# 👨‍💻 Author

**Your Name**

Data Analytics & Statistics Enthusiast

GitHub: https://github.com/yourusername

---

<a name="support"></a>
# ⭐ Support

If you found this project useful:

⭐ Star the Repository

🍴 Fork the Repository

📢 Share with Others

---

<a name="final-conclusion"></a>
# 🏆 Final Conclusion

The **Expectation Decider** project demonstrates how Probability and Statistics can be used to evaluate student performance and make informed academic predictions.

Through the use of Probability Theory, Binomial Distribution, Conditional Probability, Contingency Tables, and Bayes Theorem, the project provides meaningful insights into the factors that influence exam success and supports data-driven decision-making.

The **Expectation Decider** project demonstrates how Probability and Statistics can be used to make data-driven academic predictions. By combining probability theory, conditional probability, contingency tables, and Bayes theorem, the model provides meaningful insights into student success factors and supports intelligent decision-making.
