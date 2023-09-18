# Fifa21_Project
Resolving the Fifa project

Presentation: Data Analysis by Team Lewandowski Fifateam


Introduction

Team: Raul, Maria, Laura, Antonio

Project: Data Analysis in FIFA 21

Objective: Finding players with low value but high potential


Work Methodology


a) Initial Planning

We used Trello for planning and task organization.

We defined a detailed roadmap to guide our work.


b) Work Roadmap

Library Importation

Data Reading: CSV 'fifa21_male2.csv'

Data Cleaning: Column and NaN value checks.

Numeric Data: Creation of the fifa21_male2_numeric dataframe.

Filling Missing Values: Replacing NaN with the mean.

Selection of Relevant Variables: Creation of df_age_total_base.

Categorical Data: Creation of the fifa21_male2_categorical dataframe.

Removal of Irrelevant Columns.

Dataframe Union: New_Df_fifa1 (Numeric Data + Categorical Data).

Additional Cleaning: Height and weight correction.

Monetary Value Conversion: €, K, and M.

Final Data Preparation: Addition of necessary columns.

Conversion to Numeric Format.

Correlations: Analysis of OVA, POT, Height, Weight, Value, and Wage.

Identification of Underrated Players: Value < 2M and OVA > 75.

Linear Regression: Analysis of Player Potential and Value.

Model Evaluation: R2 Score.


Conclusions


Variable Selection: In projects with large datasets, careful variable selection from the outset is crucial.

Data Cleaning Importance: Data cleaning takes time and can be a critical step for project success.

Flexibility in Approach: Changing the project's objective may require a shift in focus, but having clean data facilitates this transition.

Efficient Collaboration: The use of tools like GitHub enables effective tracking and collaboration among team members.


Acknowledgments


We appreciate all team members for their hard work and dedication to this project.

Questions

Any comments or questions about our data analysis project?



