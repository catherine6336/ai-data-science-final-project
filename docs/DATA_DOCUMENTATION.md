# Data Documentation

## 1. Dataset Name

**Dataset Name:**  2023 ASCII 

---

## 2. Data Source

**Organization / Website:**  CDC

**Dataset URL:**  https://www.cdc.gov/yrbs/files/2023/XXH2023_YRBS_Data.dat

**Date Accessed:**  9/2/2026

Example:

```text
Organization: UCI Machine Learning Repository
URL: https://...
Date Accessed: 2026-09-12
```

---

## 3. Why I Chose This Dataset

Explain why this dataset is useful for your project.

Write 2–4 sentences.
This data set is useful for my project because it has many rows and many questions that pertain to the topic I'd like to learn about. For example, it has questions about average amount of sleep (in hours), average screentime (in hours), mental health (on a scale of 1-10), etc. 

---

## 4. Dataset Overview

| Item | Description |
|---|---|
| Number of rows | |
| Number of columns | |
| File format | CSV / Excel / JSON / Other |
| Target variable | |
| Main feature types | Numerical / Categorical / Image / Text / Other |

| Item | Description |
|---|---|
| Number of rows | 20103 |
| Number of columns | 156 |
| File format | CSV |
| Target variable | Q84 |
| Main feature types | Numerical / Categorical / Image / Text / Other | I think Numerical

---

## 5. What Does One Row Represent?

Each row in the dataset represents one person's response to the survey.

Example:

> Each row represents one person and contains information about eating habits, physical activity, and weight category.

---

## 6. Important Variables

Describe the most important columns.

| Variable | Meaning | Type | Example |
|---|---|---|---|
| sleep | Hours of sleep | Numerical | 5 |
| health | mental health rating on a scale from 1-5 | Numerical | 2 |
| screen_time | Amount of social media use on a scale from 1-8 | Numerical | 6 |

Add or remove rows as needed.

---

## 7. Target Variable

Complete this section if your project predicts something.

**Target Variable:**  Q84

**What does it represent?** In the dataset, Q84 represents a response in the survey to the question about mental health: "During the past 30 days, how often was your mental health not good?" The answers and possible values range from 1-5, where 1 means "Never" and 5 means "Always."

Write a short explanation.

**Possible target values:**

- 
- 
- 

---

## 8. Data Quality

### Missing Values

Are there missing values?

- [✓] Yes
- [ ] No
- [ ] I have not checked yet

If yes, explain:

---

### Duplicate Rows

Are there duplicate records?

- [ ] Yes
- [✓] No
- [ ] I have not checked yet

---

### Unusual or Incorrect Values

Did you find possible errors or unusual values?

Examples:

- Negative ages
- Impossible measurements
- Extreme outliers
- Incorrect categories

**Notes:**

Didn't find any. 

## 9. Data Cleaning

Describe what you changed.

| Cleaning Step | What I Did | Why |
|---|---|---|
| Missing values | | |
| Duplicate records | | |
| Data types | | |
| Category names | | |
| Outliers | | |

---

## 10. Feature Preparation

Describe any changes made before analysis or machine learning.

Examples:

- Converted categories into numbers
- Created new features
- Normalized numerical values
- Removed unnecessary columns

**Changes Made:**

1.  
2.  
3.  

---

## 11. Train/Test Split

Complete this section if using machine learning.

**Training Data:** _____ %

**Testing Data:** _____ %

**Random Seed:**  

Example:

```text
Training: 80%
Testing: 20%
random_state = 42
```

---

## 12. Possible Data Limitations

Every dataset has limitations.

Think about:

- Is the dataset small?
- Does it represent only certain populations?
- Could the data contain bias?
- Were some values self-reported?
- Are important variables missing?
- Can the results be generalized to everyone?

**Limitations:**

1.  
2.  
3.  

---

## 13. Responsible Use of the Data

Consider privacy, fairness, and responsible AI.

**Does the dataset contain personal information?**

- [ ] Yes
- [ ] No
- [ ] Unsure

**Could the dataset contain bias?**

- [ ] Yes
- [ ] No
- [ ] Unsure

**Responsible-use notes:**

Write 2–4 sentences.

---

## 14. Data Files in This Project

| File | Purpose |
|---|---|
| `raw_data.csv` | Original dataset |
| `cleaned_data.csv` | Cleaned dataset |
| `data_analysis.ipynb` | Data exploration and analysis |

Modify these names to match your project.

---

## 15. Reproducibility

Someone reviewing this project should be able to understand:

- Where the data came from
- What each important variable means
- What cleaning was performed
- What features were changed or created
- What limitations exist
- How the final dataset was produced

**Code used to prepare the data is located in:**

```text
Enter file or notebook name here
```

---

## 16. References

List the dataset source and any documentation you used.

1. Dataset:
2. Dataset documentation:
3. Other references:
