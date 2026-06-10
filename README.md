<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Expectation%20Decider&fontAlign=50&fontAlignY=40&color=timeGradient&fontColor=ffffff&fontSize=45&desc=Probability%20%26%20Statistics%20|%20Student%20Performance%20Analysis&descAlign=50&descAlignY=62&descSize=16" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-Scientific_Computing-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-Statistics-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-2ecc71?style=flat-square"/>
  <img src="https://img.shields.io/badge/Course-Mathematics%20%26%20Advanced%20Statistics-e74c3c?style=flat-square"/>
  <img src="https://img.shields.io/badge/Institute-Red%20%26%20White%20Skill%20Education-3498db?style=flat-square"/>
</p>

---

<h2 align="center">Connect With Me</h2>

<p align="center">
  <a href="https://www.instagram.com/ghost_6927/?hl=en" target="_blank">
    <img src="https://skillicons.dev/icons?i=instagram" height="50" alt="Instagram"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/ghost-patel-0267663b7/" target="_blank">
    <img src="https://skillicons.dev/icons?i=linkedin" height="50" alt="LinkedIn"/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/Dhairyapatel1mc" target="_blank">
    <img src="https://skillicons.dev/icons?i=github" height="50" alt="GitHub"/>
  </a>
</p>

---

# Table of Contents

<table>
<tr>
<td valign="top" width="60%">

- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Features](#features)
- [Dataset Attributes](#dataset-attributes)
- [Project Structure](#project-structure)
- [Statistical Concepts Used](#statistical-concepts-used)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Run](#how-to-run)
- [Visualizations](#visualizations)
- [Sample Results](#sample-results)
- [Learning Outcomes](#learning-outcomes)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [Support](#support)
- [Final Conclusion](#final-conclusion)

</td>
<td valign="top" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="350" alt="coding gif"/>

</td>
</tr>
</table>

---

<a name="project-overview"></a>
## Project Overview

**Expectation Decider** is a data analytics project built for an educational research institute. The goal is to predict whether a student will pass a competitive mathematics exam by analyzing historical patterns using **Probability and Statistics**.

A synthetic dataset of **200 students** is generated and analyzed across five key dimensions — study habits, attendance, peer interaction, prior performance, and final exam outcome.

> The model does not use machine learning. Every prediction is derived purely from probability theory and statistical formulas, making it a strong foundation for understanding how data drives decisions.

---

<a name="project-objectives"></a>
## Project Objectives

- Analyze student performance data using probability techniques
- Build a full probability analysis pipeline from scratch in Python
- Calculate empirical, theoretical, conditional, joint, and marginal probabilities
- Apply Bayes Theorem to update predictions based on evidence
- Visualize distributions, relationships, and statistical summaries
- Identify the key factors that influence a student's chance of passing

---

<a name="features"></a>
## Features

| Feature | Description |
|---|---|
| Dataset Generation | 200 synthetic student records with realistic distributions |
| Probability Analysis | Empirical and theoretical probability from data |
| Binomial Distribution | Models pass/fail outcomes for 3 random students |
| Venn Diagram | Visual overlap of study hours and attendance conditions |
| Contingency Table | Cross-tabulation with heatmap for group discussion vs exam result |
| Independence Test | Checks if group discussion and exam result are related |
| Bayes Theorem | Updates pass probability given high attendance evidence |
| Summary Dashboard | 3-panel visualization showing key patterns |

---

<a name="dataset-attributes"></a>
## Dataset Attributes

| Field | Type | Description |
|---|---|---|
| `study_hours` | Integer | Hours studied per week (2–20) |
| `attendance` | Float | Lecture attendance percentage (40–100%) |
| `group_discussion` | String | Participates in group discussions — Yes / No |
| `previous_test_score` | Integer | Score out of 100 from last internal test |
| `final_exam_pass` | String | Exam outcome — Pass / Fail |

The dataset is generated using `numpy.random` with a weighted pass probability formula based on all four input features.

---

<a name="project-structure"></a>
## Project Structure

```
Expectation-Decider/
│
├── Expectation_Decider.ipynb      # Main notebook — all 7 questions
├── README.md                      # Project documentation
│
└── charts/
    ├── q3_distribution.png        # Binomial probability distribution
    ├── q4_venn.png                # Venn diagram
    ├── q5_contingency.png         # Contingency table heatmap
    ├── q7_bayes.png               # Bayes theorem comparison
    └── final_summary.png          # 3-panel summary dashboard
```

---

<a name="statistical-concepts-used"></a>
## Statistical Concepts Used

---

### 1 — Probability Basics

Probability quantifies uncertainty. It ranges from 0 (impossible) to 1 (certain).

$$P(E) = \frac{\text{Favorable Outcomes}}{\text{Total Outcomes}}$$

Three event examples from the dataset:

```python
P_pass     = (df["final_exam_pass"] == "Pass").sum() / len(df)
P_study10  = (df["study_hours"] > 10).sum() / len(df)
P_attend80 = (df["attendance"] > 80).sum() / len(df)
```

---

### 2 — Empirical vs Theoretical Probability

**Empirical** — observed from actual data.
**Theoretical** — calculated by assumption (equal outcomes).

```python
empirical_pass    = (df["final_exam_pass"] == "Pass").sum() / len(df)
theoretical_pass  = 1 / 2
```

Empirical deviates from theoretical because real-world conditions (study, attendance, discussion) are not equally likely.

---

### 3 — Random Variable & Binomial Distribution

Let X = number of students passing out of 3 randomly selected.
X follows a Binomial distribution: **X ~ B(n=3, p)**

$$P(X=x) = \binom{n}{x} \cdot p^x \cdot (1-p)^{n-x}$$

```python
from scipy.stats import binom

probs = [binom.pmf(x, 3, empirical_pass) for x in range(4)]
```

**Mean and Variance:**

$$\mu = np \qquad \sigma^2 = np(1-p)$$

```python
mean_X     = 3 * empirical_pass
variance_X = 3 * empirical_pass * (1 - empirical_pass)
```

---

### 4 — Venn Diagram

Visual intersection of two events:
- **A** = Student studies more than 10 hours/week
- **B** = Student attends more than 80% of classes

```python
A = df["study_hours"] > 10
B = df["attendance"]  > 80

only_A  = (A & ~B).sum()
only_B  = (~A & B).sum()
both    = (A & B).sum()
neither = (~A & ~B).sum()
```

---

### 5 — Contingency Table & Probabilities

Cross-tabulates group discussion (Yes/No) against exam result (Pass/Fail).

```python
ct = pd.crosstab(df["group_discussion"], df["final_exam_pass"])
```

From the table:

```python
# Joint probability — participates AND passes
P_joint = ct.loc["Yes", "Pass"] / len(df)

# Marginal probability — passes overall
P_pass = ct["Pass"].sum() / len(df)

# Conditional probability — passes given participates
P_cond = ct.loc["Yes", "Pass"] / ct.loc["Yes", :].sum()
```

---

### 6 — Independence Test

Two events are independent if:

$$P(A \cap B) = P(A) \cdot P(B)$$

```python
expected = (df["group_discussion"] == "Yes").mean() * (df["final_exam_pass"] == "Pass").mean()
actual   = P_joint

if abs(actual - expected) > 0.01:
    print("Dependent — group discussion influences exam result")
else:
    print("Independent")
```

---

### 7 — Bayes Theorem

Updates the probability of passing given high attendance evidence.

$$P(\text{Pass} \mid \text{High Attend}) = \frac{P(\text{High Attend} \mid \text{Pass}) \cdot P(\text{Pass})}{P(\text{High Attend})}$$

Given:
- P(High Attendance | Pass) = 0.70
- P(High Attendance | Fail) = 0.40
- P(High Attendance) = 0.60

```python
P_HA_given_Pass = 0.70
P_HA            = 0.60

P_Pass_given_HA = (P_HA_given_Pass * empirical_pass) / P_HA
```

**Result — a student with high attendance has ~67% probability of passing.**

---

<a name="technologies-used"></a>
## Technologies Used

| Tool | Purpose |
|---|---|
| Python 3.10+ | Core programming language |
| NumPy | Dataset generation and numerical operations |
| Pandas | Data manipulation and contingency tables |
| SciPy | Binomial probability mass function |
| Matplotlib | All charts and visualizations |
| Seaborn | Heatmaps and styled bar plots |
| matplotlib-venn | Venn diagram rendering |
| Jupyter Notebook | Interactive analysis environment |

---

<a name="installation"></a>
## Installation

```bash
git clone https://github.com/Dhairyapatel1mc/Expectation-Decider.git
cd Expectation-Decider
pip install numpy pandas scipy matplotlib seaborn matplotlib-venn
```

---

<a name="how-to-run"></a>
## How to Run

```bash
jupyter notebook Expectation_Decider.ipynb
```

Then select **Cell > Run All** to execute every question in order.

---

<a name="visualizations"></a>
## Visualizations

| Chart | Type | What It Shows |
|---|---|---|
| Probability Distribution | Bar Chart | P(X=0,1,2,3) for Binomial(n=3, p) |
| Venn Diagram | Venn | Overlap of study hours > 10 and attendance > 80% |
| Contingency Heatmap | Heatmap | Group discussion vs exam result counts |
| Bayes Comparison | Bar Chart | Prior vs posterior pass probability |
| Final Summary | 3-panel | Pass/Fail split, group discussion rate, study hour brackets |

---

<a name="sample-results"></a>
## Sample Results

| Metric | Value |
|---|---|
| Overall Pass Rate | ~57.5% |
| P(Pass given Group Discussion = Yes) | ~62% |
| P(Pass given High Attendance) via Bayes | ~67% |
| Mean E(X) — students passing out of 3 | ~1.72 |
| Variance Var(X) | ~0.73 |
| Events: Group Discussion & Pass | Dependent |

---

<a name="learning-outcomes"></a>
## Learning Outcomes

Completing this project builds understanding of:

- Translating real-world scenarios into probability problems
- Working with random variables and probability distributions
- Building and reading contingency tables
- Applying Bayes Theorem to update beliefs with evidence
- Testing for statistical independence between two events
- Communicating findings through charts and summaries

---

<a name="future-improvements"></a>
## Future Improvements

- Add Logistic Regression to compare with probability-based predictions
- Build an interactive Streamlit dashboard
- Integrate real anonymized student data
- Extend to multi-class prediction (grade bands instead of pass/fail)
- Add confidence intervals around probability estimates

---

<a name="author"></a>
## Author

**Ghost — Patel Dhairya**

B.Tech Artificial Intelligence | Gandhinagar University | Roll No. 250101030119

Passionate about data analytics, probability, and building intelligent systems.

GitHub — [Dhairyapatel1mc](https://github.com/Dhairyapatel1mc)

*Submitted via RWSkill — Mathematics & Advanced Statistics coursework*

---

<a name="support"></a>
## Support

If this project helped you:

- Star the repository
- Fork it and build on top
- Share it with your batchmates

---

<a name="final-conclusion"></a>
## Final Conclusion

**Expectation Decider** proves that you do not need machine learning to make meaningful predictions — probability theory alone is powerful.

By combining empirical observation, binomial modeling, conditional reasoning, and Bayes Theorem, the project answers a real question: *what actually determines whether a student passes?*

The analysis points to four clear answers:

1. **Attendance above 80%** is the strongest single predictor
2. **Group discussion participation** shows a significant dependent relationship with passing
3. **Studying more than 10 hours per week** consistently raises pass rates across all brackets
4. **A strong previous test score** provides a reliable performance baseline

Statistics is not just about formulas — it is about turning data into decisions.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=timeGradient&section=footer"/>
</p>
