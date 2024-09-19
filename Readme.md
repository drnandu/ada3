#README
Nandu Meshram
ADA
Lab: Class One Survey Analysis
INSTRUCTIONS
Complete all tasks 1-7 using reproducible coding practices (annotation of all code). Use R syntax to solve all problems (i.e. do not manually change values/variables in datasets or check them manually to make sure things are correct except as a double or triple check). Please cut and paste each problem before each R markdown chunk and annotate your code within the chunks. Compare and consolidate your answers. Select one member of your group to walk the class through how each problem was solved. Elect one member of your group to turn in your consolidated code with answers.
1. Import class one survey data from our Github site (https://github.com/kijohnson/ADA-2024) (The dataset is called ‘Class 1 Survey Fall 2024_di.csv’), calling the R dataframe that you create C1survey.
2. Determine: a. the number of observations (i.e. the number of people who filled out the survey) and b. the number of variables in the dataframe.
3. a. Rename the column variables to something shorter and that is descriptive of what the variable is about (for example like_dogs for the ‘Do you like dogs?’ question variable) and b. Display that they are renamed.
4. Write code to determine and display the number of factor, integer, numerical, and character variables there are in the C1survey dataset.
5. a. Using code, check the bday and bmonth variables for any unusual or missing values. If you find any, b. describe what you will do with the unusual values in a comment before or immediately following the code that does it, and c. after you have cleaned up any unusual values, find the median bday and month. *Note: please make sure that your bday and month variables are numeric before doing statistics
6. a. Create a new variable called bseason that gives the season according to Northern Meteorological season in which respondents were born (winter = 12/1 to 2/29, spring = 3/1 to 5/31, summer = 6/1 to 8/31, fall = 9/1 to 11/30). b. Using the table function, print a table of Seasons in the columns and bmonths in the rows that allows you to check that the coding is correct c. Sum the columns using the addmargins function to answer the question of how many classmates were born in each season? Include your answer in the code.
7. Pick your favorite variable or variables to analyze, come up with a question you want to answer with that variable or variables, generate the code, and provide an answer to your question. Describe what you did using comments (i.e. #’s).
Research Question: Is there statistically significant association between the duration of experience in coding and the level of comfort in coding
Variables: “R_exp”, “coding_comfort”,


There is a moderate positive correlation (ρ = 0.556) between the amount of coding experience and comfort with coding.The relationship is statistically significant (p = 0.001751), meaning that more coding experience is associated with higher comfort levels in coding.