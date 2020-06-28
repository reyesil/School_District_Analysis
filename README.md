# School District Analysis

## Project Overview

This project provides insight into the academic performance of high school students on standardized exams across fifteen different schools. Their scores will inform the school board on future funding allocations.

## Resources
- Data source: schools_complete.csv, students_complete.csv
- Software: Python (3.7.6), Jupyter Notebook (6.0.3), Anaconda (4.8.3)

## Summary

After an error was discovered in the data, the data was revised to remove some information from the exam results. The following is a summary of how the changes have impacted the overall analysis.

The original district summary analysis revealed that the average math score was 79.0, the average reading score was 81.9, the percentage of passing math scores was 75%, the percentage of passing reading scores was 86%, and the overall passing percentage was 65%.
<img src="README Images /PyCitySchoolsDistrictSummary.png">

The modified district summary analysis revealed that the average math score changed to 78.9, the average reading score remained the same at 81.9, the percentage of passing math scores changed to 74%, the percentage of passing reading scores changed to 85%, and the overall passing percentage changed to 64%.
<img src="README Images /PyCitySchoolsChallengeDistrictSummary.png">

The original school summary showed that the top five schools, or the five schools with the highest percentage of overall passing scores, were:
1. Cabrera High School (91.3% overall passing score)
2. Thomas High School (90.9% overall passing score)
3. Griffin High School (90.6% overall passing score)
4. Wilson High School (90.6% overall passing score)
5. Pena High School (90.5% overall passing score)

The modified school summary showed that the top five schools were:
1. Cabrera High School (91.3% overall passing score)
2. Griffin High School (90.6% overall passing score)
3. Wilson High School (90.6% overall passing score)
4. Pena High School (90.5% overall passing score)
5. Wright High School (90.3% overall passing score)

Thomas High School was originally the second highest scoring school. After the error was addressed, Thomas High School moved to the eighth highest scoring school.

Omitting the 9th grade reading and writing scores from Thomas High School neither affects the scores of other grades at Thomas High School or the scores of other 9th graders at other schools.

The average reading and math scores do not change after the scores are corrected for Thomas High School. However, there are changes for the spending range of $630-644. The percentage of passing math changes from 73% to 67%, the percentage of passing reading changes from 84% to 77%, and the overall passing percentage changes from 63% to 56%.

### Original spending analysis
<img src="README Images /PyCitySchoolsSpending.png">

### Modified spending analysis
<img src="README Images /PyCitySchoolsChallengeSpending.png">

Changes can be seen in the medium school size (1,000-2,000 students) in the percentage of passing math, reading, and overall. The percentage of passing math scores drops from 94% to 88%, the percentage of passing reading drops from 97% to 91%, and the overall passing percentage drops from 91% to 85%.

### Original school size analysis
<img src="README Images /PyCitySchoolsSize.png">

### Modified school size analysis
<img src="README Images /PyCitySchoolsChallengeSize.png">

The percentages of passing math, reading, and overall change for charter schools. The percentage of passing math drops from 94% to 90%, the percentage of passing reading drops from 97% to 93%, and the overall passing percentage drops from 90% to 87%.
### Original school type analysis
<img src="README Images /PyCitySchoolsType.png">

### Modified school type analysis
<img src="README Images /PyCitySchoolsChallengeType.png">
