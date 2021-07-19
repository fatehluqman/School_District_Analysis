# School_District_Analysis

## Overview of the school district analysis: 
Initial analysis of the PyCity School District consisted of:
1. Determining the average Reading and Math scores and the % Passing in each and % Passing Overall by school.
2. Average Reading and Math scores by grade level and grouped by school.
3. Average Reading and Math Scores and % Passing in each and % Passing Overall by school spending.
4. Average Reading and Math Scores and % Passing in each and % Passing Overall by school size.
5. Average Reading and Math Scores and % Passing in each and % Passing Overall by school type.
After it was determined that the 9th grade math and reading scores from Thomas High School (THS) may have been altered, a secondary analysis was required.
The secondary analysis required the replacement of the 9th grade scores from THS and rerunning the initial analysis with the replaced scores. 
Finally, a comparison of the two different analysis of the school district data was completed. 

## Results: 
After the initial analysis was complete, the secondary analysis was completed on the school district data.  This analysis involved initially converting the 9th grade scores for reading and math from THS to NaN. 
We then calculated the averages for reading and math from 10th to 12th grade at THS and used those as replacement for the overall schools reading and math scores. 
Based on the replaced data for THS, the overall impact on the school district numbers was minimal, as detailed below.

* How is the district summary affected?
	* Overall change between the initial analysis and secondary analysis (9th grade scores from THS removed) were minimal. 
	* Average Math Score declined by .1% point while % Passing Math declined by .2% points on the secondary analysis.
	* Average Reading Score remined the same on both analyses, but the % Passing Reading declined by .1% point on the secondary analysis.
	* % Overall Passing declined by .3% points on the secondary analysis. 
 
* How is the school summary affected?
	* Scores and % Passing for THS change very little when compared to the initial analysis. All scores and percentages declined in the secondary analysis by tenths of a percentage to the initial analysis. 

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	* There was no change in THS performance relative to the other high schools.  In the initial analysis THS was the Top 2 ranked high school based on % Overall Passing, this ranking did not change after the secondary analysis. 

* How does replacing the ninth-grade scores affect the following:
	* Scores by school spending:
		* With THS falling into the $630-644 Spending range per student, we see that all scores and percentages remained the same down to the nearest tenth of a percent, for schools in that spending range.
	
	* Scores by school size:
		* THS falls into the medium size school based on the number of students.  Again, we see no change in scores or percentages down to the nearest tenth of a percent for medium size schools.
	
	* Scores by school type:
		* THS is a Charter schools and when comparing the two analysis we see no change in the scores down to the nearest tenth of a percent for Charter schools. 

## Summary: 
The changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs can be summarized as the following:
* THS % Overall Passing declined from 90.9% to 90.6%.	
* THS Average Math Score remained flat at 83.4%. While the % Passing Math declined from 93.3% to 93.2%.
* THS Average Reading Score increased from 83.8% to 83.9%. While the % Passing Reading declined from 97.3% to 97%.
* While removing the scores for the 9th grade THS scores had a slight impact on THS numbers, the impact on the overall PyCity School District was minimal, which would indicate that there was little to no evidence of academic dishonesty.
* Intial Analysis
![Intial Analysis](https://user-images.githubusercontent.com/62673123/126105152-dafe1d56-2d1c-424d-b9cd-0cebd98243ba.PNG)
* Secondary Analysis - with 9th grades sores replaced.
![Secondary Analysis](https://user-images.githubusercontent.com/62673123/126105163-3d792259-47cb-4a84-b7e2-b1e8231afc1f.PNG)

