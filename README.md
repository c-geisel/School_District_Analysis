# School_District_Analysis

## Overview of the school district analysis: 
This analysis was conducted to analyze all stadardized test data to inform and help create decisions on the district level based on trends found. These decisions will help better inform budget allotments for future years based on the scores by school spending per student, by school size, and by school type. However, it has been found that 9th grade students at Thomas High School show evidence of academic dishonesty in their math and reading scores. Because of this we want to replace the 9th grader's scores at this school with Nan and then repeat the initial analysis with the trace of academic dishonesty removed from our dataframe. 

## Results: 
- Using bulleted lists and images of DataFrames as support, address the following questions.
  - How is the district summary affected?

After removing the 9th grade student scores, the means of the math and reading score columns are recalculated. It can be seen that the average math score decreased by 0.1% in the new district summary and the average reading score stayed the same. The percent passing columns in the datafram changed as well. The percent passing math decrease by 0.2%, the percent passing reading decreased by 0.3% and the percent passing overall decreased by 0.1%
INSERT PHOTOS

  - How is the school summary affected?

The school summary dataframe is mostly unchanged by the removal of 9th graders from thomas high schools score however the data from thomas high school was slighly altered. Avergae math scores went from 83.41% to 83.35%. Average reading scores increased from 83.84% to 83.89%. The Passing math score decrease from 93.27% to 93.18%. The passing reading percentage decreased from 97.3% to 97.01%. Finally, the overall passing percentage went from 90.95% to 90.63%.
INSERT PHOTOS

  - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing ninth grader's math and reading scores doesn't have much of a difference in Thomas High School's performance relative to other schools. Initially, Thomas High School was the second best school in the district based on the overall passing percentage. After removing 9th grade scores they remained stayed at the second best position. They did slightly differ upon removal of scores such as the percent passing math, reading, and overall decreasing by less than a percent but other than this they remained in their position relative to other schools. School population size seems to have a much larger effect on the school performance as opposed to their passing percentage. 
INSERT TOP PERFORMING SCHOOLS IMAGE


  - How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade



  - Scores by school spending
  - Scores by school size
  - Scores by school type

## Summary: 
- Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
