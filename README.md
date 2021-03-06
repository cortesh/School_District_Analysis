# Overview of the school district analysis:
The school board wants to investigate suspicious test results in reading and math for Thomas High School ninth graders. The objective is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Next, run a series of analyses on the school district to analyze student performance in comparison to other school metrics like budget and school size.

## Here is the list of deliverables for the analysis of the school district: 

* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
  * Top 5 and bottom 5 performing schools, based on the overall passing rate
  * The average math score received by students in each grade level at each school
  * The average reading score received by students in each grade level at each school
  * School performance based on the budget per student
  * School performance based on the school size 
  * School performance based on the type of school

## Results:

### How is the district summary affected?
A comparison of district summaries with Thomas High School 9th grade students reading and math scores removed made little to no significant change in the overall performance, with less than 1% difference between the two summaries.
 
 ![district_comparison](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/district_comparison.PNG)
 
 
### How is the school summary affected?

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

By far the most dramatic change is in the school rankings.  Thomas High School drops from 2nd place to 8th place after 9th grade scores are removed.

![school_comparison_before](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/school_comparison_before.PNG)
![school_comparison_after](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/school_comparison_after.PNG)

### How does replacing the ninth-grade scores affect the following:
----------------------------------------------------------------------------------------------------------------------------------------------
* Math and reading scores by grade: 
  Obviously the difference here is that 9th grade scores have been replaced with "NaN" in the after for both reading and math

**Before**
![reading_grade_before](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/reading_grade_before.PNG)
![math_grade_before](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/math_grade_before.PNG)


**After**
![reading_grade_after](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/reading_grade_after.PNG)
![math_grade_after](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/math_grade_after.PNG)


----------------------------------------------------------------------------------------------------------------------------------------------
* Scores by school spending: **NO CHANGE**

**Before**

![spending_summary_before](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/spending_summary_before.PNG)

**After**

![spending_summary_after](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/spending_summary_after.PNG)

----------------------------------------------------------------------------------------------------------------------------------------------
* Scores by school size: **NO CHANGE**

**Before**

![size_summary_before](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/size_summary_before.PNG)

**After**

![size_summary_after](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/size_summary_after.PNG)

----------------------------------------------------------------------------------------------------------------------------------------------
* Scores by school type: **NO CHANGE**

**Before**

![type_summary_before](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/type_summary_before.PNG)

**After**

![type_summary_after](https://github.com/cortesh/School_District_Analysis/blob/main/Resources/type_summary_after.PNG)


## Summary: 

1. District scores remained unchanged.
2. School rankings changed with Thomas High School dropping six places.
3. In grade level analyses, 9th grade scores are replaced with 'NaN'.
4. Other metrics remain unchanged.
