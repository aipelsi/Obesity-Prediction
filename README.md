Ojectives
Understand obesity trends: Analyze data to comprehend the prevalence and incidence of obesity across different demographics and regions.
Predict future trends: Employ machine learning models to predict future obesity trends and identify potential intervention points.
Inform policy and intervention design: Translate data-driven insights into actionable strategies for health policy makers and public health officials.
Methods
Data Collection: The dataset included variables such as gender, age, dietary habits, physical activity, and genetic factors, derived from a variety of sources including the UC Irvine’s Machine Learning Repository.
Modeling Techniques Used:
Multinomial Logistic Regression to handle categorical outcomes of obesity classes.
Decision Tree Classification and Random Forests to predict obesity based on lifestyle and genetic factors.
Hierarchical Clustering to identify patterns and groups based on lifestyle factors which could be targeted in interventions.
Key Findings
Predictive Performance: The Random Forest model achieved a high accuracy rate, significantly better than the baseline, indicating robust predictive capabilities for identifying obesity levels.
Insights for Interventions: Decision tree analysis provided clarity on the importance of factors such as the number of main meals, vegetable consumption frequency, and physical activity in predicting obesity.
Behavioral Patterns: Hierarchical clustering revealed distinct lifestyle patterns that could be specifically targeted with customized public health interventions.
Impact
Policy Formulation: Insights from the project are being used to guide policy formulation, focusing on preventive measures and resource allocation that address high-risk groups identified by the models.
Intervention Design: Data-driven understanding allows for the design of targeted interventions, such as community fitness programs and nutritional education, tailored to the specific needs and habits of different population segments.
Conclusion
The Health Trends Analysis project has equipped policymakers and health officials with a deeper understanding of the factors influencing obesity, enabling them to deploy more effective and targeted health interventions. This project exemplifies how advanced data analysis and machine learning can play a pivotal role in modern public health strategies.


Independent Variables:

Eating Habits- Frequent consumption of high caloric food (FAVC), Frequency of consumption of vegetables (FCVC), Number of main meals (NCP), Consumption of food between meals (CAEC), Consumption of water daily (CH20), and Consumption of alcohol (CALC).
Physical Habits- Calories consumption monitoring (SCC), Physical activity frequency (FAF), Time using technology devices (TUE) Transportation used (MTRANS).
Other Variables: Gender, Age, Height, and Weight.

Dependent Variable: [NObesity] was created with the values of: Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III.

Body Mass Index (BMI) Calculation
The Body Mass Index (BMI) is calculated as the weight in kilograms divided by the square of height in meters:

BMI = Weight (kg) / Height (m)2

BMI Formula
