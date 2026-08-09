# Brain Tumour Analysis: Confirmed vs Unconfirmed Cases

## Project Overview

This project presents an exploratory and comparative analysis of brain tumour cases, examining how **diagnostic confirmation status** relates to tumour grade, tumour type, anatomical location, patient age, tumour size, and diagnosis trends over time.

Rather than excluding unconfirmed cases from the analysis, this project examines them alongside confirmed cases to understand whether they demonstrate similar patterns across key clinical and demographic variables.

The analysis is designed to demonstrate how **health data analytics can move beyond descriptive statistics to generate clinically relevant and policy-oriented insights**.

---

## Project Objectives

The analysis aimed to:

* Examine the distribution of brain tumour cases across Grades 1–4.
* Compare confirmed and unconfirmed cases.
* Identify the most common tumour types within each grade.
* Examine tumour distribution across anatomical brain regions.
* Identify the age groups most affected by each tumour grade.
* Analyse average tumour size across tumour grades.
* Examine annual variations in diagnosis volume.
* Identify patterns that may be relevant to healthcare planning and resource allocation.
* Demonstrate the importance of retaining unconfirmed cases in exploratory health data analysis.

---

## Key Analytical Questions

The project was guided by the following questions:

1. How are brain tumour cases distributed across tumour grades?
2. Which tumour types dominate each grade?
3. Which brain regions are most frequently affected?
4. Which age groups carry the greatest burden across tumour grades?
5. How does average tumour size vary by tumour grade?
6. How does the annual number of cases vary over time?
7. How similar are confirmed and unconfirmed cases?
8. What potential implications do these patterns have for healthcare planning and data management?

---

# Dataset

The dataset contains brain tumour records covering a **10-year period**.

Key analytical variables include:

| Variable            | Description                   |
| ------------------- | ----------------------------- |
| Tumour Grade        | Grade 1–4 classification      |
| Confirmation Status | Confirmed or unconfirmed      |
| Tumour Type         | Classification of tumour      |
| Brain Region        | Anatomical location of tumour |
| Age                 | Patient age                   |
| Age Group           | Categorized age range         |
| Tumour Size         | Recorded tumour size          |
| Diagnosis Year      | Year of diagnosis             |

> **Note:** This project focuses on descriptive and exploratory analysis. The observed patterns should not automatically be interpreted as causal relationships.

---

# Analytical Approach

The analysis followed a structured exploratory data analysis workflow.

### 1. Data Preparation

The dataset was reviewed and structured around:

* Tumour grade
* Confirmation status
* Tumour type
* Brain region
* Age
* Tumour size
* Diagnosis year

### 2. Cohort Segmentation

Cases were divided into:

* **Confirmed cases**
* **Unconfirmed cases**

Each cohort was subsequently analysed by tumour grade.

### 3. Descriptive Analysis

For each grade, the following metrics were examined:

* Total number of patients
* Average annual intake
* Average patient age
* Average tumour size
* Tumour-type distribution
* Brain-region distribution
* Age-group distribution
* Annual diagnosis trends

### 4. Comparative Analysis

Confirmed and unconfirmed cohorts were compared to identify similarities and differences in their:

* Demographic profiles
* Tumour characteristics
* Anatomical distribution
* Temporal patterns

---

# Key Findings

## Grade 1

![](https://github.com/Cuteod/Brain-Tumour-Analysis-Confirmed-vs-Unconfirmed-Cases/blob/main/Brain%20Tumour.png)

### Confirmed Cases

* **2,428 patients**
* Average annual intake: **220**
* Average age: **51.15 years**
* Average tumour size: **1.99**
* Most affected age group: **41–50 years**

### Tumour Distribution

| Tumour Type      | Percentage |
| ---------------- | ---------: |
| Meningioma       |     68.45% |
| Pituitary tumour |     23.72% |
| Glioma           |      7.83% |

The most represented brain region was the **pituitary region**, followed by the occipital and parietal regions.

The highest annual number of confirmed Grade 1 cases occurred in **2016 (252 cases)**.

### Unconfirmed Cases

* **1,588 patients**
* Average annual intake: **144.4**
* Average age: **51.55 years**
* Average tumour size: **2.03**
* Most affected age group: **41–50 years**

Tumour distribution was highly similar to confirmed cases:

| Tumour Type      | Percentage |
| ---------------- | ---------: |
| Meningioma       |     69.08% |
| Pituitary tumour |     21.98% |
| Glioma           |      8.94% |

### Key Observation

The close similarity between confirmed and unconfirmed Grade 1 cases is notable. Both cohorts show similar age profiles, tumour sizes and tumour-type distributions.

---

# Grade 2

![](https://github.com/Cuteod/Brain-Tumour-Analysis-Confirmed-vs-Unconfirmed-Cases/blob/main/Brain%20tumour%20grade%202.png)

### Confirmed Cases

* **680 patients**
* Average annual intake: **61.8**
* Average age: **42.35 years**
* Average tumour size: **4.01**
* Most affected age group: **41–50 years**

Tumour distribution:

| Tumour Type | Percentage |
| ----------- | ---------: |
| Ependymoma  |     45.15% |
| Glioma      |     28.97% |
| Meningioma  |     25.85% |

The **brainstem and cerebellum** were the most represented anatomical regions.

The highest annual number of cases occurred in **2019 (78 cases)**.

### Unconfirmed Cases

* **441 patients**
* Average annual intake: **40.1**
* Average age: **43.05 years**
* Average tumour size: **4.08**
* Most affected age group: **41–50 years**

Tumour distribution:

| Tumour Type | Percentage |
| ----------- | ---------: |
| Ependymoma  |     43.54% |
| Glioma      |     29.25% |
| Meningioma  |     27.21% |

The **cerebellum and brainstem** remained the leading anatomical regions.

### Key Observation

The Grade 2 confirmed and unconfirmed cohorts again demonstrate similar tumour-type, age and anatomical patterns.

---

# Grade 3

![](https://github.com/Cuteod/Brain-Tumour-Analysis-Confirmed-vs-Unconfirmed-Cases/blob/main/Brain%20tumour%20grade%203.png)

### Confirmed Cases

* **698 patients**
* Average annual intake: **63.5**
* Average age: **37.52 years**
* Average tumour size: **6.02**
* Most affected age groups: **21–30 and 31–40 years**

Tumour distribution:

| Tumour Type | Percentage |
| ----------- | ---------: |
| Ependymoma  |     59.17% |
| Glioma      |     40.83% |

The **cerebellum and brainstem** were the most frequently represented regions.

The highest annual number of cases occurred in **2015 (75 cases)**.

### Unconfirmed Cases

* **84 patients**
* Average annual intake: **7.6**
* Average age: **41.21 years**
* Average tumour size: **5.97**
* Most affected age group: **31–40 years**

Tumour distribution:

| Tumour Type | Percentage |
| ----------- | ---------: |
| Ependymoma  |     58.33% |
| Glioma      |     41.67% |

Again, the cerebellum and brainstem were the leading regions.

### Key Observation

The most striking feature of Grade 3 is the **large difference in case volume between confirmed and unconfirmed cohorts**.

However, the tumour-type and anatomical distributions remain remarkably similar.

This suggests that confirmation status should be investigated alongside other variables rather than treated simply as a data-quality filter.

---

# Grade 4

![](https://github.com/Cuteod/Brain-Tumour-Analysis-Confirmed-vs-Unconfirmed-Cases/blob/main/Brain%20tumour%20grade%204.png)

### Confirmed Cases

* **3,667 patients**
* Average annual intake: **333.4**
* Average age: **40.45 years**
* Average tumour size: **6.49**
* Most affected age group: **60+**

Tumour distribution:

| Tumour Type     | Percentage |
| --------------- | ---------: |
| Glioma          |     75.51% |
| Medulloblastoma |     24.49% |

The **cerebellum** was the most represented anatomical region.

The highest annual number of cases occurred in **2016 (363 cases)**.

### Unconfirmed Cases

* **414 patients**
* Average annual intake: **37.6**
* Average age: **40.77 years**
* Average tumour size: **6.54**
* Most affected age group: **60+**

Tumour distribution:

| Tumour Type     | Percentage |
| --------------- | ---------: |
| Glioma          |     75.12% |
| Medulloblastoma |     24.88% |

The cerebellum remained the most represented anatomical region.

### Key Observation

Grade 4 showed the **largest overall patient burden** among the four grades and was strongly dominated by gliomas.

The confirmed and unconfirmed groups also showed almost identical tumour-type proportions and very similar average age and tumour size.

---

# Cross-Grade Findings

One of the clearest patterns observed was the increase in average tumour size with tumour grade.

| Grade   | Confirmed | Unconfirmed |
| ------- | --------: | ----------: |
| Grade 1 |      1.99 |        2.03 |
| Grade 2 |      4.01 |        4.08 |
| Grade 3 |      6.02 |        5.97 |
| Grade 4 |      6.49 |        6.54 |

This provides a strong descriptive gradient in the dataset: **higher tumour grades are associated with larger average recorded tumour sizes**.

Importantly, the pattern is almost identical between confirmed and unconfirmed cases.

---

# Major Insights

## 1. Confirmed and Unconfirmed Cases Show Similar Structural Patterns

Across the grades, confirmed and unconfirmed cases demonstrate similar:

* Tumour-type distributions
* Average tumour sizes
* Age patterns
* Anatomical distributions

This makes unconfirmed cases analytically important rather than simply cases to be discarded.

---

## 2. Grade 1 Represents the Largest Confirmed Cohort

Grade 1 accounted for **2,428 confirmed cases**, while Grade 4 accounted for **3,667 confirmed cases**.

Although Grade 4 had the largest confirmed population overall, Grade 1 demonstrated a substantially different tumour profile, particularly the dominance of meningioma and pituitary tumours.

This highlights the importance of analysing tumour grades separately rather than relying solely on total case counts.

---

## 3. Grade 4 Represents the Largest Overall Burden

Grade 4 had:

* The largest confirmed population
* The largest average annual intake
* The largest average tumour size

Glioma accounted for approximately **three-quarters of Grade 4 cases** in both confirmation groups.

This makes Grade 4 a particularly important area for resource planning and further investigation.

---

## 4. Anatomical Patterns Change Across Grades

Lower-grade disease showed greater representation of areas such as the **pituitary, frontal and temporal regions**, while higher-grade groups showed stronger representation of the **cerebellum and brainstem**.

These patterns provide an opportunity for further investigation into the relationship between tumour grade, anatomical location and clinical presentation.

---

## 5. Age Patterns Differ Across Tumour Grades

The analysis does not show a simple linear relationship between age and tumour grade.

Instead:

* Grade 1 was concentrated around **41–50 years**
* Grade 2 remained concentrated around **41–50 years**
* Grade 3 shifted toward **younger adults**
* Grade 4 showed substantial representation among **older adults and younger age groups**

This suggests that age should be considered alongside tumour grade and type when planning further analysis.

---

# Health-System and Policy Implications

The analysis raises several questions relevant to health-system planning.

### Diagnostic Confirmation

Confirmation status should be interpreted within its clinical context. An unconfirmed case should not automatically be considered an invalid or poor-quality record.

Future data collection should ideally capture **why a case remains unconfirmed**, such as:

* Imaging-based diagnosis
* Clinical management decision
* Surgical risk
* Patient referral status
* Loss to follow-up
* Other documented reasons

### Resource Allocation

The high burden of Grade 4 cases, particularly gliomas, suggests the importance of examining the availability and distribution of:

* Neuroimaging
* Neurosurgical services
* Oncology services
* Radiotherapy
* Specialist referral pathways

### Data Quality

A binary confirmed/unconfirmed variable provides useful information, but it does not fully explain the diagnostic pathway.

Adding diagnostic pathway variables would allow future analyses to distinguish between:

> **clinical non-confirmation** and **system-related non-confirmation**.

---


# Tools & Skills

This project demonstrates skills in:

* Exploratory Data Analysis (EDA)
* Data cleaning and preparation
* Data segmentation
* Descriptive statistics
* Cohort analysis
* Comparative analysis
* Health data analytics
* Data visualization
* Dashboard development
* Analytical storytelling

**Tools:**
`Excel` | `Power BI` | `Data Visualization`

> Update the tools section to reflect only the tools actually used in this project.

---

# Project Takeaway

The central lesson from this project is that **health data should not be interpreted through a single variable**.

Separating confirmed and unconfirmed cases revealed that both groups shared several important structural characteristics across tumour grade, size, age, tumour type and anatomical location.

The analysis therefore demonstrates the value of looking beyond simple case counts and asking a deeper question:

> **What does the pattern in the data tell us about the disease — and what does it tell us about the system collecting the data?**

For me, this project demonstrates how data analytics can bridge the gap between **raw clinical records, meaningful insights, and evidence-informed health-system decision-making**.


