# Correlation-Regression-Analysis
Still on Dover Insurance, I was also tasked with leveraging survey data and regression techniques to identify key drivers of overall wellbeing.

By examining employee responses on a 0-100 scale, I identified patterns that could inform HR strategies for improving workplace wellness. 

*I have videos showing my processes in real-time in **[this article](),** incase you would prefer that.*

## Task Overview
- Identify key factors influencing overall employee wellbeing through correlation analysis 
- Run a regression model to pinpoint the most significant drivers of employee wellbeing 
- Evaluate limitations of the model and identify additional data sources for deeper insights

**Tools used:**
Microsoft Excel 

By understanding what truly impacts their employee's wellbeing, Dover Insurance can design better policies, improve employee satisfaction, and reduce turnover— leading to a healthier work environment and better business outcomes.

## Introduction
The Regression worksheet contains separate survey data from a smaller random sample of employees, with statements below on a 0 to 100 scale:
- Overall Wellbeing (Target Variable)
- Work Stress
- Relationship with Manager
- Negative Feelings at Work
- Friendships at Work
- Opportunities for CPD (Continuous Professional Development)


# Correlation Analysis
## Step 1: 
- I opened the 'Regression' worksheet, added filters and then checked for missing/ inconsistent values, ensured the values are on the same 1-100 scale. 
- I cross-checked the survey questions to be sure they are related to overall wellbeing 

## Step 2: 
- I selected my dataset and used the data analysis feature under the data tab to perform correlation analysis (data > data analysis > correlation) 
- I analyzed the correlation matrix for strong positives (closer to +1), and weak negatives

![image](https://github.com/user-attachments/assets/ddfd6dab-b748-4139-9816-68afe3448df0)

**Key Findings:**
- Positive drivers of wellbeing:
From the results, employees who have good relationships with their managers tend to report higher overall wellbeing, and those with good friends at work reported the same, both showing the importance of a supportive work environment.

- Negative drivers of wellbeing: 
The most significant negative driver of wellbeing is strong negative feelings at work, which has the highest negative correlation with overall wellbeing; similarly, high work stress was another notable factor reducing wellbeing. This could indicate that workload management and mental health support could be key intervention points.

# Regression Analysis 
First I used correlation analysis to determine the direction of relationships between the drivers and overall wellbeing. Next I am doing multiple regression analysis to determine what variables are statistically significant predictors of overall wellbeing.

I selected the data in the 'Regression' worksheet and used the data analysis feature to automatically perform the calculations like so; data > data analysis > regression

**Important parameters:**<br>
R-squared:<br>
- 0.47, which means that about 47% of the variation in overall wellbeing is explained by the independent variables (the survey questions)

P-values: 
- P-values below 0.05 are NOT significant to overall wellbeing, and the independent variables that fall under this category are 'friends at work' ('I have good friends at work' column), and 'opportunities for CPD' ('There are ample opportunities for CPD at work' column). 

- Independent variables with P-value above 0.05 are statistically significant to overall well-being, and they include 'my work is stressful and pressurized,' 'I have a good relationship with my manager,' and the 'I regularly have strong negative feelings at work' columns. 

![image](https://github.com/user-attachments/assets/d46cbf5d-2fbb-4562-8c2f-3f268b3d2e8d)

So, for every 1-point increase in work stress, and negative feelings, overall well-being drops by 0.27 & 0.44 points respectively, while for every 1-point increase in manager relationship, overall wellbeing heightens by 0.28 points. (see co-efficient column)

## Conclusion 
The analysis above informs that priorities should include;
- Reducing workplace stress
- Improving employee-manager relationships by encouraging managers to be supportive
- Addressing negative emotions at work through mental health support, workplace culture, and conflict resolution.

