# Project 1: Standardized Testing, Statistical Summaries and Inference

### Problem Statement

The SATs and the ACTs are the two most popular exams used for admissions into colleges in the United States of America (USA). However, their differing assessment criterias, subjects tested and grading standards has divided students to pick one over the other. This has also been reflected onto the popularity of the exams across all states in USA.

With various state-wide and college-based regulations as well as mandatory ACT testing in certain states, there seems to be a decline in the participation rate of the SATs. The [New York Times](https://www.nytimes.com/2020/05/23/us/SAT-ACT-abolish-debate-california.html) has even reported that University of California will stop requiring the need for SATs and ACTs for admissions entirely. 

---

### Executive Summary 

This Project will investigate and understand the trends between the participation rates and scores of the SATs and ACTS from the years 2017 to 2018. From the findings, recommendations will be proposed to improve the participation rates of the SATs. To successfully provide these recommendation, we had to understand the SAT and ACT datasets of 2017 and 2018 to understand the trend between the variables in the datasets, which was done through exploratory data analysis. Then we proceeded to explore these trends further through data visualisations such as correlation heatmaps, scatter plots, box plots and choropleth maps. With extra research on the side, we were able to pick out the criteria of the states that we wanted to improve and picked South Dakota as the ideal state. South Dakota does not have any mandated admission tests and still had a relative number of participation rates indicating students that are interested and willing to take part in the admissions tests. Some ways to improve the participation rate was through subsidies, improved learning resources, accesible locations and campaigns.

### Data Dictionary (SAT AND ACT 2017 Data Sets)

|Feature|Type|Dataset|Description|
|:---|:---|:---|:---|
|state|object|sat2017/act2017|Name of a state in USA|
|sat_part_2017|float64|sat2017|Participation Rate of a State| 
|sat_erw_2017|int64|sat2017|Average Evidence-Based Reading and Writing Score of a State| 
|sat_math_2017|int64|sat2017|Average Math Score of a State| 
|sat_total_2017|int64|sat2017|Average Total Score of a State| 
|act_part_2017|float64|act2017|Participation Rate of a State| 
|act_english_2017|float64|act2017|Average English Score of a State| 
|act_math_2017|float64|act2017|Average Math Score of a State| 
|act_reading_2017|float64|act2017|Average Reading Score of a State| 
|act_science_2017|float64|act2017|Average Science Score of a State|
|act_composite_2017|float64|act2017|Average Composite Score of a State|

### Updated Data Dictionary (Merged Data Set)

|Feature|Type|Dataset|Description|
|:---|:---|:---|:---|
|state|object|final|Name of a state in USA|
|sat_part_2017|float64|final|Participation Rate of a State in 2017| 
|sat_erw_2017|int64|final|Average Evidence-Based Reading and Writing Score of a State in 2017| 
|sat_math_2017|int64|final|Average Math Score of a State in 2017| 
|sat_total_2017|int64|final|Average Total Score of a State in 2017| 
|act_part_2017|float64|final|Participation Rate of a State in 2017| 
|act_english_2017|float64|final|Average English Score of a State in 2017| 
|act_math_2017|float64|final|Average Math Score of a State in 2017| 
|act_reading_2017|float64|final|Average Reading Score of a State in 2017| 
|act_science_2017|float64|final|Average Science Score of a State in 2017|
|act_composite_2017|float64|final|Average Composite Score of a State in 2017|
|sat_part_2018|float64|final|Participation Rate of a State in 2018| 
|sat_erw_2018|int64|final|Average Evidence-Based Reading and Writing Score of a State in 2018| 
|sat_math_2018|int64|final|Average Math Score of a State in 2018| 
|sat_total_2018|int64|final|Average Total Score of a State in 2018| 
|act_part_2018|float64|final|Participation Rate of a State in 2018| 
|act_english_2018|float64|final|Average English Score of a State in 2018| 
|act_math_2018|float64|final|Average Math Score of a State in 2018| 
|act_reading_2018|float64|final|Average Reading Score of a State in 2018| 
|act_science_2018|float64|final|Average Science Score of a State in 2018|
|act_composite_2018|float64|final|Average Composite Score of a State in 2018|

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017/18.

### Conclusions and Recommendations

Key Takeaways: 
Although no University/College in America has ever provided preference of one admission test over the other, there is a lot of competition between the two tests. It is also interesting to see how different states delegate to mandate either tests or make them completely optional. 

Additionally, there is a strong negative correlation between the participation rates for both tests. There is also a strong negative correlation between the participation rates and the total test scores as well. Both the participation rates for individual tests are positively related for both years. 

Recommendations for promoting SATs

1. Subsidies/Absorb Costs of SATs

Students no longer have to worry about expensive tests and provides accessibility, even to lower income households, to take the SATs

2. Improved Exam Preparation Resources

Collaborate with non-profit organisations/education companies to provide free learning resources (both online and offline) for students to prepare for the tests.

3. Location of Testing

Students are able to take the tests from the nearest educational institute from their place. This enhances accessibility and saves travel time for students, allowing them more time to prepare for their tests. 

4. Campaigns

Provision of talks in High Schools to increase understanding in students regarding the benefits of taking the SATs
