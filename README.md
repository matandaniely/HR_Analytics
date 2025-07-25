# About Dataset

Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists.

Education
1 'Below College'
2 'College'
3 'Bachelor'
4 'Master'
5 'Doctor'

EnvironmentSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobInvolvement
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

JobSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

PerformanceRating
1 'Low'
2 'Good'
3 'Excellent'
4 'Outstanding'

RelationshipSatisfaction
1 'Low'
2 'Medium'
3 'High'
4 'Very High'

WorkLifeBalance
1 'Bad'
2 'Good'
3 'Better'
4 'Best'

### Checking how many null existis (if any) 

<img width="497" height="602" alt="Screenshot 2025-07-25 at 15 32 46" src="https://github.com/user-attachments/assets/4ae36b8f-fe2e-4356-be70-50c482ad5ed9" />

### Describing data types and checking number of unique values for further filtration

<img width="1390" height="772" alt="Screenshot 2025-07-25 at 15 35 16" src="https://github.com/user-attachments/assets/c58df8b6-5b7c-4660-af56-a932bc6d58ce" />

### Dropping columns that wont contribute much value 

<img width="1192" height="133" alt="Screenshot 2025-07-25 at 15 36 25" src="https://github.com/user-attachments/assets/ca593ff6-2da9-4354-ab39-51895095adc2" />


## Breakdown of Distance From Home By Job Role and Attrition


### Visualizing how many employees contributed to attrition depending on distance from home between those who stayed and left 

By Number: 

<img width="2740" height="1339" alt="image" src="https://github.com/user-attachments/assets/f5a5f547-986c-4cda-a71b-3517417a3702" />

By Percentage:

<img width="2740" height="1339" alt="image" src="https://github.com/user-attachments/assets/52274a0a-3e20-47a2-bd29-18ab39ec672e" />

True Atrittion Rate per Job Role (leavers/ total in the role):

<img width="770" height="399" alt="Screenshot 2025-07-25 at 15 45 13" src="https://github.com/user-attachments/assets/2da1ec96-61e9-4abc-b493-50845a4ee4c6" />


## Key Insights: Job Roles with Notable Attrition Patterns
From the attrition analysis, five job roles stand out due to high attrition volume or rate. Here's a breakdown:

From this analysis it is important to point out 5 different job roles with significant realization: 

1) Laboratory Technicians

- 62 employees left the company — the highest count among all job roles.
- This accounts for 26% of all attrition cases.
- The company currently employs 197 active Laboratory Technicians.
- The attrition rate for this role is ~24%, making it the second-highest overall — behind Sales Representatives and ahead of Human Resources.

2) Sales Executives 

- 57 employees left, representing 24% of all attrition cases — the second-highest count.
- With 269 active employees, Sales Executives make up the largest job role in the company.
- Despite their large presence, their attrition rate is ~17.5%, ranking 4th highest among all roles.

3) Research Scientists

- 47 employees left — the third-highest number overall.
- This represents ~20% of total attrition.
- Currently, the company employs 245 active Research Scientists (the second-largest role by count).
- The attrition rate is ~16%, which ranks 5th among the 9 job categories.

4) Sales Representatives 

- 33 employees left, making up ~14% of attrition cases.
- The role has only 50 active employees, one of the smallest teams in the company.
- Their attrition rate is ~40%, the highest among all roles — indicating a serious retention issue.

5) Human Resources 

- 12 employees left, comprising ~5% of total attrition.
- With just 40 current employees, HR is the smallest department in the dataset.
- The attrition rate for HR is ~23%, placing it at 3rd highest across all job roles.

Intermediate Summary

- Sales Representatives face the most critical retention challenge with a 40% attrition rate.
- Laboratory Technicians and Sales Executives contribute the most to the absolute number of employees who left.
- Human Resources and Research Scientists have above-average attrition rates that merit attention despite lower headcounts.


## How Distance From Home Influences Attrition

<img width="769" height="398" alt="Screenshot 2025-07-25 at 15 47 24" src="https://github.com/user-attachments/assets/03ef15e7-2613-4fbf-84b0-5c92eedee54f" />

<img width="759" height="400" alt="Screenshot 2025-07-25 at 15 47 52" src="https://github.com/user-attachments/assets/888f98d1-b190-41fe-b8b8-acff3b72610c" />


### Analysis of Distance Effect
A boxplot visually represents the distribution of a dataset by displaying the median, quartiles, and potential outliers. It summarizes the data using five key values: the minimum, first quartile (Q1), median, third quartile (Q3), and maximum.

A histogram is a graphical representation of the distribution of numerical data, where the data is grouped into ranges (bins) and the frequency of each range is represented by the hight of the bar.

Sales Executives

The boxplot suggests that attrition among Sales Executives is slightly skewed toward longer commutes, with a median around 12 km and distances reaching the maximum of 29 km. While the histogram shows a noticeable number of departures above 10km, further comparison with employees who stayed would be needed to assess wheter distance truly plays a role in attrition.

Laboratory Technicians

The median is around 7 km. However, the histogram reveals an irregular distribution, with high counts at both short (2km) and longer distances (24 km), and gaps in between. This lack of a clear pattern suggets that distance alone may not be a strong predictor of attrition for this role.

Sales Representative

Sales Rep who left the company tended to live closer to the office, with a median distance around 7 km and a distribution skewed towards lower values. Interestingly, this suggets that proximity did not correlate with retention for this role - though a proper comparison with those who stayed would be needed to confirm this.

Research Scientist

The median distance from home for Research Scientist who left the company is 8 km, with a distribution that is slightly skewed toward higher distances. The boxplot shows a wide spread of values and visible gaps in the lower range, suggesting that employees left from a variety of locations. While the histogram shows that some attrtion occured at longer distances, the overall pattern does not strongly suggest that distance from home alone is a driving factor.

Human Resources

Among the top five job roles analyzed, Human Resources shows the highest median distance from home at approximately 15 km, though the sample size is relatively small (12 employees). The histogram reveals a wide spread of departure distances between 6 km and 20 km, with no single distance showing more than two occurences. This indicates a more evenly distributed pattern of attrition, without clear concentration at either short or long commutes

____________________________________________________________________________________________

### Analyzing Monthly Income by Education Level and Attrition

<img width="674" height="396" alt="Screenshot 2025-07-25 at 15 50 13" src="https://github.com/user-attachments/assets/c363975c-dcbb-49fb-9eaa-6265cc18d8c0" />

<img width="936" height="352" alt="Screenshot 2025-07-25 at 15 51 09" src="https://github.com/user-attachments/assets/c2f51861-25a8-4494-b115-3fb0d0a46dec" />


<img width="1544" height="1143" alt="image" src="https://github.com/user-attachments/assets/8bfcaf1a-a201-4a29-9eb4-99a2430c5210" />



The two charts and the table all confirm the same: potentital dissatisfaction or mismatch when income expectations aren;t met are more prominant in those who left. In all categories of educations we see that those who left had a lower mean of income. Also the spread is lower indicating that even those who were paid the most in those groups still earned less than the max of those who stayed.

Across both attrition groups:
- Employees with Doctorate or Master's degrees tend to earn more than those with Below College or College education. 
- The Doctor group shows the highest income diustribution and widest spread - especially for those who stayed. Interestingly, the mean of the two groups inside the Doctor group show the same mean. We can observe that from those who left, the data is more skewed towards the lower income, suggesting that salary mismatach might have been more prominant in this group. 

Variabilty and Outliers:
- Increasing spread (interquantile ranges) between all groups as the education level increases. Especially in the "No" group. 
- There are many high income outliers, especially College, Master and Doctor education levels and is more prominant in the "No" group. 

Highest Attrition in Lower Income Ranges
- For each education group, the left (green) boxes are consistently lower, indicating those who left the company tend to earn less. 
- This is most prominant in Below College, Bachelors and Doctor categories - showing a potential dissatisfaction or mismatch at higher education levels when income expectations arn't met.


____________________________________________________________________________________________

### SQL Queries For Further Analysis

<img width="536" height="772" alt="Screenshot 2025-07-25 at 22 20 46" src="https://github.com/user-attachments/assets/62a555d3-ed3e-42d9-acf0-1872d3d227af" />

<img width="638" height="214" alt="Screenshot 2025-07-25 at 22 21 03" src="https://github.com/user-attachments/assets/4877bd81-0455-4640-8a23-eeaab01b127e" />


<img width="711" height="762" alt="Screenshot 2025-07-25 at 22 21 18" src="https://github.com/user-attachments/assets/387b376e-679a-4666-96c2-32aed2ea5e38" />

<img width="634" height="394" alt="Screenshot 2025-07-25 at 22 21 32" src="https://github.com/user-attachments/assets/20a25240-c031-441f-a244-0d3505ed5c64" />





<img width="1719" height="1139" alt="image" src="https://github.com/user-attachments/assets/4c4c84c9-9b89-4226-b391-0f766c30ccab" />


