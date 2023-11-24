# Medical Data Visualizer

![image](https://github.com/Munchkinland/Medical-data-visualizer/assets/92251234/4f014139-d036-4548-9b07-4dabb4cc3b43)

Medical Examination Data Analysis
This repository contains Python code to perform analysis on medical examination data. The dataset used is stored in the "medical_examination.csv" file.

Features Added
Overweight Column:

Added an "overweight" column to the dataset, indicating whether an individual is overweight based on BMI.
Normalized Cholesterol and Glucose:

Normalized the "cholesterol" and "gluc" columns, making 0 always good and 1 always bad. If the value is 1, it is changed to 0; if the value is more than 1, it is changed to 1.
Visualizations
1. Categorical Plot
The categorical plot displays the counts of various health-related features split by the presence or absence of cardiovascular disease.

Categorical Plot

2. Heat Map
The heat map visualizes the correlation matrix of selected health parameters. It only includes data within certain ranges to focus on the significant correlations.

Heat Map

Code
The code uses Python with the following libraries:

pandas
seaborn
matplotlib
numpy
The draw_cat_plot function generates the categorical plot, and the draw_heat_map function generates the heat map.

Feel free to explore and modify the code for further analysis or visualization.

Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer
