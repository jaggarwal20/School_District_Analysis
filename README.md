# School_District_Analysis

## Table of Contents
- [1.0 Project Overview](#Project-Overview)
  * 1.1 Purpose
  * 1.2 Resources
- [2.0 Results](#Results)

- [3.0 Summary](#Summary)

<a name="Project-Overview"></a>
## Project Overview
### 1.1 Purpose
The school board sees that academic dishonesty is occurring and want to remove the ninth graders from the list as their grades have been altered.

 1. Replace ninth graders reading and math scores with NaN
 2. Conduct a school district analysis

### 1.2 Resouces
- Data Source: schools_complete.csv and students_complete.csv
- Software: Python 3.6.1, Jupyter Notebook

<a name="Results"></a>
## Results
* Replace ninth graders reading and math scores with NaN. 
  
  ![alt text](Resource/ninth_nan.png)
  
  
* How is the district summary affected?

* How is the school summary affected?

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

* How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
   
   The percentage of students that passed math and reading significantly increased when removing the ninth graders.  The scores for math went from 66.9% to 93.2% and the reading scored went 69.7% to 97.0%. 
   
   Original:
   ![alt text](Resource/THS_Original.png)
   
   Removed the 9th graders:
   ![alt text](Resource/THS_No_9th.png)
   
  - Scores by school spending
    The scores by school spending did not change, as it is based off of per capitia.
    
    `Per Capita = per school budget/per school counts`
    
  - Scores by school size
   There were no changes in the school size, as the 9th graders from Thomas High School were only removed from the total count of students in the district.  The school size is based off of the following calculation
   `school_data_complete_df["school_name"].value_counts()`
   
  - Scores by school type

<a name="Summary"></a>
## Summary

Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

