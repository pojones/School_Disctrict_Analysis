# School_Disctrict_Analysis

## Overview of the school district analysis:
After an initial analysis of students' scores across the district, the results of the ninth grade class at Thomas High School
were called into question. Because academic dishonesty can skew our results by a significant amount, an additional analysis was
performed with Thomas' ninth grade score results omitted. All else held equal, calculating for the same metrics in the second
analysis allows for an easy comparison. 

## Results:
The following is a list of metrics that are of interest:

### What changed:
For the District:
- Average Math Score dropped by .1
- Percentage Passing Math dropped by .2%
- Percentage Passing Reading dropped by .3%
For Thomas High School:
- Average Math Score dropped by .07
- Average Reading Score raised by .05
- Percentage Passing Math dropped by .08%
- Percentage Passing Reading dropped by .29%
- Overall Passing Percentage dropped by .32%

### What remained unchanged:
For the District:
- Average Scores or Percentage Passing by Spending Range
- Average Scores or Percentage Passing by School Size

## Summary:
To determine if our results are statistically significant, we have to consider the scale of things. The district results show
the most variance. A tenth of a percent seems like a very small difference, until realizing that the dataset has almost forty
thousand entries. <br />
A quick sidenote here; suppose there is a group of a hundred people taking an exam. The average score of the exam for the
first ninety-nine people turns out to be 83.35. For the last person to raise the average score of the exam by just 0.1% to
83.45, she would have to score ten percent higher. <br /> 
Let's apply our school data to this model: one out of a hundred students in a district of 39,170 yields 391 students. Meaning
that roughly 391 students would have had to score about ten percent higher than was expected. Or that 195 students scored 
twenty percent higher than was expected. Since the ninth grade class in question is comprised of 461 students, even reasonably
conservative estimates would suggest some evidence to academic dishonesty. <br />
Conversely, the data for Thomas High School is much less distinct. The average math score is certainly lower in the second
analysis but reading scores actually improved between the two. Furthermore, the percentage of students who passing reading
dropped, despite the average score being better than when the potentially corrupt data was included. It is possible that
whatever academic dishonesty was taking place got more students to pass but did not necessarily improve overall scores. 
Either way, the drop in average math scores for Thomas High School agree with the district data. Using our one in one hundred
model from before, we see that it would take roughly 115 students scoring 10% higher than expected to make that much of a 
difference. While the reading scores might be less subject to academic dishonesty, the discrepencies in math scores may lead
some school officials to do further investigation. <br />
One last observation: the average scores and percentage passing based on spending range did not have any significant change. 
That is to say that there was no significant increase and more importantly, there was no significant decrease. This would 
indicate that per dollar spent by an institution, a dishonest student neither gains nor lose. That is to say that cheating 
doesn't pay off... but there is the chance it doesn't cost anything, either. 
