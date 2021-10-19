# Module 4: School District Analysis

## Overview of Project
The school board noticed that there may be academic dishonesty in the Thomas High School ninth grade student's grades. They want to redo the School district analysis without that data and report any changes from original analysis.

### Purpose 
The purpose of this challenge is to replace 9th grade student data with NaN and then redo the analysis of the school district data.

## Results
### District Summary
#### Updated data
![District Summary](Resources/Challenge_Pics/DistrictSummary.jpg)
#### Previous data
![District Summary2](Resources/prior_pics/district_summary.jpg)

The updated district summary above shows that the average reading score was unchanged by removing the 9th grade scores from Thomas High School (THS) however the other scores decreased by about .1

### School Summary
#### Updated Data
![school summary](Resources/Challenge_Pics/school_summary.jpg)
#### Previous Data
![school summary](Resources/prior_pics/perschoolSummary.jpg)

The updated school summary is all the same except for Thomas High school. The average Math score, % passing math % passing reading and % overall passing all decreased by a small amount, while the average reading score increased by an even smaller amount.


### Top 5 performing schools based on overall passing rate
#### Updated Data
![top5](https://github.com/Melberoni/School_District_Analysis/blob/f61221412e4babbcb3b26d1dd67c6bbfee095a5d/Resources/Challenge_Pics/top5schools.jpg)

#### Previous Data
![top 5 prior](Resources/prior_pics/top5schools.jpg)

The top 5 school order has not changed even though the overall passing rate of Thomas High School decreased by .3%

### Bottom 5 performing schools based on overall passing rate
#### Updated Data
![bottom5](Resources/Challenge_Pics/Bottom5schools.jpg)

#### Previous Data
![bottom5 prior](Resources/prior_pics/bottom_5schools.jpg)

The bottom 5 schools did not change

### Average math score for each grade level for each school
![math scores by grade](Resources/Challenge_Pics/mathScoresbyGrade.jpg)

### Average reading score for each grade level for each school
![reading scores by grade](Resources/Challenge_Pics/readingScoresbyGrade.jpg)

The average reading and math scores by grade did not change except for NaNs being inserted in the 9th grade column of Thomas High School

### Scores by school spending by student
![scores by spending](Resources/Challenge_Pics/scoresbyspending.jpg)
### Scores by school size
![scores by school size](Resources/Challenge_Pics/scoresbysize.jpg)
### Scores by school type
![scores by school type](Resources/Challenge_Pics/scoresbytype.jpg)


The scores by school spending, by school size and school type did not change with the removal of the 9th grade scores from Thomas High School


## Summary
After removing the math and reading scores for the 9th graders in Thomas High School, the average grades for the school changed by a small amount and it changed the district summary averages by a very small amount. This change was not large enough to affect the spot of Thomas high school in the top 5 schools and it didn’t change the overall scores by school size, type, or spending.


