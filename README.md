# School_District_Analysis
## This GitHub repository is created to assist Maria's team for school district analysis utilizing Anaconda, Jupyter Notebook and Python tools.  
### Originally this report was supposed to be a high-level snapshot of the districts in Py City Schools focusing on the following key metrics.
- Total number of students
- Total number of schools
- Total budget
- Average math score
- Average reading score
- Percentage of students who passed math
- Percentage of students who passed reading
- Overall passing percentage
### However, feedback from the board and Maria's supervisor expanded the report to include multiple dataframes which included high and low performing schools, average math and reading scores by grade, scores by school spending per student, scoring data by school size and type.  This analysis was completed in the PyCitySchools file, [PyCitySchools.ipynb](PyCitySchools.ipynb).  In an unexpected turn of events, The school board notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.  

### Therefore, the report deliverable has pivoted to a data scrub of the Thomas High School 9th grade data and a revised version of this report.  The deliverables pictured below will show display some of the code and visuals necessary to complete said analysis.
![Deliverable_1_Steps1_4](Deliverable_1_Steps1_4.jpg)
### For Deliverable 2, this report focused on the functional removing of the Thomas High School 9th grade data and the subsequent effects this data change - please see code and visualizations below.
![Deliverable_2_Steps1_2](Deliverable_2_Steps1_2.jpg)
![Deliverable_2_Steps3_4](Deliverable_2_Steps3_4.jpg)
![Deliverable_2_Steps5_12](Deliverable_2_Steps5_12.jpg)
![Deliverable_2_Steps13_14](Deliverable_2_Steps13_14.jpg)
![Thomas_High_School_Nan_Data](Thomas_High_School_Nan_Data.jpg)
### Please reference last 2 visualizations above.  Note the change for Thomas High School data was due to the NaN insertions for the 9th graders on the visualization directly above.  The Thomas High School data for the 10th - 12th graders on a step by step basis from the code and calculations show they performed at a high level for % Passing Math, % Passing Reading, and subsequentally a high overall passing grade was achieved at 90.6%.

Total Students                    1635
Total School Budget      $1,043,130.00
Per Student Budget             $638.00
Average Math Score           83.350937
Average Reading Score        83.896082
% Passing Math                93.18569
% Passing Reading            97.018739
% Overall Passing            90.630324
Name: Thomas High School, dtype: object
![High_and_Low_Performing_Schools](High_and_Low_Performing_Schools.jpg)
![Average_Math_and_Reading_Scores_By_Grade](Average_Math_and_Reading_Scores_By_Grade.jpg)
![Scores_by_School_Spending_Per_Student](Scores_by_School_Spending_Per_Student.jpg)
![Scores_by_School_Spending_Per_Student_Bins](Scores_by_School_Spending_Per_Student_Bins.jpg)
![Scores_by_School_Size](Scores_by_School_Size.jpg)
![Scores_by_School_Type](Scores_by_School_Type.jpg)
