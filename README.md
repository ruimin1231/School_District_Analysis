# **Written report on the employee database analysis


## **Overview of the analysis**

This report aims to report and present insights about the performance trends and patterns of the Pycity schools. It will inform discussions and strategic decisions at the school and district level through using Pandas, the Python Data Analysis Library. This analysis includes retrieving and parsing the schools' data, such as accessing every student's math and reading scores as well as various information on the schools they attend and analyzing data on student funding and students' standardized test scores. This report will assist the school board regarding the school budgets and priorities.

## **Results**

*1. The influence by shool budget*
      -  From the DataFrame of the *summary_df*, we can see that there is no clear trend about how the total school budget and per student budget could influence the student's performance on math and reading scores.

The data of retiring the entire school information as the following image shown:
      ![This is an image](https://github.com/ruimin1231/School_District_Analysis/blob/main/summary_df.png)

      
*2. The influence by shool size*
            -  From the DataFrame of the *score_percentage_by_school_size,* we can see that the schools in small school sizes (<1000) generally have higher scores on both average and overall scores. The DataFrame of *overall-df* shows that Cabrera High School has the highest overall passing percentage (91%) as well as average scores on math (83%) and reading(83%), whereas Bailey High School, with the highest per-student budget ($628) but has the nearly lowest scores, 54% on overall passing, 77% on average math score and 81% on reading score. Though Cabrera High School has quite a lower per-student budget ($582), they have a smaller number of students (1858), compared with the students' numbers at Bailey High School (4976). These data trends bring a hypothesis that smaller numbers of students may allow the teachers easier to teach and maintain a higher teaching quality.
      
The data of the summary of the school information as the following image shown:
      ![This is an image](https://github.com/ruimin1231/School_District_Analysis/blob/main/overall_df.png)



## **Summary**

Given the data info from the CSV file, we have the info of school type, total students numbers, total and per-student budget, average and passing scores of math and reading. However, this information still can't guarantee us a clear clue of how the budget and school size affect the students' performance. To assist the school board makes a better decision, we probably need more info. For instance, the background info of teachers and faculties per school, school location, demographic, etc., all of these will help us analyze the factors that influence the education performance deeper.


