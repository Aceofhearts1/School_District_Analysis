# School_District_Analysis
## Overview of the district Analysis
The purpose of the analysis was to gather info through the data that was collected. After having inserted it into our code we were to read the data and come up with some tables to help read the data. However, the data had a few errors that needed to be cleaned in order to properly show the results.
## Results of removing Thomas High's 9th grade scores for academic dishonesty
- The district summary was not affected. When you really think about it, a single grade within a district wouldn't really change  such a large sample size. We see that through the data.
- The school summary was affected but only one row. That would be the Thomas High School row. Their scores were altered since we replaced the values with NaN. The School Type and Budget weren't affected. You would not really expect them to be since we did not do anything to alter those numbers.
- Removing the ninth grade math and reading scores negatively affected Thomas High School's performance.It dropped their average a few percentage points down. Not enough to react over still.
-These were the following affects of replacing the scores (The left being the original numbers and the right being the new numbers):
1 The math scores:
!https://github.com/Aceofhearts1/School_District_Analysis/blob/main/Resources/Passing_by_math_grade.png
2 The reading scores:
!https://github.com/Aceofhearts1/School_District_Analysis/blob/main/Resources/Passing_by_reading_grade.png
3 Scores by School spending:
!https://github.com/Aceofhearts1/School_District_Analysis/blob/main/Resources/Passing_by_spending.png
4 Scores by school size:
!https://github.com/Aceofhearts1/School_District_Analysis/blob/main/Resources/Passing_by_SchoolSize(4).png
5 Scores by school type:
!https://github.com/Aceofhearts1/School_District_Analysis/blob/main/Resources/Passing_by_school_type.png
## Summary of four changes to the School District Analysis
- The ninth grade class as a whole in the district was affected. Removing the ninth grade class at a school would impact the district's ninth grade class numbers.
- Thomas High school's whole school's numbers were changed since we removed around 1/4 of their numbers. They remained a top five school, but by a lesser margin. In fact, they are extremely close to falling into third place.
- The charter school numbers were affected as well. Once again, it was barely enough to even notice. In fact, when it is rounded, the numbers appear to have not changed at all.
- The medium school numbers followed the same path as everything else. The numbers were affected but barely enough for anyone to notice.
### Things that remained the same
- The budget remained the same for the schools. The kids may have had their scores eliminated but they still count as a body that the school has to spend on.
- The total counts of the school remained the same. The students still attend.
- The school type never changed.
1 So the numbers involving those things will usually remain the same throughout the analysis.