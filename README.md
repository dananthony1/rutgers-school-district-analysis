# rutgers-school-district-analysis
Module 4 of Rutgers Data Science Bootcamp. Working with Pandas library in Jupyter Notebooks.

# PyCitySchools

## Overview of Project

### Purpose
	The purpose of the analysis is to recreate metrics from the school district analysis with the replacement 
of 9th grade scores as NaN values.

## Results

- How is the district summary affected?
![District Summary Original](/Resources/01a-District_Summary.png "District Summary Original")
![District Summary Recreated](/Resources/01b-District_Summary.png "District Summary Recreated")	
	
- How is the school summary affected?
![School Summary Original](/Resources/02a-School_Summary.png "School Summary Original")
![School Summary Recreated](/Resources/02b-School_Summary.png "School Summary Recreated")

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance 
relative to the other schools?
	The values for the school dropped from values in the 90% range to the 60% range.

- How does replacing the ninth-grade scores affect the following:

*Math and reading scores by grade:
![Reading Scores By Grade Original](/Resources/03a-Reading_Scores_By_Grade.png "Reading Scores By Grade Original")
![Reading Scores By Grade Recreated](/Resources/03b-Reading_Scores_By_Grade.png "Reading Scores By Grade Recreated")

![Math Scores By Grade Original](/Resources/04a-Math_Scores_By_Grade.png "Math Scores By Grade Original")
![Math Scores By Grade Recreated](/Resources/04b-Math_Scores_By_Grade.png "Math Scores By Grade Recreated")

*Scores by school spending:
![Scores By Spending Original](/Resources/05a-Scores_by_Spending.png "Scores By Spending Original")
![Scores By Spending Recreated](/Resources/05b-Scores_by_Spending.png "Scores By Spending Recreated")

*Scores by school size:
![Scores By Size Original](/Resources/06a-Scores_by_Size.png "Scores By Size Original")
![Scores By Size Recreated](/Resources/06b-Scores_by_Size.png "Scores By Size Recreated")

*Scores by school type:
![Scores By Type Original](/Resources/07a-Scores_by_Type.png "Scores By Type Original")
![Scores By Type Recreated](/Resources/07b-Scores_by_Type.png "Scores By Type Recreated")

## Summary
-Summarize four changes in the updated school district analysis.
1. In the District Summary, the "% Passing Math" dropped by 0.2%, the "% Passing Reading" dropped 0.1%, and
 the "% Overall Passing" dropped 0.3%
2. In the School Summary, the following values changed for Thomas High School: "% Passing Math" dropped to 66.9%, 
the "% Passing Reading" dropped to 69.7%, and the "% Overall Passing" dropped to 65.1%
3. The reading scores and math scores by grade did not change except for the 9th grade values for Thomas High 
School which were replaced by NaN values.
4. The changes to the by spending, size, and type tables were minimal and did not result in changes per the tenth 
decimal place.
