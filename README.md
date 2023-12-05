# University-Data-Analysis
This dataset is about a university. It recently started offering differnt types of courses. I will be leveraging the Pandas libraries to import and clean data making sure all erroneus/missing values are removed. 
Seaborn and Matplotlib will be used to create informative visualisations about the dataset. Sci-kit Learn will be used to implement machine learning algorithms to better predict the enrollment count for differnt courses.

## Dataset Explained

| Column Name| Criteria |
| ---------- | :---------- |
| course_id | Nominal, unique identifier| 
| course_type  | Nominal, two options 'online' or 'classroom'. Replace missing values with 'classroom'|
| year   | Discrete, ranges from 2011,2022. Missing values replaced with 2011|
| enrollment_count    | Discrete, replace missing values with 0| 
| pre_score    | Continuous, average score of enrolled students on precourse exam. Replace missing values with 0|
| post_score    | Continuous, average score of enrolled students on post course exam. Replace missing values with 0| 
| pre_requirement    | Nominal, prior course completion requirement for students to enroll. Replace missing values with 'None'| 
| department    | Nominal, departments offering courses. 4 options“Science”, “Technology”, “Engineering”, “Mathematics”. Replace missing values with 'unknown'| 

## Techniques
-	Analysed dataset using Pandas to find missing or erroneous data, replacing with appropriate values
-	Demonstrated skills in Seaborn and Matplotlib to show visualisations between key variables
-	Performed feature engineering to create relevant features for machine learning
-	Implemented and evaluated machine learning algorithms from Scikit-Learn to see which was most suitable for the business problem
