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
