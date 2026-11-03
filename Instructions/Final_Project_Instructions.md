# FINAL PROJECT
## Advanced Data Wrangling: From Raw Data to Reproducible Data Products

**Course:** Teknik Sampling dan Data Wrangling  
**Study Program:** Bachelor of Data Science, Institut Teknologi Sepuluh Nopember (ITS)  
**Project Type:** Group Project (2 Students per Group)  
**Duration:** 4 Weeks  
**Programming Language:** Python  
**Assessment:** Open, Take-Home Project  
**Final Deliverables:** Public GitHub Repository, Published Kaggle Notebook, and Final Presentation

---

## 1. Project Overview

Real-world datasets frequently contain missing values, duplicate records, inconsistent formats, invalid observations, and structural problems. These issues must be systematically identified and addressed before reliable analysis can be performed.

In this project, students will develop an end-to-end data wrangling pipeline using a real-world dataset. The project emphasizes evidence-based data cleaning, comparison of preprocessing strategies, data validation, reproducibility, and public documentation.

Students must demonstrate not only how data are cleaned and transformed, but also why particular preprocessing decisions are appropriate and how those decisions affect the resulting dataset.

## 2. Group Requirements

1. Each group must consist of **exactly 2 students**.
2. The project duration is **4 weeks**.
3. Both students must contribute substantially to the project.
4. Each member must understand the complete workflow and be able to explain the implementation.
5. Individual contributions must be documented through GitHub commit history and a contribution statement.
6. A mandatory progress checkpoint will be conducted at the end of Week 14.

## 3. Dataset Selection

Each group must select **ONE** dataset from the following repository:

[Final Project Dataset Repository](https://github.com/neni1705/FinalProject_DataWrangling-DS-ITS/tree/488de37a5a559275194d62baa48812ce69d2307c/Dataset)

Available datasets:

- **Hotel Bookings Data:** Hotel reservations, booking characteristics, arrival information, and cancellation-related variables.
- **NFL Attendance Data:** American football attendance, team information, game records, and seasonal characteristics.
- **Spotify Genre Data:** Music attributes, genre information, and numerical audio characteristics.

Students must preserve the original dataset and document its source.

## 4. Project Tasks

### Task A — Data Gathering and Understanding (10%)

Students must:

1. Load and inspect the selected dataset.
2. Identify the unit of observation, variable types, identifiers, and relationships between tables.
3. Report the number of observations, variables, and files.
4. Create a data dictionary describing the variables and their expected values.
5. Formulate three relevant analytical questions.
6. Develop a workflow diagram illustrating the data preparation process.

**Required outputs:** Data profiling notebook, data dictionary, three analytical questions, and workflow diagram.

### Task B — Data Quality Assessment (20%)

Students must systematically investigate at least six relevant categories of potential data quality issues, including missing values, duplicates, inconsistent categories, invalid values, incorrect data types, outliers, and structural inconsistencies.

Students must:

1. Quantify missing values and examine missingness patterns.
2. Identify exact and potential duplicate records.
3. Examine invalid values, inconsistent categories, and incorrect data types.
4. Detect potential outliers using suitable techniques.
5. Create a `quality_issue_log.csv` documenting problems, evidence, proposed treatments, and final decisions.
6. Calculate at least four quantitative data quality indicators, where applicable.

Students must distinguish genuine data errors from valid but unusual observations. If a particular issue is absent, the assessment must still be documented.

**Required outputs:** Quality assessment notebook, issue log, supporting visualizations, and data quality summary.

### Task C — Data Cleaning and Transformation (25%)

Students must implement a systematic preprocessing pipeline.

#### C1. Missing-Data Treatment

Compare at least two appropriate missing-data handling strategies for a selected variable.

Explain the assumptions, implementation, evaluation criteria, and final method selection.

If no relevant missing values exist, conduct a clearly labeled controlled missingness experiment without modifying the original dataset.

#### C2. Cleaning and Standardization

Perform necessary procedures for duplicate resolution, category standardization, type conversion, invalid-value treatment, and other identified quality problems.

Every treatment must be justified.

#### C3. Data Transformation

Implement at least four meaningful operations, selected according to the dataset:

- Grouping and aggregation.
- Filtering and subsetting.
- Sorting and ranking.
- Feature construction.
- Date/time transformation.
- Reshaping or pivoting.
- Encoding or scaling.
- String normalization.

#### C4. Data Integration

For multiple related tables, perform appropriate merging or concatenation and validate the result.

For a single-table dataset, construct and integrate two logically related derived tables with a clear analytical purpose.

#### C5. Sensitivity Analysis

Compare two reasonable preprocessing decisions and demonstrate their effects on at least one meaningful statistical summary or analytical conclusion.

**Required outputs:** Reusable preprocessing code, processed dataset, comparison of missing-data methods, sensitivity analysis, and documented methodological decisions.

### Task D — Data Validation and Reproducibility (15%)

Students must implement at least five automated validation checks based on the dataset's requirements.

Examples include:

- Required columns exist.
- Data types are correct.
- Values satisfy domain constraints.
- Identifiers are unique where required.
- Derived variables are internally consistent.
- Merging preserves the intended data structure.

Each validation check must return an interpretable **PASS/FAIL** result.

Students must also compare data quality indicators before and after preprocessing.

The complete workflow must run from the original dataset using relative paths and documented dependencies.

**Required outputs:** Automated validation code, validation results, before-and-after quality comparison, and reproducible pipeline.

### Task E — Exploratory Data Analysis and Interpretation (15%)

Using the processed dataset, students must answer the three analytical questions formulated in Task A.

Minimum requirements:

1. Four meaningful visualizations.
2. Two summary tables.
3. Three evidence-based findings.
4. Interpretation of all major results.
5. Discussion of how preprocessing affects at least one analytical result.
6. Discussion of limitations and possible preprocessing bias.

The focus must remain on data preparation and descriptive or exploratory analysis. Predictive machine learning models are not required.

**Required outputs:** EDA notebook, visualizations, tables, findings, and limitations.

### Task F — Documentation and Public Publication (15%)

#### F1. GitHub Repository — Mandatory

Each group must create a public GitHub repository containing:

- Original data or appropriate source-access instructions.
- Processed data, where redistribution is permitted.
- Jupyter notebooks.
- Reusable Python scripts.
- Data dictionary.
- Quality issue log.
- Validation results.
- Project report.
- `requirements.txt`.
- Complete `README.md`.

The README must include project objectives, dataset description, methodology, key findings, reproducibility instructions, member contributions, and the Kaggle publication link.

#### F2. Kaggle Notebook — Mandatory

Each group must publish a public Kaggle Notebook containing:

1. Introduction and analytical objectives.
2. Dataset description.
3. Data quality assessment.
4. Data cleaning and transformation.
5. Data validation.
6. Exploratory analysis.
7. Findings, limitations, and conclusions.

The notebook must contain explanatory Markdown and relevant visualizations, execute successfully, and link to the GitHub repository.

**GitHub and Kaggle are both mandatory.**

However, students are **not required to obtain a particular number of Kaggle upvotes, views, comments, followers, or medals**. These engagement metrics will not affect their grades.

Publication quality will be assessed based on technical correctness, clarity, reproducibility, completeness, and accessibility.

## 5. Four-Week Schedule and Mandatory Checkpoint

| Week | Activities | Milestone |
|---|---|---|
| Week 13 | Data gathering, understanding, profiling, and quality assessment | Initial quality assessment and data dictionary |
| Week 14 | Cleaning, missing-data treatment, integration, and transformation | Working preprocessing pipeline and mandatory checkpoint |
| Week 15 | Automated validation, sensitivity analysis, and EDA | Validated dataset and preliminary findings |
| Week 16 | Documentation, reproducibility testing, publication, and presentation | Final GitHub repository, Kaggle Notebook, and presentation |

### Mandatory Checkpoint — End of Week 2

Each group must demonstrate:

1. Identified data quality problems and supporting evidence.
2. The data cleaning procedures implemented so far.
3. A comparison of at least two preprocessing strategies.
4. The preliminary processed dataset.
5. GitHub commit history showing both members' contributions.

The checkpoint is intended to identify methodological problems early and provide feedback before final publication.

Students must incorporate relevant feedback into their final submission.

## 6. Final Assessment Rubric

| Component | Weight |
|---|---:|
| A. Data Gathering and Understanding | 10% |
| B. Data Quality Assessment | 20% |
| C. Data Cleaning and Transformation | 25% |
| D. Data Validation and Reproducibility | 15% |
| E. Exploratory Analysis and Interpretation | 15% |
| F. Documentation and Public Publication | 15% |
| **Total** | **100%** |

### Individual Assessment

The final grade will combine:

- **85% Group Project Performance:** Evaluated using the six-component rubric above.
- **15% Individual Contribution and Understanding:** Evaluated through GitHub contribution history, individual explanations, and performance during the final presentation and questions.

The final score for student $i$ is calculated as:

$$
\text{Final Score}_i = 0.85(\text{Group Project Score}) + 0.15(\text{Individual Score}_i)
$$

Both scores are measured on a scale of 0–100.

#### Individual Evaluation Criteria

| Criterion | Weight within individual score |
|---|---:|
| Substantive technical contribution | 40% |
| Understanding of methodological decisions | 40% |
| Presentation and ability to answer questions | 20% |
| **Total** | **100%** |

GitHub commit counts alone will not determine individual contributions. The quality and substance of each student's work will also be considered.

## 7. Final Presentation

Each group must deliver:

- **10-minute presentation**.
- **5-minute question-and-answer session**.

Both students must participate and be prepared to explain the complete project, including preprocessing decisions and validation procedures.

## 8. Repository Structure

```text
final-project-data-wrangling/
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_quality_assessment.ipynb
│   ├── 03_cleaning_transformation.ipynb
│   ├── 04_validation_eda.ipynb
│   └── 05_kaggle_publication.ipynb
├── src/
│   ├── cleaning.py
│   ├── transformation.py
│   └── validation.py
├── reports/
│   ├── data_dictionary.csv
│   ├── quality_issue_log.csv
│   ├── quality_comparison.csv
│   └── final_report.md
├── figures/
├── requirements.txt
├── README.md
└── .gitignore
```

## 9. Submission Requirements

Each group must submit through MyClassroom:

1. Public GitHub Repository URL.
2. Published Kaggle Notebook URL.
3. Final project report, stored in the repository.
4. Presentation slides in PDF format.
5. Names and student IDs of both members.

The GitHub repository and Kaggle Notebook must remain accessible for evaluation.

**Deadline:** Four weeks after the official project announcement, at the date and time specified through MyClassroom.

## 10. Academic Integrity and Responsible Use of AI

Students may use programming documentation, tutorials, and AI-assisted tools as learning resources.

However:

- Students must understand and verify all submitted code.
- External code and references must be acknowledged.
- Fabrication of data quality issues, validation results, or analytical findings is prohibited.
- Both students must be able to explain the submitted work.
- Substantial use of AI-assisted tools must be disclosed in the README.

## 11. Final Submission Checklist

- [ ] Group consists of exactly two students.
- [ ] Dataset is selected from the designated repository.
- [ ] Original dataset is preserved.
- [ ] Data dictionary is complete.
- [ ] Data quality assessment and issue log are provided.
- [ ] Alternative missing-data strategies are compared.
- [ ] At least four meaningful transformations are implemented.
- [ ] Data integration is demonstrated.
- [ ] Sensitivity analysis is completed.
- [ ] At least five automated validation checks are implemented.
- [ ] Before-and-after data quality comparison is included.
- [ ] At least four visualizations and two summary tables are provided.
- [ ] Three analytical questions are answered.
- [ ] Pipeline runs reproducibly.
- [ ] GitHub repository is public and documented.
- [ ] Kaggle Notebook is published and accessible.
- [ ] Both students' contributions are documented.
- [ ] Final presentation is prepared.

---

**Expected Outcome:** A professional, reproducible, and publicly documented data wrangling project demonstrating the complete workflow from raw data to validated, analysis-ready data.

The project should serve as an academic portfolio demonstrating students' technical, analytical, documentation, and collaborative skills.

