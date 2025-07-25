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

Analysis of Distance Effect
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



<img width="1544" height="1143" alt="image" src="https://github.com/user-attachments/assets/8bfcaf1a-a201-4a29-9eb4-99a2430c5210" />

### Analyzing Monthly Income by Education Level and Attrition

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
