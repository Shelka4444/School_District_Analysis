# School District Analysis

## Overview of the school district analysis:
The purpose of this project was to examine 15 different high school math and reading scores based on a variety of metrics (schools size, spending per student, school type, etc.). Due to academic dishonesty, grades were omitted in the data set at the 9th grade level from Thomas High School. These findings were presented to the school board committee who will then decided how to allocate funds for the following academic year.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
<img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/district%20summary.png" alt="District Summary">
The school district summary was not significantly affected by the removal of 461 9th grade Thomas High School student grades out of 39,170 total students in the data set. The Average Math Score was 78.9, a 0.1 decrease from the prior summary. The Average Reading Score (81.9), % Passing Math (74.8%), % Passing Reading (85.7%), and % Overall Passing (64.9%) categories stayed constistent across all asssessments.

<br /> <img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/per%20school%20summary.png" alt="School Summary">
The school summary displays each school in the district with metrics for type, student count, school budget, per student budget, average math scores, average reading scores, students passing math percentage, students passing reading percentage , overall passing percentage, and overall category of spending range per student. 

<br /> <img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/per%20school%20summary.png" alt="THS School Summary">
The removal of 9th grade information only affected Thomas High School's row: Average Math Scores decreased by 0.07, Average Reading Scores increased by 0.04, % Passing Math decreased by 0.08%, % Passing Reading by decreased by 0.29%, and % Overall Passing decreased by 0.32%.

<br /> Math Scores           |  Reading Scores
:-------------------------:|:-------------------------:
![Math Scores](https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/average%20math%20by%20grade.png)|![Reading Scores](https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/average%20reading%20by%20grade.png)

These two tables display math and reading scores per grade for each school in the district. The removal of 9th grade students from Thomas High School is shown with NaN added to where the original scores were supposed to be stored.

<br /> <img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/top%20schools.png" alt="THS summary">
Even with the removal of grades for 9th grade students at Thomas High School, Thomas High School still remains the second best school in the district with respect to the percentage of students passing both math and reading.

<br /> <img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/spending%20ranges.png"  alt="Spending Ranges">
Interestingly, the information for the summary of Spending Ranges (Per Students) indicates a negative correlation between spending ranges and resulting student scores. For example, in the % Overall Passing column, schools spending <$584 have a 90% passing rate, $585-$629 have a 81% passing rate, $630-644 have a 56% passing rate, and $645-675 have 54% passing rate. This trend is visible across average math scores, average reading scores, % passing math, and % passing reading.

<br /> <img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/school%20size.png"  alt="School Size">
School size appears to affect average scores and passing rates. Small schools (<1000 students) have an overall passing percentage of 90%, medium schools (1000 - 2000 students) have an overall passing percentage of 91%, and large schools (2000 - 5000 students) have the lowest overall passing percentage at 51%. 

<br /> <img src="https://github.com/Shelka4444/School_District_Analysis/blob/main/Resources/Images/school%20type.png"  alt="School Type">
It is evident from the data displayed in the table above that Charter schools fare significantly better overall than do District schools. Charter schools have higher scores in math and reading, and high overall passing rates (90%), compared to District schools which only have an overall passing rate of 54%.

## Summary:
Out of the 39,170 students recorded in this school district, 461 students were removed from the analysis from Thomas High School's 9th grade class due to academic dishonesty. The removal of 9th grade information only affected Thomas High School's individual school summary and the deleted scores were replaced with NaNs to keep the overall integrity of the data in tact. The updated school district analysis was insignificantly affected by the deletion of this one group of student grades. With the removal of the tampered scores, Thomas High School's Average Math Scores decreased by 0.07, Average Reading Scores increased by 0.04, % Passing Math decreased by 0.08%, % Passing Reading by decreased by 0.29%, and % Overall Passing decreased by 0.32%.
