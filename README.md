# Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB

![image](https://github.com/Sdec30/Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB/assets/140704907/0b998e01-7e98-45da-b5f0-f59edf1e4c74)

Author: **Sneha Bhaskar**

Date: 10 October 2023

# Overview

The Employee Performance Analysis delves into a dataset to identify determinants of employee ratings, using a data-centric approach to guide HR strategies. Performance trends were observed across departments like Sales, HR, and Data Science, with Employee Environment Satisfaction, Last Salary Hike, and Work-Life Balance emerging as critical factors. Notably, logistic regression, with its superior predictive accuracy for this data's categorical nature, was deemed more apt than linear regression, emphasizing the importance of model selection based on data characteristics. 

# Business & Goal of this project

In today's competitive business landscape, employee performance plays a pivotal role in a company's success. Organizations need to understand the factors influencing employee performance to optimize workforce strategies, foster employee growth, and maintain a competitive edge. For the company in question, having a comprehensive and data-driven understanding of the performance determinants can enable effective HR decisions, from recruitment strategies to tailored training programs.

The primary objective of this project is to derive actionable insights from the Employee dataset to understand the critical factors affecting employee performance ratings. By leveraging data analytic skills, the company aims to predict performance ratings with high accuracy and pinpoint the most influential features. The insights obtained will serve as a foundation for data-driven decision-making in HR strategies, leading to improved employee performance and, by extension, organizational growth.

# Key Findings 

# Department Wise Performance Rating

![image](https://github.com/Sdec30/Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB/assets/140704907/b6c9dc20-f765-4a6b-a9dc-603730e88aa0)

![image](https://github.com/Sdec30/Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB/assets/140704907/3156e8e9-dd15-4fe2-abba-825b8d0044ab)

**At a Glance: How Departments Are Performing**

**Sales:** In the sales world, most employees are hitting the mark with a performance rating of 3. Men have a slight edge in their ratings over women.

**Human Resources:** Most HR professionals are rocking a performance level of 3. A special shoutout to older employees in HR; they might be a tad behind in their ratings. But the women in HR? They're shining stars, consistently delivering top-notch work.

**Development:** The majority of folks in Development are consistent performers, scoring a level 3. Age doesn't seem to matter here - young or old, they're all at the top of their game. As for gender, it's a tie; both men and women are equally impressive.

**Data Science:** Now, this is an exciting department! They boast the highest average of level 3 performers. It's noteworthy to mention that there's a smaller bunch of level 2 performers here compared to other departments. And guess what? Men in Data Science are outperforming a bit!

**Research & Development:** Age is just a number in R&D! Employees of various ages can be found at each performance level. A thumbs-up to the women in this department; they're bringing their A-game.

**Finance:** The finance realm offers an interesting insight: as employees age, their performance seems to take a dip. Men seem to be at the forefront in terms of performance. A notable mention: more experienced folks might be facing challenges, as their performance tends to decrease a bit.

# TOP 3 FACTOR AFFECTING TO THE EMPLOYEE PERFORMANCE

From the visualisation file, we get the top 3 factors affecting employee performance

# 1. Employee Environment Satisfaction

![image](https://github.com/Sdec30/Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB/assets/140704907/a7c622c2-7e64-4603-a76a-f39d876085e6)

Maximum Number of Employees Performance Rating belongs to EmpEnvironmentSatisfaction Level 3 & Level 4

ranking score means;

**Low: 19%**

Description: Employees who rank their satisfaction as "Low" are generally unhappy or discontent with their working environment. This might be due to a number of reasons such as inadequate facilities, poor ergonomics, excessive noise, lack of cleanliness, or other factors that affect their comfort and ability to work productively.

Implications: Low satisfaction often leads to decreased morale, lower productivity, and potentially higher turnover. It's crucial for management to identify the causes and work towards improving the working conditions. Medium:

**Medium: 20.2%**

Description: A "Medium" rank indicates that employees find their working environment to be average. They might have certain elements they are happy with, but there might be areas of improvement. They neither feel too discontent nor too pleased.

Implications: Employees who rank their satisfaction as medium might not be urgently looking to leave, but they're not fully engaged either. It's a signal for management that there are areas to be improved, but the situation isn't critical. High:

**High - 30.6%**

Description: Employees who give a "High" rank are generally pleased with their working environment. They find most facilities and conditions to be conducive to work, and they feel comfortable in their workspace. It indicates that the organization is taking good measures to ensure employee comfort.

Implications: High satisfaction levels are linked to better morale, increased productivity, and lower turnover. However, it's always beneficial for management to stay proactive and continue seeking feedback to maintain or even enhance this satisfaction level. Very High:

**Very High - 30.1%**

Description: A "Very High" ranking denotes that employees are extremely satisfied with their working environment. This could mean that not only are the basic needs met, but there are additional perks, amenities, or conditions that enhance their work experience. Such environments might include advanced ergonomic setups, appealing aesthetics, state-of-the-art facilities, and a positive, inclusive culture.

Implications: A very high satisfaction level is indicative of a workplace that truly values and understands the importance of a good working environment. Such organizations likely see higher employee loyalty, increased efficiency, and a stronger organizational culture.

# 2. Employee Last Salary Hike Percentage

![image](https://github.com/Sdec30/Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB/assets/140704907/073419eb-c222-4c52-8b95-9dfd46769ab1)

**Employees with a Salary Hike Percentage of 11-19%**

Observation: A majority of employees who received a salary hike in the range of 11-19% have been observed to receive performance ratings of 2 (Good) and 3 (Excellent).

Elaboration: If a company is awarding salary hikes in the range of 11-19%, it could indicate that these employees are delivering consistent performance, but perhaps not exceptionally above and beyond what is expected. This is reflected in the 'Good' and 'Excellent' performance ratings.

Employees with a 'Good' rating might have met their targets and expectations, hence the reasonable hike. Those with an 'Excellent' rating might have slightly exceeded the expectations, justifying a higher percentage in the same range.

The data suggests that employees in this salary hike range have shown considerable merit, but not enough to break into the highest echelons of performance (Outstanding).

**Employees with a Salary Hike Percentage of 20-25%**

Observation: Employees who received a salary hike in the range of 20-22% predominantly have a performance rating of 4 (Outstanding).

Elaboration: Such a significant salary hike implies that these employees have demonstrated exceptional performance. Their contributions have had a notable positive impact on the organization, warranting a substantial financial reward.

A performance rating of 'Outstanding' indicates that these employees consistently went above and beyond their job roles, showing innovation, leadership, and a significant impact. They might have achieved and even surpassed high-target goals, introduced transformative ideas, or taken on additional responsibilities.

By giving them such a hike, the company is not only rewarding their stellar performance but also possibly trying to retain these top talents by making them feel valued and recognized.

# 3.Employee Work-life balance

![image](https://github.com/Sdec30/Capstone_ProjectDAT7_EmployeePerformanceAnalysis_SB/assets/140704907/583b3a47-f80f-444b-8c61-a0e4cc56f447)

EmpWorkLifeBalance - Assessment of work-life balance

ranking;

Bad
Good
Better
Best
Interpretation

This heatmap shows that employees with a 'Better' work-life balance rating (level 3) tend to have excellent performance ratings, this suggests several insights:

Importance of Balance: Employees who perceive their work-life balance as 'Better' tend to perform better. This underscores the importance of fostering a work environment where employees can achieve a satisfactory balance between work and personal life.

Motivation and Productivity: A 'Better' work-life balance might indicate that employees are less stressed, more motivated, and more satisfied with their jobs, leading to higher performance levels.

Comparison with Other Levels: The strength of this relationship becomes even more pronounced if the 'Better' rating's darker squares starkly contrast with those of other ratings. For instance, if employees with a 'Good' or 'Best' work-life balance don't show as strong a pattern with performance, it might indicate that there's something unique about the conditions or perceptions of the 'Better' group.

# Regression analysis 

Linear regression resulted in an R-square value of 0.53, while logistic regression yielded a more promising 0.85. Given the nature of the dataset and the categorization of employee performance ratings, logistic regression proves to be a more suitable model.

Importance of Logistic Regression for This Dataset: Linear regression, which is predominantly used for continuous dependent variables, did not reveal a strong correlation between the variables in this dataset. However, the higher logistic regression score of 0.85 indicates its efficacy in predicting categorical outcomes like employee performance ratings.

In summary, for datasets where the dependent variable is categorical, like our performance ratings, logistic regression offers a more relevant and effective analytical approach compared to linear regression.

# Message for the Human resources and companies 

To optimize employee performance, it's pivotal to provide an ergonomic workspace and foster an inclusive culture. Regular salary assessments aligned with market standards, combined with performance incentives, ensure competitive compensation. Emphasizing work-life balance with flexible hours and remote work options is crucial, as is continuous learning. Frequent feedback, data-driven decision-making, cross-department collaboration, timely recognition, and clarity in career progression are all instrumental in enhancing overall employee satisfaction and performance.
