# School District Analysis

## Overview

The Chief Data Scientist for a city school district has requested assistance in anlayzing the results of student standardized math and reading test scores within the district to analyze performance trends and patterns.  Insights provided from the analysis will be used by school board for school budget and planning.  During the analysis it was discovered that the test scores of for ninth grade students at Thomas High School may have been tampered with.  For the purpose of this analysis the test scores of those students have been excluded from the final reports.

## Results

### District Summary - Key Metrics

![DistrictSummary](/Resources/challenge_district_summary.png)

##### District Summary by School Type

![SchoolType](/Resources/challenge_school_type.png)

##### District Summary by School Size

![SchoolSize](/Resources/challenge_school_size.png)

##### District Summary by per Student Spending

![SpendingRanges](/Resources/challenge_spending_ranges.png)

#### School Ranking
Top 5 Performing Schools:
![TopFive](/Resources/challenge_top_five.png)

Bottom 5 Performing Schools:
![BottomFive](/Resources/challenge_bottom_five.png)

#### Grade Level Performance

Average Math Score | Average Reading Score
-------------------|----------------------
![Math](/Resources/challenge_math_score_by_grade.png) | ![Reading](/Resources/challenge_reading_score_by_grade.png)

Results:  

Replacing the math and reading scores of the Thomas High School ninth graders with NaNs had negligible impact on the district wide averages and did not change the overall school rankings.  The overall passing percentage decreased slightly from 65.2% to 64.9%.  The average math and reading scores and the related passing percentages for Thomas High School changed by less than +/- 0.5% after removing the ninth graders test scores.  A definitive conclusion on the impact of those test scores cannot be made until the scores are validated and added back into the data population. 

