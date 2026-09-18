# Titanic-Survival_Analysis
Titanic survival analysis and prediction using Python, Pandas, Seaborn and Logistic Regression.
# 🚢 Titanic Survival Analysis

### Exploratory Data Analysis using Python

This project performs exploratory data analysis (EDA) on the famous Titanic dataset to understand the factors associated with passenger survival.

## 📌 Project Objective

The main objective is to explore the Titanic passenger data and identify patterns in survival based on:

* Passenger class
* Age
* Gender
* Fare
* Family size

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook

## 📊 Analysis Performed

### 1. Passenger Class Analysis

Compared survival rates across 1st, 2nd, and 3rd class passengers.

**Finding:** Class 1 had the highest observed survival rate.

### 2. Age Analysis

Calculated the average passenger age and created age groups.

**Finding:**

* Average age: **29.36 years**
* Young Adults (19–35) were the largest age group.
* Children had the highest observed survival rate among the defined age groups.

### 3. Gender Analysis

Compared passenger counts and survival rates between males and females.

**Finding:**

* Male passengers: **577**
* Female passengers: **314**
* Female survival rate: **74.20%**
* Male survival rate: **18.89%**

### 4. Gender + Passenger Class

Analyzed survival using both gender and passenger class.

**Finding:** Survival rates varied considerably across gender and class.

### 5. Fare Analysis

Compared the average fare paid by passengers who survived and those who did not.

**Finding:**

* Average fare of survivors: **48.40**
* Average fare of non-survivors: **22.12**

### 6. Family Size Analysis

Created a `FamilySize` feature using:

```python
FamilySize = SibSp + Parch + 1
```

**Finding:** Survival rates varied across different family sizes, with some small family groups showing higher observed survival rates.

## 📈 Key Insights

The analysis identified associations between survival and several passenger characteristics:

**Passenger Class + Gender + Age + Fare + Family Size**

These variables provide useful features for a future machine learning model.

## 📂 Project Structure

```text
Titanic-Survival-Analysis/
│
├── Titanic_Survival_Analysis.ipynb
├── README.md
└── dataset/
    └── titanic.csv
```

## 🚀 Future Improvements

The next stage of this project could include:

* Data preprocessing
* Handling missing values
* Feature engineering
* Encoding categorical variables
* Train/test split
* Logistic Regression
* Decision Tree
* Random Forest
* Model evaluation using accuracy, precision, recall, and F1-score

## 👨‍💻 Author

Beginner Python & Machine Learning Project

