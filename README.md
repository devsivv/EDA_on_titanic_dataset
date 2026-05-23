# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project explores the famous Titanic dataset to understand the factors that influenced passenger survival during the Titanic disaster.

The main goal of this analysis was to:
- Explore passenger demographics
- Understand survival patterns
- Identify relationships between different features
- Perform univariate, bivariate, and multivariate analysis
- Extract meaningful insights from the dataset

This project was created while learning Exploratory Data Analysis through the CampusX EDA lecture series.

---

# Dataset Information

The dataset contains information about Titanic passengers, including:

- Passenger Class
- Age
- Gender
- Fare
- Family Information
- Cabin Information
- Embarkation Port
- Survival Status

### Target Variable
- `Survived`
  - `0` → Did Not Survive
  - `1` → Survived

---

# Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Project Structure

```bash
Titanic_CampusX/
│
├── images/
│   ├── Age Distribution of Titanic Passengers.png
│   ├── Passenger Survival Distribution.png
│   ├── Passenger Class vs Survival Heatmap.png
│   └── ...
│
├── notebooks/
│   └── eda_titanic.ipynb
│
├── sample_data/
│   ├── train.csv
│   └── test.csv
│
├── README.md
└── requirements.txt
```

---

# Exploratory Data Analysis

# 1. Age Analysis

## Age Distribution of Titanic Passengers

### Conclusion
- Most passengers were between 20 and 40 years old.
- Very few elderly passengers were present.
- The age distribution was positively skewed.

---

## Kernel Density Estimation of Passenger Ages

### Conclusion
- Passenger ages were heavily concentrated around young adults.
- Multiple peaks suggested the presence of different age groups.

---

## Box Plot of Passenger Ages

### Conclusion
- Median passenger age was around 28 years.
- Several outliers existed above 65 years.
- Most passengers belonged to a relatively young age group.

---

# 2. Fare Analysis

## Fare Distribution of Titanic Passengers

### Conclusion
- Most passengers paid low ticket fares.
- A small number of passengers paid extremely high fares.
- The distribution showed strong right skewness.

---

## Kernel Density Estimation of Passenger Fares

### Conclusion
- The majority of passengers traveled economically.
- Luxury-class passengers formed a very small portion of the dataset.

---

## Box Plot of Passenger Fares

### Conclusion
- Fare contained many extreme outliers.
- High ticket fares were associated with premium passenger classes.

---

# 3. Survival Analysis

## Passenger Survival Distribution

### Conclusion
- More passengers died than survived.
- The dataset showed moderate imbalance toward non-survivors.
- Survival rate was below 40%.

---

## Passenger Survival Percentage

### Conclusion
- Around 62% of passengers did not survive.
- Approximately 38% survived the disaster.

---

# 4. Passenger Class Analysis

## Passenger Class Distribution

### Conclusion
- Most passengers belonged to 3rd class.
- 1st class passengers formed the minority group.
- Lower socioeconomic travelers dominated the dataset.

---

## Passenger Class Percentage

### Conclusion
- Third-class passengers occupied the largest share of the ship population.
- Passenger class distribution reflected economic inequality aboard the Titanic.

---

# 5. Gender Analysis

## Passenger Sex Distribution

### Conclusion
- Male passengers significantly outnumbered female passengers.
- Gender imbalance existed in the dataset.

---

## Passenger Sex Percentage

### Conclusion
- Male passengers formed the majority population.
- Female passengers represented a smaller proportion of travelers.

---

# 6. Embarkation Analysis

## Passenger Embarked Distribution

### Conclusion
- Most passengers boarded from Southampton.
- Cherbourg and Queenstown contributed smaller passenger groups.

---

## Passenger Embarked Percentage

### Conclusion
- Southampton served as the primary boarding location.
- Embarkation point may have indirectly influenced passenger class and survival.

---

# 7. Family-Based Analysis

## Distribution of Siblings/Spouses Aboard

### Conclusion
- Most passengers traveled alone.
- Few passengers traveled with large families.
- Small family sizes were more common.

---

## Percentage of Siblings/Spouses Aboard

### Conclusion
- Solo travelers dominated the dataset.
- Large family groups were rare aboard the ship.

---

## Distribution of Parent-Children Aboard

### Conclusion
- Most passengers did not travel with parents or children.
- Family-based travel groups were relatively uncommon.

---

## Percentage of Parent-Children Aboard

### Conclusion
- Passenger groups with children represented a small fraction of the dataset.

---

# 8. Bivariate Analysis

## Passenger Class vs Survival Heatmap

### Conclusion
- First-class passengers had the highest survival rates.
- Third-class passengers had the lowest survival probability.
- Passenger class strongly influenced survival chances.

---

## Average Age by Survival Status

### Conclusion
- Survivors were slightly younger on average.
- Age alone was not the strongest survival factor.

---

## Age Distribution by Survival Status

### Conclusion
- Younger passengers showed slightly better survival rates.
- Children appeared to receive evacuation priority.

---

## Survival Distribution Across Decks

### Conclusion
- Certain decks had significantly higher survival rates.
- Cabin location likely influenced evacuation accessibility.

---

# 9. Correlation Analysis

## Correlation Heatmap of Numerical Features

### Conclusion
- Fare showed positive correlation with survival.
- Passenger class had negative correlation with fare.
- Family-related variables were strongly correlated with each other.
- Age showed relatively weak correlation with survival.

---

# 10. Multivariate Analysis

## Pairwise Relationships Between Key Titanic Features

### Conclusion
- Higher fares were generally associated with higher survival rates.
- Family size variables showed strong relationships.
- Most passengers traveled with small family groups.
- Feature interactions revealed socioeconomic patterns among passengers.

---

# Key Insights from the Entire Analysis

- Passenger class was one of the strongest factors affecting survival.
- Female passengers and younger passengers had better survival chances.
- Wealthier passengers generally survived more often.
- Most passengers belonged to lower economic classes.
- Family size influenced travel patterns and survival behavior.
- Age alone was not a strong predictor of survival.
- Ticket fare strongly reflected passenger class and socioeconomic status.

---

# Final Conclusion

This exploratory analysis revealed that survival on the Titanic was heavily influenced by:
- socioeconomic status
- passenger class
- gender
- cabin/deck location

The dataset also highlighted strong inequality patterns among passengers. Wealthier passengers and those in better locations on the ship had significantly higher survival probabilities.

Through this EDA process, multiple statistical patterns and relationships were discovered, helping build a deeper understanding of the Titanic disaster dataset.

---

# How to Run This Project

```bash
git clone <your-repository-link>

cd Titanic_CampusX

pip install -r requirements.txt

jupyter notebook
```

---

# Future Improvements
- Machine Learning Models
- Survival Prediction
- Advanced Visualizations
- Outlier Handling
- Missing Value Treatment

---

# Author

### Shivam Dubey

GitHub: https://github.com/devsivv

Made during the CampusX Exploratory Data Analysis (EDA) lecture series for learning.