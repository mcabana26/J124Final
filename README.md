# J124 Final Project: Data Analysis and Visualization of Diabetes Health Indicators
### By Melissa Cabana

## Story Summary and Sourcing

In the analysis of the ["Diabetes Health Indicators Dataset"](https://github.com/mcabana26/J124Final/blob/main/Diabetes%20Health%20Indicators%20Dataset%20-%20Diabetes%20Health%20Indicators.csv), out of the individuals reported to have diabetes, it was more prevalent in women compared to men, more people with a body mass index (BMI) of 30 or higher had it compared to other categories, more people with a reported highest education level of grade 12 or a GED had it compared to other education levels, and more people with an income of level of $75,000 or more had it compared to other income levels.  This potentially identifies being a woman, having a low education level, and having a high BMI as indicators for diabetes.  Why do more women have diabetes?  Is low education level intersectional with other socioeconomic and social factors, such as race and zip code, that may also be predictors?  Does having a high a BMI affect the worsening of the illness?  If so, how has diabetes treatment been adjusted to address this issue in all groups of patients?  With this findings paired with these additional questions, I will explore other sources to report on both why and how different groups may be more at risk of diabetes and possible methods to enhancing prevention and treatment with the knowledge of these possible predictors.


### Potential Interviews

1. **Dr. Marie Agleham**: A physician of Kaiser Permanente Northern California.  
* **Email**: Marie.L.Agleham@KP.org
* Dr. Agleham is involved with the Filipino American Care Experience (FACE), an organization that consists of Filipino-American physicians, that has organized a program that provides Bay Area Filipino Kaiser patients with diabetes classes as part of diabetes education treatment.  The classes are part of a concept called culturally-responsive diabetes education programs, which provide treatment to diabetes patients catered towards their culture and identity as a means to help close the critical care gap.  By interviewing Dr. Agleham, I hope to gain more information and insight on what issues found within data on diabetes patients that prompted her and her colleagues to start this program, and how that program may provide a solution to diabetes disproportionately affecting certain groups of people.

2. **Blake Silva**: A 21-year-old diabetes patient from Lodi, California in the Central Valley.  
* **Phone number**: (209) 993-0561
* I hope to gain insight on what it has been like to live with diabetes and how he believes his social factors have contributed to the conditions of his illness and treatment.  This would help give my story a more personal voice, as well as first person perspective on what it is like to like to live with diabetes and what can be improved on treatment wise.

### Additional Sources

The following two additional sources can add on to my story to make it more reliable, acccurate, as well as provide possible methods to finding data for analysis.  

1. ["Predicting Risk of Type 2 Diabetes by Using Data on Easy-to-Measure Risk Factors"](https://www.cdc.gov/pcd/issues/2017/16_0244.htm) is a study on using risk factors for Type 2 Diabetes to predict the risk of developing the illness.  This study could provide more information on how and why health predictors and risk factors are an effective tool for gauging the risk of developing diabetes.  In addition, this study may provide data that matches the findings in the data set analyzed, as well as what else can be analyzed, including other socieconomic or social factors.
2. ["Building Risk Prediction Models for Type 2 Diabetes Using Machine Learning Techniques"](https://www.cdc.gov/pcd/issues/2019/19_0109.htm) is a study on using machine learning techniques as a model for predicting the risk of developing Type 2 Diabetes.  This study could not only provide more data to help confirm findings from this data analysis, as well as other potential data to be analyzed, but also provide a possible method to a standarized predicting model for diabetes.

## Data Visualizations

*This [bar chart](https://datawrapper.dwcdn.net/mgk5J/1/) shows the six different levels of highest education received and how many patients from the dataset who have diabetes are in each of those categories:*

![bar chart](https://github.com/mcabana26/J124Final/blob/main/mgk5J-diabetes-patients-by-highest-education-level.png)

*This [bar chart](https://datawrapper.dwcdn.net/mgk5J/1/) shows the four different BMI categories and how many patients from the dataset who have diabetes are in each those categories:*

![bar chart](https://github.com/mcabana26/J124Final/blob/main/8YD3V-diabetes-patients-by-body-mass-index-bmi-.png)


## Data Analysis Process
* Download the ["Diabetes Health Indicators Dataset"](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset) as .csv files, upload to [Google Drive](https://github.com/mcabana26/J124Final/blob/main/Diabetes%20Health%20Indicators%20Dataset%20-%20Diabetes%20Health%20Indicators.csv), and open with [Google Sheets](https://docs.google.com/spreadsheets/d/1WJPAhUcL1bI6ilt2nX3dlz3LWssY-z3rVvXJrZ6b9TU/edit?usp=sharing)
* Freeze and bold row one
* Insert descriptions of variables as notes for each cell in row one **(Note: Refer to these descriptions to answer the question below)**
  

*The following are five questions and the process to finding their answers based on the dataset above:*

**Question 1: Which age group has the highest rate of diabetes?**

  1. Create a pivot table.

  2. Drag "Diabetes" and "Age" under "Rows" in the Pivot table editor.
    ![step 2](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%208.46.38%20PM.png)


  3. Drag "Diabetes" under "Values" in the Pivot Table editor, and click the dropdown menu under "Summarize by" and click "COUNT."
    ![step 3](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%208.48.19%20PM.png)
    
  **Optional: Show totals can be unselected since they are not needed.**

  4. Minimize rows "0" and "1" under the "Diabetes" column.
    ![step 4](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%208.49.08%20PM.png)

  5. In the Pivot table editor, go to the rows section, under "Age," click the dropdown menu under "Sort by" and click "COUNT," then click the dropdwon menu under "Order" and click "descending."
    ![step 5](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%208.50.02%20PM.png)
    
  **Answer: The age group with the highest rate of diabetes is the age group of 65 to 69 years old.**



**Question 2: Which BMI group has the highest rate of diabetes?**

  1. Create a pivot table.

  2. Drag "Diabetes" and "BMI" under "Rows" in the Pivot table editor.
  ![step 2](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.14.25%20PM.png)

  3. Drag "Diabetes" under "Values" in the Pivot Table editor, and click the dropdown menu under "Summarize by" and click "COUNT." Make sure that the box next "Show totals" under "BMI" is checked.
  ![step 3](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.08.51%20PM.png)

  4. Minimize rows "0" and "1" under the "Diabetes" column.
  ![step 4](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.09.26%20PM.png)

  5. Drag "BMI" under "Filter" in the Pivot Table editor, and click the dropdown menu under "Status," click "Filter by condition," then do the following conditions"
   * "Less than 18.5"
   * "Is between 18.5 and 24.9"
   * "Is between 25 and 29.9"
   * "Greater than or equal to 30"
    ![step 5a](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.15.12%20PM.png)
    ![step 5b](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.15.40%20PM.png)
    ![step 5c](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.16.30%20PM.png)
    ![step 5d](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2011.17.07%20PM.png)

  6. Compare the totals listed on row "2" under the "Diabetes" column of each condition. 
  
  **Answer: The BMI group with the highest rate of diabetes is 30 and above, or obesity.**



**Question 3: Out of those with diabetes, what is the average income level?**

  1. Create a pivot table.

  2. Drag "Diabetes" under "Rows" in the Pivot table editor.
  ![step 2](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%209.23.29%20PM.png)

  3. Drag "Income" under "Values" in the Pivot Table editor, and click the dropdown menu under "Summarize by" and click "AVERAGE."
  ![step 3](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%209.23.51%20PM.png)

  4. In the table, look for row "2" under "Diabetes" and look at the "AVERAGE of Income" for that row.
  ![step 4](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%209.24.21%20PM.png)
  
  **Answer: Out of those with diabetes, the average income level is between $25,000 and $35,000.**



**Question 4: Do females or males have a higher rate of diabetes?**

  1. Create a pivot table.

  2. Drag "Diabetes" and "Sex" under "Rows" in the Pivot table editor.
  ![step 2](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.49.21%20PM.png)

  3. Drag "Diabetes" under "Values" in the Pivot Table editor, and click the dropdown menu under "Summarize by" and click "COUNT."
  ![step 3](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.49.56%20PM.png)

  4. Minimize rows "0" and "1" under the "Diabetes" column.
  ![step 4](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.50.58%20PM.png)
  
  5. In the Pivot table editor, go to the rows section, under "Sex," click the dropdown menu under "Sort by" and click "COUNT," then click the dropdwon menu under "Order" and click "descending."
  ![step 5](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.51.38%20PM.png)
  
  **Answer: Females have a higher rate of diabetes.**



**Question 5: Out of those with diabetes, what is the most prevalent highest education level?**

  1. Create a pivot table.

  2. Drag "Diabetes" and "Education" under "Rows" in the Pivot table editor.
  ![step 2](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.55.13%20PM.png)

  3. Drag "Diabetes" under "Values" in the Pivot Table editor, and click the dropdown menu under "Summarize by" and click "COUNT."
  ![step 3](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.55.40%20PM.png)

  4. Minimize rows "0" and "1" under the "Diabetes" column.
  ![step 4](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.56.04%20PM.png)

  5. In the Pivot table editor, go to the rows section, under "Education," click the dropdown menu under "Sort by" and click "COUNT," then click the dropdwon menu under "Order" and click "descending."
  ![step 5](https://github.com/mcabana26/J124Final/blob/main/Screen%20Shot%202022-08-07%20at%2010.56.45%20PM.png)
  
  **Answer: Out of those with diabetes, the most prevalent highest education level is grade 12 or GED.**
