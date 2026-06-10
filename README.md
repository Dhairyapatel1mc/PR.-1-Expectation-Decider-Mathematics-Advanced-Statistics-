<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&text=Expectation%20Decider&fontAlign=50&fontAlignY=40&color=gradient" />
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
  <img src="https://img.shields.io/badge/Status-✅ Completed-2ecc71?style=flat-square"/>
  <img src="https://img.shields.io/badge/Course-Mathematics%20%26%20Advanced%20Statistics-e74c3c?style=flat-square"/>
  <img src="https://img.shields.io/badge/Institute-Red%20%26%20White%20Skill%20Education-3498db?style=flat-square"/>
</p>

<h2 align="center">🌐 Connect With Me</h2>
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

# 📌 Table of Contents

<table>
<tr>
<td valign="top" width="60%">

- 🎯 [Project Overview](#-project-overview)
- 🎯 [Project Objectives](#-project-objectives)
- 🚀 [Features](#-features)
- 📊 [Dataset Attributes](#-dataset-attributes)
- 📂 [Project Structure](#-project-structure)
- 🧠 [Statistical Concepts Used](#-statistical-concepts-used)
- 🔬 [Technologies Used](#-technologies-used)
- ⚙️ [Installation](#%EF%B8%8F-installation)
- ▶️ [How to Run](#%EF%B8%8F-how-to-run)
- 📈 [Visualizations](#-visualizations)
- 📋 [Sample Results](#-sample-results)
- 📚 [Learning Outcomes](#-learning-outcomes)
- 💡 [Future Improvements](#-future-improvements)
- 👨‍💻 [Author](#-author)
- ⭐ [Support](#-support)
- 🏆 [Final Conclusion](#-final-conclusion)

</td>
<td valign="top" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="350" alt="coding gif"/>

</td>
</tr>
</table>

---

## 🎯 Project Overview

**Expectation Decider** is a data analytics project built for an educational research institute. The goal is to predict whether a student will pass a competitive mathematics exam by analyzing historical patterns using **Probability and Statistics**.

A synthetic dataset of **200 students** is generated and analyzed across five key dimensions:

- 📖 Study habits
- 🏫 Attendance
- 🤝 Peer interaction
- 📝 Prior performance
- 🎓 Final exam outcome

> 💡 The model does not use machine learning. Every prediction is derived purely from probability theory and statistical formulas, making it a strong foundation for understanding how data drives decisions.

---

## 🎯 Project Objectives

- 📌 Generate and analyze student performance data
- 📌 Apply probability concepts to real-world scenarios
- 📌 Understand random variables and probability distributions
- 📌 Calculate empirical and theoretical probabilities
- 📌 Analyze relationships between variables
- 📌 Use Bayes Theorem for prediction
- 📌 Visualize statistical patterns using charts
- 📌 Develop data-driven decision-making skills

---

## 🚀 Features

| ✅ Feature | 📝 Description |
|---|---|
| 🗂️ Dataset Generation | 200 synthetic student records with realistic distributions |
| 🔢 Probability Analysis | Empirical and theoretical probability from data |
| 📊 Binomial Distribution | Models pass/fail outcomes for 3 random students |
| 🔵 Venn Diagram | Visual overlap of study hours and attendance conditions |
| 📋 Contingency Table | Cross-tabulation with heatmap for group discussion vs exam result |
| 🔗 Independence Test | Checks if group discussion and exam result are related |
| 🧮 Bayes Theorem | Updates pass probability given high attendance evidence |
| 📈 Summary Dashboard | 3-panel visualization showing key patterns |

---

## 📊 Dataset Attributes

| 🏷️ Field | 🔤 Type | 📝 Description |
|---|---|---|
| `study_hours` | Integer | ⏰ Hours studied per week (2–20) |
| `attendance` | Float | 🏫 Lecture attendance percentage (40–100%) |
| `group_discussion` | String | 🤝 Participates in group discussions — Yes / No |
| `previous_test_score` | Integer | 📝 Score out of 100 from last internal test |
| `final_exam_pass` | String | 🎓 Exam outcome — Pass / Fail |

---

## 📂 Project Structure

```
📁 Expectation-Decider/
│
├── 📓 Expectation_Decider.ipynb      # Main notebook — all 7 questions
├── 📄 README.md                      # Project documentation
│
└── 📊 charts/
    ├── q3_distribution.png           # Binomial probability distribution
    ├── q4_venn.png                   # Venn diagram
    ├── q5_contingency.png            # Contingency table heatmap
    ├── q7_bayes.png                  # Bayes theorem comparison
    └── final_summary.png             # 3-panel summary dashboard
```

---

## 🧠 Statistical Concepts Used

---

### 1️⃣ Probability Basics

📌 Probability measures the likelihood that an event will occur. It ranges from **0** (impossible) to **1** (certain).

$$P(E) = \frac{\text{Favorable Outcomes}}{\text{Total Outcomes}}$$

> 💬 **What this means in simple words:**
> Think of probability as answering the question *"how often does this happen out of all possible cases?"*
> If 115 out of 200 students pass the exam, the probability of passing is 115/200 = 0.575 — meaning there is a **57.5% chance** any randomly picked student passes.
> A probability of 0 means it never happens. A probability of 1 means it always happens. Everything in between is a chance.

📚 **Key Probability Terms used in this project:**

| Term | Meaning |
|---|---|
| **Sample Space** | All possible outcomes — here, every student in the dataset |
| **Event** | A specific outcome we are interested in — e.g. "student passes" |
| **Complement** | The opposite of an event — "student fails" |
| **Union (A ∪ B)** | Either A or B or both happen |
| **Intersection (A ∩ B)** | Both A and B happen at the same time |

🔍 Three event examples calculated directly from the dataset:

```python
total = len(df)

# Event A: Student passes the final exam
P_A = (df['final_exam_pass'] == 'Pass').sum() / total

# Event B: Student studies more than 10 hours/week
P_B = (df['study_hours'] > 10).sum() / total

# Event C: Student attends more than 80% of classes
P_C = (df['attendance'] > 80).sum() / total

print('=' * 55)
print('   THREE PROBABILITY EVENT EXAMPLES FROM DATASET')
print('=' * 55)
print(f'Event A - Passes Final Exam          : P(A) = {P_A:.4f}  ({P_A*100:.1f}%)')
print(f'Event B - Studies > 10 hrs/week      : P(B) = {P_B:.4f}  ({P_B*100:.1f}%)')
print(f'Event C - Attendance > 80%           : P(C) = {P_C:.4f}  ({P_C*100:.1f}%)')
print('=' * 55)
```

---

### 2️⃣ Empirical vs Theoretical Probability

- 📊 **Empirical** — observed from actual data
- 📐 **Theoretical** — calculated by assumption (equal outcomes)

> 💬 **What this means in simple words:**
> **Empirical probability** is based on what *actually happened* in real data. You count how many times an event occurred and divide by total observations.
> **Theoretical probability** is based on *assumptions* — like assuming every outcome is equally likely. For example, if we assume any student is equally likely to pass or fail, that gives 50%.
> In real life, empirical always differs from theoretical because factors like study hours and attendance create unequal chances. This is exactly what this project explores.

```python
# Empirical — based on actual observed data
empirical_pass = (df['final_exam_pass'] == 'Pass').sum() / total
print('EMPIRICAL PROBABILITY')
print(f'Observed passes    : {(df["final_exam_pass"]=="Pass").sum()}')
print(f'Total students     : {total}')
print(f'P(Pass) [Empirical]: {empirical_pass:.4f}  ({empirical_pass*100:.1f}%)')

# Theoretical — assuming equally likely outcomes (Pass or Fail)
theoretical_pass = 1 / 2
print('THEORETICAL PROBABILITY')
print(f'P(Pass) [Theoretical]: {theoretical_pass:.4f}  ({theoretical_pass*100:.1f}%)')

print(f'Difference (Empirical - Theoretical): {empirical_pass - theoretical_pass:+.4f}')
```

> ⚠️ Empirical deviates from theoretical because real-world factors — study hours, attendance, and discussion — are not equally likely.

---

### 3️⃣ Random Variable & Binomial Distribution

📌 Let **X = number of students passing out of 3 randomly selected**.
X follows a Binomial distribution: **X ~ B(n=3, p)**

$$P(X=x) = \binom{n}{x} \cdot p^x \cdot (1-p)^{n-x}$$

> 💬 **What this means in simple words:**
> A **random variable** assigns a number to each possible outcome of a random experiment.
> Here, X counts how many students pass when we randomly pick 3 students. X can be 0, 1, 2, or 3.
> We use the **Binomial distribution** because each student independently either passes or fails — just like flipping a coin, but with a probability based on our dataset instead of 50/50.
> The formula tells us: *"what is the chance that exactly x students pass out of n selected, if each has probability p of passing?"*
>
> **Mean E(X) = np** → tells us the *expected* number of students who will pass on average.
> **Variance Var(X) = np(1-p)** → tells us how much that number varies from pick to pick.

```python
from scipy.stats import binom

p        = empirical_pass
n_trials = 3
x_values = [0, 1, 2, 3]

probs = [binom.pmf(x, n_trials, p) for x in x_values]

dist_df = pd.DataFrame({
    'X (No. of Students Passing)': x_values,
    'P(X)'                       : [round(p_, 4) for p_ in probs],
    'X · P(X)'                   : [round(x * p_, 4) for x, p_ in zip(x_values, probs)],
    'X² · P(X)'                  : [round(x**2 * p_, 4) for x, p_ in zip(x_values, probs)]
})

print(f'Random Variable: X = Number of students passing out of n=3')
print(f'Distribution   : X ~ Binomial(n=3, p={p:.4f})')
print(dist_df.to_string(index=False))
```

📐 **Mean and Variance:**

$$\mu = np \qquad \sigma^2 = np(1-p)$$

```python
mean_X     = n_trials * p
variance_X = n_trials * p * (1 - p)
std_X      = np.sqrt(variance_X)

print(f'Mean     E(X) = n * p           = {mean_X:.4f}')
print(f'Variance Var(X) = n * p * (1-p) = {variance_X:.4f}')
print(f'Std Dev  σ(X)  = √Var(X)        = {std_X:.4f}')
```

📊 **Chart:**

```python
colors = ['steelblue', 'mediumseagreen', 'darkorange', 'tomato']
plt.bar(x_values, probs, color=colors, edgecolor='black')
for i, prob in enumerate(probs):
    plt.text(i, prob + 0.005, f'{prob:.4f}', ha='center', fontweight='bold')
plt.xlabel('X = No. of Students Passing (out of 3)')
plt.ylabel('Probability P(X)')
plt.title('Probability Distribution: X ~ Binomial(n=3, p)')
plt.xticks(x_values)
plt.tight_layout()
plt.show()
```

---

### 4️⃣ Venn Diagram

🔵 Visual intersection of two events:
- **A** = Student studies more than 10 hours/week
- **B** = Student attends more than 80% of classes

> 💬 **What this means in simple words:**
> A **Venn diagram** is a visual tool that shows how two groups overlap.
> - The **left circle** represents students who study hard (>10 hrs/week)
> - The **right circle** represents students with high attendance (>80%)
> - The **overlap in the middle** shows students who do BOTH
> - Students outside both circles do neither
>
> This helps us answer questions like: *"Do students who study more also attend more?"* or *"Are these two habits independent of each other?"*
> The larger the overlap, the stronger the connection between the two habits.

```python
set_A = set(df[df['study_hours'] > 10].index)
set_B = set(df[df['attendance']  > 80].index)

only_A  = len(set_A - set_B)
only_B  = len(set_B - set_A)
both_AB = len(set_A & set_B)
neither = total - len(set_A | set_B)

print(f'Set A (study_hours > 10)  : {len(set_A)} students')
print(f'Set B (attendance  > 80%) : {len(set_B)} students')
print(f'A ∩ B (Both conditions)   : {both_AB} students')
print(f'Neither                   : {neither} students')
print(f'P(A)     = {len(set_A)/total:.4f}')
print(f'P(B)     = {len(set_B)/total:.4f}')
print(f'P(A ∩ B) = {both_AB/total:.4f}')
print(f'P(A ∪ B) = {len(set_A|set_B)/total:.4f}')
```

📊 **Chart:**

```python
from matplotlib_venn import venn2

v = venn2(subsets=(only_A, only_B, both_AB),
          set_labels=('Study > 10 hrs/week', 'Attendance > 80%'))
v.get_patch_by_id('10').set_color('steelblue')
v.get_patch_by_id('01').set_color('tomato')
v.get_patch_by_id('11').set_color('mediumpurple')
for patch in v.patches:
    if patch: patch.set_alpha(0.5)
plt.title('Venn Diagram: Study Hours vs Attendance')
plt.tight_layout()
plt.show()
```

---

### 5️⃣ Contingency Table & Probability Calculations

📋 Cross-tabulates **group discussion (Yes/No)** against **exam result (Pass/Fail)**.

> 💬 **What this means in simple words:**
> A **contingency table** is like a scorecard that counts how many students fall into each combination of two categories.
> Here it counts: students who discussed AND passed, discussed AND failed, didn't discuss AND passed, didn't discuss AND failed.
>
> From this one table we can calculate three types of probability:
> - 🔹 **Joint Probability** P(A ∩ B) → chance of BOTH events happening together — *"participates in discussion AND passes"*
> - 🔸 **Marginal Probability** P(A) → chance of just one event regardless of the other — *"passes, no matter if they discussed or not"*
> - 🔺 **Conditional Probability** P(A|B) → chance of one event GIVEN the other already happened — *"passes, knowing they participated in discussion"*

```python
ct = pd.crosstab(df['group_discussion'], df['final_exam_pass'],
                 margins=True, margins_name='Total')
print(ct)

# Joint Probability — participates AND passes
P_GD_and_Pass = ct.loc['Yes', 'Pass'] / ct.loc['Total', 'Total']

# Marginal Probability — passes overall
P_Pass = ct.loc['Total', 'Pass'] / ct.loc['Total', 'Total']

# Conditional Probability — passes given participates in group discussion
P_Pass_given_GD = ct.loc['Yes', 'Pass'] / ct.loc['Yes', 'Total']

print(f'Joint P(GD=Yes ∩ Pass)       = {P_GD_and_Pass:.4f}')
print(f'Marginal P(Pass)             = {P_Pass:.4f}')
print(f'Conditional P(Pass | GD=Yes) = {P_Pass_given_GD:.4f}')
```

🔥 **Heatmap:**

```python
ct_raw = pd.crosstab(df['group_discussion'], df['final_exam_pass'])
sns.heatmap(ct_raw, annot=True, fmt='d', cmap='Blues', linewidths=1)
plt.title('Group Discussion vs Final Exam Pass')
plt.xlabel('Final Exam Result')
plt.ylabel('Group Discussion')
plt.tight_layout()
plt.show()
```

---

### 6️⃣ Understanding Relationships — Independence Test

🔗 Two events are independent if:

$$P(A \cap B) = P(A) \cdot P(B)$$

> 💬 **What this means in simple words:**
> Two events are **independent** if knowing one tells you nothing about the other.
> For example — if flipping heads on a coin doesn't affect the next flip, those flips are independent.
>
> In our dataset, we check: *"Does participating in group discussion affect the chance of passing?"*
> - If **independent**: P(Discussion ∩ Pass) = P(Discussion) × P(Pass) — knowing a student discussed doesn't change their pass probability
> - If **dependent**: The actual joint probability differs from the product — knowing they discussed DOES change the prediction
>
> We also check **mutual exclusivity** — two events are mutually exclusive if they cannot happen at the same time (like a student cannot both pass AND fail). Since students CAN both participate AND pass, these events are NOT mutually exclusive.

```python
P_GD_yes       = total_yes / N
expected_joint = P_GD_yes * P_Pass

print(f'P(Pass | Group Discussion = Yes) = {P_Pass_given_GD:.4f} ({P_Pass_given_GD*100:.1f}%)')
print(f'P(Pass) [Overall]               = {P_Pass:.4f} ({P_Pass*100:.1f}%)')
print()
print(f'P(GD=Yes) * P(Pass) = {expected_joint:.4f}  <- Expected if independent')
print(f'P(GD=Yes ∩ Pass)    = {P_GD_and_Pass:.4f}  <- Actual')

if abs(P_GD_and_Pass - expected_joint) > 0.01:
    print('DEPENDENT — group discussion influences exam result')
else:
    print('INDEPENDENT')

# Mutual exclusivity check
print(f'P(GD=Yes ∩ Pass) = {P_GD_and_Pass:.4f}')
# Since it is not 0, they are NOT mutually exclusive
```

---

### 7️⃣ Bayes Theorem Application

🧮 Updates the probability of passing given high attendance evidence.

$$P(\text{Pass} \mid \text{High Attend}) = \frac{P(\text{High Attend} \mid \text{Pass}) \cdot P(\text{Pass})}{P(\text{High Attend})}$$

> 💬 **What this means in simple words:**
> **Bayes Theorem** lets us *update* our belief about something when we get new evidence.
>
> Before seeing any information about a student, we only know the overall pass rate — this is the **prior probability**.
> But once we learn that a student has **high attendance**, we can update our estimate — this becomes the **posterior probability**.
>
> Think of it like a doctor updating a diagnosis after getting test results:
> - Before the test: the base rate of the disease
> - After a positive test: the updated probability the patient has it
>
> In our case:
> - **Prior**: overall pass rate (~57.5%)
> - **New evidence**: student has high attendance (>80%)
> - **Posterior**: updated pass probability (~67%)
>
> The formula works by asking: *"Among all students with high attendance, what fraction actually passed?"* — and it derives that from the reverse probability we already know.

📌 Given historical data:
- P(High Attendance | Pass) = 0.70
- P(High Attendance | Fail) = 0.40
- P(High Attendance) = 0.60

```python
P_HA_given_Pass = 0.70
P_HA_given_Fail = 0.40
P_HA            = 0.60

P_pass_prior = empirical_pass
P_fail_prior = 1 - P_pass_prior

P_Pass_given_HA = (P_HA_given_Pass * P_pass_prior) / P_HA

print(f'P(Pass | HA) = ({P_HA_given_Pass} * {P_pass_prior:.4f}) / {P_HA}')
print(f'             = {P_Pass_given_HA:.4f} ({P_Pass_given_HA*100:.2f}%)')
```

📊 **Chart:**

```python
P_low_HA_given_Pass = 1 - P_HA_given_Pass
P_low_HA            = 1 - P_HA
P_Pass_given_LowHA  = (P_low_HA_given_Pass * P_pass_prior) / P_low_HA

labels = ['P(Pass) Prior', 'P(Pass|High Attend)', 'P(Pass|Low Attend)']
values = [P_pass_prior, P_Pass_given_HA, P_Pass_given_LowHA]
colors = ['steelblue', 'mediumseagreen', 'tomato']

plt.bar(labels, values, color=colors, edgecolor='black')
for i, v in enumerate(values):
    plt.text(i, v + 0.01, f'{v:.4f}', ha='center', fontweight='bold')
plt.ylabel('Probability of Passing')
plt.title("Bayes' Theorem: Effect of Attendance on P(Pass)")
plt.ylim(0, 1.1)
plt.tight_layout()
plt.show()
```

✅ **Result — a student with high attendance has ~67% probability of passing.**

---

### 🔟 Final Summary Dashboard

> 💬 **What this shows:**
> Three charts side by side that summarize the entire analysis:
> - 🥧 **Pie chart** — overall split of how many students passed vs failed
> - 📊 **Bar chart 1** — compares pass rates between students who joined group discussions vs those who didn't
> - 📊 **Bar chart 2** — shows how pass rates increase as study hours increase, confirming that studying more directly improves outcomes

```python
fig, axes = plt.subplots(1, 3, figsize=(14, 4))
fig.suptitle('Expectation Decider - Final Summary', fontsize=14, fontweight='bold')

# Chart 1: Pass/Fail pie
counts = df['final_exam_pass'].value_counts()
axes[0].pie(counts, labels=counts.index, autopct='%1.1f%%',
            colors=['mediumseagreen', 'tomato'], startangle=90)
axes[0].set_title('Pass/Fail Split')

# Chart 2: Pass rate by group discussion
df['passed'] = (df['final_exam_pass'] == 'Pass').astype(int) * 100
sns.barplot(data=df, x='group_discussion', y='passed',
            palette=['tomato', 'steelblue'], ax=axes[1], errorbar=None)
axes[1].set_title('Pass Rate by Group Discussion')
axes[1].set_ylabel('Pass Rate (%)')
axes[1].set_xlabel('Group Discussion')
axes[1].set_ylim(0, 100)

# Chart 3: Pass rate by study hours
df['study_group'] = pd.cut(df['study_hours'], bins=[0, 5, 10, 15, 20],
                            labels=['0-5', '6-10', '11-15', '16-20'])
sns.barplot(data=df, x='study_group', y='passed',
            palette=['tomato', 'goldenrod', 'steelblue', 'mediumseagreen'],
            ax=axes[2], errorbar=None, order=['0-5', '6-10', '11-15', '16-20'])
axes[2].set_title('Pass Rate by Study Hours')
axes[2].set_xlabel('Study Hours Group')
axes[2].set_ylabel('Pass Rate (%)')
axes[2].set_ylim(0, 100)

plt.tight_layout()
plt.show()

results = {
    'Overall Pass Rate'                 : f'{empirical_pass*100:.1f}%',
    'P(Pass | Group Discussion = Yes)'  : f'{P_Pass_given_GD*100:.1f}%',
    'P(Pass | High Attendance) [Bayes]' : f'{P_Pass_given_HA*100:.1f}%',
    'Mean E(X) out of 3 students'       : f'{mean_X:.4f}',
    'Variance Var(X)'                   : f'{variance_X:.4f}',
}

print('=' * 55)
print('FINAL SUMMARY - KEY FINDINGS')
print('=' * 55)
for i, (k, v) in enumerate(results.items(), 1):
    print(f'{i}. {k:40s}: {v}')

factors = ['High attendance (>80%)', 'Group discussion participation',
           'More study hours', 'High previous test score']
print('Factors most affecting probability of passing:')
for f in factors:
    print(f'  - {f}')
print('=' * 55)
```

---

## 🔬 Technologies Used

| 🛠️ Tool | 🎯 Purpose |
|---|---|
| 🐍 Python 3.10+ | Core programming language |
| 🔢 NumPy | Dataset generation and numerical operations |
| 🐼 Pandas | Data manipulation and contingency tables |
| 📐 SciPy | Binomial probability mass function |
| 📊 Matplotlib | All charts and visualizations |
| 🎨 Seaborn | Heatmaps and styled bar plots |
| 🔵 matplotlib-venn | Venn diagram rendering |
| 📓 Jupyter Notebook | Interactive analysis environment |

---

## ⚙️ Installation

```bash
git clone https://github.com/Dhairyapatel1mc/Expectation-Decider.git
cd Expectation-Decider
pip install numpy pandas scipy matplotlib seaborn matplotlib-venn
```

---

## ▶️ How to Run

```bash
jupyter notebook Expectation_Decider.ipynb
```

🚀 Then select **Cell > Run All** to execute every question in order.

---

## 📈 Visualizations

| 📊 Chart | 🖼️ Type | 🔍 What It Shows |
|---|---|---|
| Probability Distribution | Bar Chart | P(X=0,1,2,3) for Binomial(n=3, p) |
| Venn Diagram | Venn | Overlap of study hours > 10 and attendance > 80% |
| Contingency Heatmap | Heatmap | Group discussion vs exam result counts |
| Bayes Comparison | Bar Chart | Prior vs posterior pass probability |
| Final Summary | 3-panel | Pass/Fail split, group discussion rate, study hour brackets |

---

## 📋 Sample Results

| 📌 Metric | 📊 Value |
|---|---|
| 🎓 Overall Pass Rate | ~57.5% |
| 🤝 P(Pass given Group Discussion = Yes) | ~62% |
| 🏫 P(Pass given High Attendance) via Bayes | ~67% |
| 📐 Mean E(X) — students passing out of 3 | ~1.72 |
| 📉 Variance Var(X) | ~0.73 |
| 🔗 Events: Group Discussion & Pass | Dependent |

---

## 📚 Learning Outcomes

Completing this project builds understanding of:

- 🎯 Translating real-world scenarios into probability problems
- 📊 Working with random variables and probability distributions
- 📋 Building and reading contingency tables
- 🧮 Applying Bayes Theorem to update beliefs with evidence
- 🔗 Testing for statistical independence between two events
- 📈 Communicating findings through charts and summaries

---

## 💡 Future Improvements

- 🤖 Add Logistic Regression to compare with probability-based predictions
- 🌐 Build an interactive Streamlit dashboard
- 📂 Integrate real anonymized student data
- 🏷️ Extend to multi-class prediction (grade bands instead of pass/fail)
- 📉 Add confidence intervals around probability estimates

---

## 👨‍💻 Author

**Ghost — Patel Dhairya**

🎓 B.Tech Artificial Intelligence | Gandhinagar University | Roll No. 250101030119

💻 Passionate about data analytics, probability, and building intelligent systems.

🔗 GitHub — [Dhairyapatel1mc](https://github.com/Dhairyapatel1mc)

📌 *Submitted via RWSkill — Mathematics & Advanced Statistics coursework*

---

## ⭐ Support

If this project helped you:

- ⭐ Star the repository
- 🍴 Fork it and build on top
- 📢 Share it with your batchmates

---

## 🏆 Final Conclusion

**Expectation Decider** proves that you do not need machine learning to make meaningful predictions — probability theory alone is powerful.

By combining empirical observation, binomial modeling, conditional reasoning, and Bayes Theorem, the project answers a real question: *what actually determines whether a student passes?*

The analysis points to four clear answers:

1. 🏫 **Attendance above 80%** is the strongest single predictor
2. 🤝 **Group discussion participation** shows a significant dependent relationship with passing
3. 📖 **Studying more than 10 hours per week** consistently raises pass rates across all brackets
4. 📝 **A strong previous test score** provides a reliable performance baseline

> 📊 Statistics is not just about formulas — it is about turning data into decisions.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=timeGradient&section=footer"/>
</p>
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
