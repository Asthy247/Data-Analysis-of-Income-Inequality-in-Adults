# Data-Analysis-of-Income-Inequality-in-Adults
# Introduction
This project aims to analyze the Adult Income dataset from Kaggle website to understand the factors influencing income inequality. By exploring the relationships between various demographic, socioeconomic, and employment-related factors, we can gain insights into the underlying causes of income disparities.
**Datase**t - https://www.kaggle.com/datasets/wenruliu/adult-income-dataset The data available at hand comes from Census 1994.
# Data Description
The dataset contains 48,842 data points representing adult individuals, with 15 attributes describing their demographics, education, occupation, income, and other relevant characteristics. Each record is classified as either "<=50K" or ">50K" based on annual income.
# Attribute Information:
Age: Describes the age of individuals. Continuous.

Workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

fnlwgt: Continuous.

education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

education-num: Number of years spent in education. Continuous.

marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

sex: Female, Male.

capital-gain: Continuous.

capital-loss: Continuous.

hours-per-week: Continuous.

native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

salary: >50K,<=50K

# Data Preprocessing:
# •	Missing Values: 
The dataset had to be processed and there are no missing values.
# •	Duplicate Removal: 
Data processing was carried out to remove duplicate entries, resulting in a cleaner dataset for analysis.

# •	Data Cleaning:
Special characters was replaced or inconsistencies in the data to ensure accurate analysis.

# •	Categorical Conversion: 
The variable "workclass" was converted to a categorical data type for enhanced analysis of work categories and their association with income levels.
# Exploratory Data Analysis (EDA)
**1.	Univariate Analysis:** The distribution of each attribute was analyzed (e.g., age, education level, work class) to understand the central tendencies, variations, and potential skewness within the data. 
**A)	Distribution of Age
Histogram of Age**

![image](https://github.com/user-attachments/assets/aa4ecdab-1428-43cc-8b57-fe9ae29c4670)
The age distribution demonstrated a right-skewed pattern, indicating a larger proportion of younger individuals in the dataset.

**B)	Distribution of Work class
Bar chart of Work class**

![image](https://github.com/user-attachments/assets/7a2ad51a-2be6-4853-991c-17e4b704ec3e)

The analysis revealed a dominance of individuals employed in the private sector, followed by a significant presence in local and state government jobs. Self-employment and unpaid work appeared less common.

# 2. Bivariate Analysis:
The relationships between pairs of variables to identify potential correlations was explored. Bivariate analysis allows us to explore the relationships between pairs of variables, such as the possible correlation between age and income or the association between work class and income levels.

**A)	Age vs. Income: **

![image](https://github.com/user-attachments/assets/3183d4cd-b5f6-4968-bcea-e893fb7c4d6e)

A boxplot analysis revealed a higher median age for individuals with incomes exceeding $50K compared to those earning less. This suggests a potential association between age and income.

**B) Income Distribution: **
Analyzing the income distribution demonstrated a clear class imbalance, with a considerably larger group earning less than or equal to $50K.
**Income Distribution Bar Plot**

![image](https://github.com/user-attachments/assets/a01b27a8-2793-4785-9b04-6b944ca4d574)

**Interpreting the Income Distribution Bar Plot
Key Observations:**
**Class Imbalance:**
The plot clearly shows an imbalance in the distribution of income levels. There are significantly more individuals with an income less than or equal to $50K compared to those with an income greater than $50K.
**Dominant Class: **
The majority of individuals in the dataset belong to the lower income group (<=50K).

# Research Questions and Findings
**1.	How does age, education, and occupation influence income level?**
o	Older individuals with higher education and professional occupations tend to have higher incomes.
**2.	Is there a significant gender pay gap?**
o	Preliminary analysis suggests a potential gender pay gap, but further investigation is needed to control for other factors.
**3.	How does race and ethnicity impact income levels?**
o	Certain racial and ethnic groups might face systemic disadvantages, leading to lower income levels.
**4.	What is the impact of capital gains and losses on income?**
o	Capital gains and losses can significantly impact income levels, especially for individuals in certain professions or investment activities.
**5.	How does the number of hours worked per week correlate with income?**
o	There is a positive correlation between hours worked and income, but other factors like occupation and productivity also play a role.

# Recommendations
Based on the analysis of the Adult Income dataset, I can offer the following recommendations:
**Policy Implications:**
**•	Education and Training:** Invest in education and training programs to equip individuals with the skills needed for higher-paying jobs.
**•	Social Safety Nets:** Strengthen social safety nets to support low-income individuals and families.
**•	Anti-Discrimination Laws:** Enforce and strengthen anti-discrimination laws to ensure equal opportunities for all.
**Data-Driven Decision Making:**
**•	Continuous Monitoring:** Continuously monitor changes in income distribution and identify emerging trends.
**•	Targeted Interventions:** Develop targeted interventions to address specific needs of disadvantaged groups.
**•	Data-Driven Policymaking:** Use data analytics to inform policy decisions and evaluate the effectiveness of interventions.
**Machine Learning Applications:**
**•	Predictive Modeling:** Develop predictive models to identify individuals at risk of low income and provide early interventions.
**•	Fairness and Bias:** Ensure that machine learning models are fair and unbiased, avoiding discriminatory outcomes.

# Conclusion
The analysis of the Adult Income dataset has provided valuable insights into the factors influencing income inequality. By understanding the relationships between demographic, socioeconomic, and employment-related factors, I can identify areas for targeted interventions and policy changes.
**Key findings from the analysis include:**
**•	Age and Income: **Older individuals tend to have higher incomes, likely due to factors like experience, seniority, and higher-paying positions.
