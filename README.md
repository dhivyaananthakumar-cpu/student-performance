 Student Performance Data Analysis
 Project Overview

This project analyzes student performance data using Python and Pandas. The dataset contains students' demographic information and their scores in Mathematics, Reading, and Writing.

 Objectives

1. Clean categorical features such as Gender, Race/Ethnicity, Parental Level of Education, Lunch, and Test Preparation Course.
2. Calculate statistical measures such as mean, median, standard deviation, and quartiles.
3. Create new features for Total Marks and Percentage.
4. Detect extreme performance outliers in subject scores.

 Technologies Used

1. Python
2. Pandas
4. NumPy
5. Google Colab

 Dataset Features

 Categorical Features

1. Gender
2. Race/Ethnicity
3. Parental Level of Education
4. Lunch
5. Test Preparation Course

 Numerical Features

1. Math Score
2. Reading Score
3. Writing Score

 Calculated Features

1. Total Marks
2. Percentage

 Statistical Analysis

The following statistical measures are calculated:

1. Mean
2. Median
3. Standard Deviation
4. First Quartile (Q1)
5. Third Quartile (Q3)

 Outlier Detection

Extreme performance outliers are detected using the IQR (Interquartile Range) method.

The lower and upper limits are calculated as:

 Lower Limit = Q1 - 1.5 × IQR
 Upper Limit = Q3 + 1.5 × IQR

Values outside these limits are considered outliers.

 How to Run

1. Open the program in Google Colab.
2. Upload the student performance CSV dataset.
3. Run the code.
4. The cleaned data, statistical measures, total marks, percentage, and outliers will be displayed.

 Conclusion

This project helps to understand student performance using basic data analysis techniques. It provides statistical information, calculates overall performance, and identifies unusual scores using outlier detection.
