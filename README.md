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
├── expectation_decider.ipynb
├── expectation_decider_dataset.xls
├── README.md
│
├── charts/
│   ├── attendance_distribution.png
│   ├── pass_vs_fail.png
│   └── study_hours_vs_test_score.png
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

### Example from Project

Probability that a student passes the final exam.

### Python Code

```python
P_pass = (df["final_exam_pass"] == "Pass").mean()

print(P_pass)
```

---

## 2️⃣ Empirical Probability

Calculated using actual observed data.

### Example

Probability of passing based on generated student records.

### Python Code

```python
empirical_probability = P_pass

print(empirical_probability)
```

---

## 3️⃣ Theoretical Probability

Calculated mathematically without observed data.

### Example

Probability of selecting a weekend day from a week.

```math
P(Weekend)=\frac{2}{7}
```

### Python Code

```python
theoretical_probability = 2 / 7

print(theoretical_probability)
```

---

## 4️⃣ Random Variable

Define:

```math
X = Number\ of\ students\ passing\ among\ 3\ randomly\ selected\ students
```

Possible values:

```text
0, 1, 2, 3
```

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

---

## 5️⃣ Probability Distribution

The project models passing students using a Binomial Distribution.

### Formula

```math
P(X=x)=\binom{n}{x}p^x(1-p)^{n-x}
```

### Python Code

```python
from scipy.stats import binom

for x in range(4):
    print(
        x,
        binom.pmf(
            x,
            n_students,
            p
        )
    )
```

---

## 6️⃣ Mean of Random Variable

Expected number of passing students.

### Formula

```math
\mu=np
```

### Python Code

```python
mean_x = n_students * p

print(mean_x)
```

---

## 7️⃣ Variance of Random Variable

Measures spread in outcomes.

### Formula

```math
\sigma^2=np(1-p)
```

### Python Code

```python
variance_x = n_students * p * (1 - p)

print(variance_x)
```

---

## 8️⃣ Venn Diagram Analysis

Used to analyze overlap between:

- Students studying more than 10 hours
- Students with attendance above 80%

### Python Code

```python
A = df["study_hours"] > 10
B = df["attendance"] > 80

only_A = np.sum(A & ~B)
only_B = np.sum(~A & B)
both = np.sum(A & B)
neither = np.sum(~A & ~B)

print(only_A)
print(only_B)
print(both)
print(neither)
```

### Example

```text
Only Study >10 Hours
Only Attendance >80%
Both Conditions
Neither Condition
```

---

## 9️⃣ Contingency Table

Used to compare:

- Group Discussion Participation
- Final Exam Result

### Python Code

```python
contingency_table = pd.crosstab(
    df["group_discussion"],
    df["final_exam_pass"]
)

print(contingency_table)
```

### Example Output

```text
final_exam_pass  Fail  Pass
group_discussion
No                45    35
Yes               65    55
```

---

## 🔟 Joint Probability

Probability of:

```text
Participates in Group Discussion
AND
Passes Exam
```

### Formula

```math
P(A\cap B)
```

### Python Code

```python
joint_probability = len(
    df[
        (df["group_discussion"] == "Yes")
        &
        (df["final_exam_pass"] == "Pass")
    ]
) / len(df)

print(joint_probability)
```

---

## 1️⃣1️⃣ Marginal Probability

Probability of a single event.

### Example

Probability that a student passes.

### Python Code

```python
marginal_probability = len(
    df[df["final_exam_pass"] == "Pass"]
) / len(df)

print(marginal_probability)
```

---

## 1️⃣2️⃣ Conditional Probability

Probability that a student passes given participation in group discussion.

### Formula

```math
P(A|B)=\frac{P(A\cap B)}{P(B)}
```

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
    len(
        df[
            df["group_discussion"] == "Yes"
        ]
    )
)

print(conditional_probability)
```

---

## 1️⃣3️⃣ Independent vs Dependent Events

Check whether:

```text
Group Discussion
```

and

```text
Passing Exam
```

are independent.

### Formula

```math
P(A\cap B)=P(A)P(B)
```

### Python Code

```python
left_side = joint_probability

right_side = (
    (df["group_discussion"] == "Yes").mean()
    *
    (df["final_exam_pass"] == "Pass").mean()
)

if abs(left_side - right_side) < 0.02:
    print("Independent")
else:
    print("Dependent")
```

---

## 1️⃣4️⃣ Bayes Theorem

Used to predict the probability of passing when attendance is high.

### Formula

```math
P(A|B)=\frac{P(B|A)P(A)}{P(B)}
```

### Python Code

```python
P_H_given_Pass = 0.70
P_H_given_Fail = 0.40
P_H = 0.60

P_Pass = (
    (P_H - P_H_given_Fail)
    /
    (P_H_given_Pass - P_H_given_Fail)
)

P_Pass_given_H = (
    P_H_given_Pass * P_Pass
) / P_H

print(P_Pass_given_H)
```

### Output

```text
0.7778
```

Meaning:

A student with high attendance has approximately **77.78% probability of passing**.

---

## 1️⃣5️⃣ Data Visualization

The project visualizes statistical patterns using charts.

### Pass vs Fail Distribution

```python
df["final_exam_pass"].value_counts().plot(kind="bar")
plt.show()
```

### Attendance Distribution

```python
plt.hist(df["attendance"], bins=10)
plt.show()
```

### Study Hours vs Previous Score

```python
plt.scatter(
    df["study_hours"],
    df["previous_test_score"]
)
plt.show()
```

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
jupyter expectation_decider.ipynb
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

Patel Dhairya

Data Analytics & Statistics Enthusiast

GitHub: https://github.com/Dhairyapatel1mc

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
