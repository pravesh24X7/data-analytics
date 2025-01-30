### *Data Cleaning & Preprocessing*
1. What are the missing values in the dataset, and how will you handle them?
2. How do you handle the 'Age' column, given that it has missing values?
3. How would you treat outliers in the 'Fare' column?
4. How do you handle the 'Embarked' column, which has missing values?
5. What preprocessing steps would you take for the 'Cabin' feature, which has many missing values?
6. Should you drop the 'Name' column? Why or why not?
7. How do you handle the 'Ticket' column, which may not provide useful information for analysis?
8. Are there any duplicates in the dataset? How would you deal with them?
9. How can you deal with categorical variables like 'Sex', 'Embarked', and 'Pclass' in machine learning models?

### *Univariate Analysis*
10. What is the distribution of the 'Age' variable, and what does it reveal about the dataset?
11. What does the distribution of 'Fare' tell us about the dataset's socioeconomic representation?
12. How would you analyze the survival rate based on gender? What visualizations would you use?
13. How does the survival rate differ between the different passenger classes (Pclass)?
14. What is the distribution of the 'Embarked' variable, and how does it impact survival rates?
15. What are the survival rates for passengers based on their 'Pclass'? 
16. How would you visualize the correlation between numeric features like 'Age', 'Fare', and survival?
17. What patterns can you find from the 'SibSp' and 'Parch' columns in relation to survival?
18. How would you summarize the age distribution for survivors vs. non-survivors?
19. What is the distribution of the 'Ticket' feature, and does it provide any useful insights?
20. Can you visualize and compare the survival rate based on the 'Embarked' feature?

### *Bivariate Analysis*
21. How does the survival rate differ between men and women? 
22. What is the relationship between passenger class (Pclass) and survival rate? 
23. How do 'Pclass' and 'Sex' together impact survival rate? 
24. Can you plot a boxplot to compare the 'Age' distribution across different survival outcomes?
25. What is the correlation between 'Age' and 'Fare'? Does it suggest any underlying relationship?
26. Can you use Seaborn’s pairplot to explore relationships between 'Age', 'Fare', and survival?
27. What insights can you gain from visualizing the relationship between 'Pclass' and 'Fare'?
28. How does the survival rate vary with both 'SibSp' and 'Parch' columns together?
29. Can you identify any significant interaction effects between 'Sex', 'Pclass', and 'Survived'?
30. How does the 'Embarked' feature influence survival, and does it differ across Pclass?
31. What can you infer about 'Parch' and 'SibSp' in relation to survival? Would you consider creating a combined feature (e.g., Family size)?
32. How would you use Seaborn’s violin plots to analyze the distribution of 'Age' and 'Fare' by survival status?

### *Feature Engineering*
33. How would you create a new feature representing family size from 'SibSp' and 'Parch'?
34. Can you create a 'Title' feature from the 'Name' column (e.g., Mr., Mrs., Miss)? How would it help in the analysis?
35. Would you create a 'Fare per Person' feature? If so, how would it be useful?
36. How can you extract useful information from the 'Cabin' column by splitting it into 'Cabin letter' and 'Cabin number'?
37. Should you create a 'Deck' feature from the 'Cabin' column, and how could it impact survival analysis?
38. How could you categorize passengers into different age groups (e.g., child, adult, senior) and analyze their survival rates?

### *Advanced Visualization*
39. What can you conclude from visualizing survival rates using a heatmap of correlations among numeric features?
40. How would you create a stacked bar chart to show survival rates by gender and passenger class?
41. What insights can you derive from plotting survival against 'Age' using Seaborn’s *FacetGrid*?
42. Can you use a *countplot* to visualize the relationship between 'Embarked' and survival? How would you interpret the results?
43. How can you visualize survival rates across different combinations of 'Pclass', 'Sex', and 'Embarked'?
44. Can you create a violin plot to show the spread of 'Fare' for both survivors and non-survivors?
45. How do you analyze the relationship between 'SibSp' and survival using a Seaborn heatmap or cluster map?

### *Statistical Analysis*
46. What statistical test would you use to determine if survival rates differ significantly by gender? 
47. How would you test the hypothesis that passengers in first class had a significantly higher chance of survival compared to other classes?
48. Can you perform a chi-square test to assess the independence of survival and 'Embarked'?
49. How would you assess the correlation between 'Age' and survival, using a statistical method?
50. What is the significance of 'Fare' when analyzing survival rates? Is there a clear trend?