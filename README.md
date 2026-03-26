# Sleep Health Data Analysis

## Project Overview
This project explores the relationship between sleep health, lifestyle habits, and physiological indicators using the **Sleep Health and Lifestyle Dataset**.

The goal is to understand how factors such as **age, occupation, stress level, BMI, physical activity, and blood pressure** are associated with sleep quality and sleep disorders.

This project focuses on:
- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Insight Generation**
- **(Optional Extension) Predictive Modeling**

---

## Research Questions
This project aims to answer the following questions:

- Does **sleep quality** vary across different **age groups**?
- Is **BMI** more strongly associated with **blood pressure** than stress level?
- Do certain **occupations** appear to have higher **stress levels** or poorer sleep health?
- How do **sleep disorders** differ in terms of **sleep duration** and **quality of sleep**?
- Which lifestyle and health factors may be useful for predicting **sleep disorders**?

---

## Dataset
- **Dataset Name:** Sleep Health and Lifestyle Dataset
- **Source:** Kaggle
- **Observations:** ~374 individuals
- **Features:** Demographic, lifestyle, cardiovascular, and sleep-related variables

### Main Features
- Gender
- Age
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Blood Pressure
- Heart Rate
- Daily Steps
- Sleep Disorder

> **Note:** This dataset is suitable for exploratory analysis and educational modeling, but findings should be interpreted as **associations rather than causal conclusions**.

---

## Project Workflow

### 1. Data Loading and Inspection
- Loaded the dataset
- Checked data types and column structure
- Reviewed general dataset shape and summary statistics

### 2. Data Cleaning
- Checked for missing values
- Checked for duplicate rows
- Inspected potential formatting inconsistencies

### 3. Feature Engineering
- Split the **Blood Pressure** column into:
  - `Systolic_BP`
  - `Diastolic_BP`
- Created additional interpretable groupings where necessary (e.g., age-based categories)

### 4. Exploratory Data Analysis (EDA)
The analysis focused on:
- Distribution of sleep and health-related variables
- Relationship between **BMI and blood pressure**
- Differences in **sleep quality by age**
- **Occupation vs stress level**
- **Sleep disorder patterns**

### 5. Insight Generation
The project identifies meaningful patterns and interprets them in a health/lifestyle context.

---

## Key Findings

### 1) BMI appears more strongly associated with blood pressure than stress level
After separating blood pressure into systolic and diastolic values, the data suggested that individuals in higher BMI categories tended to show elevated blood pressure values.

### 2) Sleep quality differs across age groups
Some age groups appeared to report better sleep quality than expected, which suggests that age alone may not explain sleep outcomes.

### 3) Occupation may influence stress and sleep patterns
Certain occupations appeared to cluster around higher stress levels and different sleep behavior patterns.

### 4) Sleep disorders are associated with meaningful lifestyle and physiological differences
Individuals with different sleep disorder categories showed visible variation in sleep duration, quality, and health indicators.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```bash
Sleep_Health_Data_Analysis/
│
├── data/
│   └── sleep_health_and_lifestyle_dataset.csv
│
├── notebooks/
│   └── sleep_health_analysis.ipynb
│
├── images/
│   ├── bmi_vs_bp.png
│   ├── age_vs_sleep_quality.png
│   ├── occupation_vs_stress.png
│   └── sleep_disorder_patterns.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

### 1. Clone the repository
```bash
git clone https://github.com/ebruarik/Sleep_Health_Data_Analysis.git
cd Sleep_Health_Data_Analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
Open Jupyter Notebook or Jupyter Lab and run:

```bash
jupyter notebook
```

Then open:

```bash
notebooks/sleep_health_analysis.ipynb
```

---

## Limitations
This project has several limitations:

- The dataset is relatively small
- The analysis is based on observational data
- Results indicate **correlation/association**, not **causation**
- Some variables may be simplified or synthetic in nature

Because of this, the findings should be treated as **exploratory insights**, not medical conclusions.

---

## Future Improvements
Possible next steps for this project include:

- Building a **classification model** to predict **Sleep Disorder**
- Using **cross-validation** for more reliable model evaluation
- Creating a **machine learning pipeline**
- Testing multiple models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Performing **feature importance analysis**
- Improving visual storytelling and dashboard presentation

---

## Conclusion
This project shows that sleep health is connected not only to sleep duration itself, but also to broader **lifestyle and physiological indicators** such as **BMI, stress, occupation, and cardiovascular measurements**.

The analysis serves as a strong foundation for both:
- **data storytelling**
- and **introductory machine learning applications**

---

## Author
**Ebru Arık**
