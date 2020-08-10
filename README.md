# School_District_Analysis

# Overview
This code was done following a previous analysis of reports of grades for various subjects amongst different school districts. The original report monitored how schools were performing based upon pass rates for the various subjects broken up amongst grade level, passing rate for the exams, school spending per student as well as school type.

Following the intial report it was determined that, based upon the information contained within said report, academic dishonesty had taken place amongst the ninth grades students for Thomas High School in the subjects of reading and math. It was determined that these scores had been altered. Therefore, it was decided that these scores had to be removed from the overall reports so as to not scew the final reporting.

# Results
* Following the removal of the ninth grade reading and math scores for Thomas High School we can see how it affected the data. Below is the original district summary:

![](resources/District_summary_original.PNG)

and here is the district summary following the removal of the scores:

![](resources/District_summary_revised.PNG)

While ultimately the difference for the district as a whole is not the large, the only noticeable difference being the drop from average math scores from 79 to 78.9 and a corresponding drop in passing math percentage from 75 to 74%, as we drill down further in the data the impact of the removal will become more pronounced.

* Listed here is the original data for the school summary:

![](resources/per_school_original.PNG)

and here is the revised data following the cleanse:

![](resources/per_school2_revised.PNG)

We can see here that the changes are more pronounced with average math scores dropping from 83.41 to to 83.35 and a nearly 30% drop in the number of students passing math and reading.

* It is notable to check how the removal of these scores might affect Thomas' High Schools performance compared to the other schools on the list. In the original data base Thomas High School was listed as one of the top five performing schools in the county by pass rate.

![](resources/top_5_original.PNG)

Whereas after removing the fixed scores Thomas High School in no longer amongst the top five

![](resources/Top_5_Revised.PNG)

* When we check the ninth grade reading and math scores for students in Thomas High before the removal we can see the following data:

![](resources/grade_math_original.PNG)

![](resources/grade_reading_original.PNG)

However following the removal we have the following, due to all the scores being removed in favor of a null value:

![](resources/grade_math_revised.PNG)

![](resources/grade_reading_revised.PNG)

* Additionally when we look at how it changed the data for performance based upon school size we can see the original data:

![](resources/size_original.PNG)

versus the changed data

![](resources/size_revised.PNG)

We can see how the path rate has decreased dramatically for reading and math scores in the Medium Sized school bucket.

* Finally changes have also come about when we analyze the data based upon school type. Refer to the original data below:

![](resources/type_original.PNG)

versus the changed data

![](resources/type_revised.PNG)

We can see how the overall pass rate as well as the pass rate for reading and math has dropped.

