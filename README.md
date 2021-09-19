# School_District_Analysis
Module 4 analysis using Anaconda, JupyterLab/Notebook, PANDAS

## Overview of the school district analysis

In this challenge we’re helping Maria analyze the math and reading scores of 15 high schools. Using the NumPy and Pandas libraries in Jupyter Lab, we produced a summary of test metrics based on the various schools’ budget per student, school size, school type, and the students’ grades. The analysis removed the math and reading scores from all 9th graders from Thomas High School due to suspicions of academic dishonesty.

## Results:

*How is the district summary affected?*

The only change to the district summary is that the average math scores dropped from 79.0 to 78.9.

Here is the District Summary after removing the 9th grade scores from Thomas High School:
![District_Summary_Challenge](https://raw.githubusercontent.com/mdwilliams11/School_District_Analysis/main/Resources/District_Summary_Challenge.png)

Here is the original district summary from the module 4 exercises:
![District_Summary_Challenge](https://raw.githubusercontent.com/mdwilliams11/School_District_Analysis/main/Resources/District_Summary_Module_4_Original.png)


*How is the school summary affected?*

All of the schools other than Thomas High School are unaffected by the omission of the Thomas High School 9th graders. The 
 
Here is the school summary after removing the 9th grade scores from Thomas High School:  
![District_Summary_Challenge](https://raw.githubusercontent.com/mdwilliams11/School_District_Analysis/main/Resources/School_Summary_Challenge.png)

Here is the original school summary from the module 4 exercises:
![District_Summary_Challenge](https://raw.githubusercontent.com/mdwilliams11/School_District_Analysis/main/Resources/School_Summary_Module_4_Original.png)

*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?*

The Thomas High School overall passing percentage dropped from 90.95% to 90.63%. Removing the 9th grade math and reading scores does not affect Thomas High School’s ranking as the 2nd highest performing school.
 
*How does replacing the ninth-grade scores affect the following:*

*Math and reading scores by grade*
	
- All of the math and reading scores for other schools, and for Thomas High School’s 10-12th graders, are unaffected.
		
*Scores by school spending*
	
- The math and reading scores by spending ranges are virtually unchanged.
		
*Scores by school size*
	
- The math and reading scores by spending ranges are virtually unchanged.
		
*Scores by school type*
	
- The changes to Thomas High School, a charter school, barely changed the average math and reading scores for charter schools. The averages for district schools remain unchanged.

## Summary:

- The average math score for Medium-sized schools drops from 83.37 to 83.36

- The average reading score for medium-sized schools rises from 83.86 to 83.87.

- The average math scores for charter schools fell from 83.474 to 83.465

- The average reading scores for charter schools rose from 83.896 to 83.902.

These changes are extremely miniscule and suggest the omitted Thomas High School 9th grade scores were largely in line with the overall averages.


