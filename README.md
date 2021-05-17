# School_District_Analysis

# Overview of the school district analysis: Explain the purpose of this analysis.

The purpose is to perform a school district analysis of 15 high schools comparing math and reading scores with relation to spending per student, school size, and school type (charter or district).  However in this case the school board noticed that the data they received shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders. With that being said I will perform the analysis by replacing the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.

How is the district summary affected?

With the exclusion of the 9th graders at Thomas High School the average math score dropped from 79.0 to 78.9.

![image](https://user-images.githubusercontent.com/80642682/118424214-c6b38180-b694-11eb-9678-ccf88ced78d0.png)

![image](https://user-images.githubusercontent.com/80642682/118424766-cf588780-b695-11eb-861e-eee4439a3719.png)


How is the school summary affected?

The school summary has been affcted due to exclusion of the 9th grader scores from Thomas High School.  Below the percent passing for math and reading at Thomas High School has dropped significantly.

![image](https://user-images.githubusercontent.com/80642682/118425237-c320fa00-b696-11eb-8791-ba1c2cd76ad4.png)

![image](https://user-images.githubusercontent.com/80642682/118425186-a4226800-b696-11eb-964e-14d66a875076.png)


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders’ math and reading scores did not affect Thomas High School’s performance relative to the other schools.  The 9th graders scores across the other high schools in the images below are similar. 

Math

![image](https://user-images.githubusercontent.com/80642682/118426108-94a41e80-b698-11eb-9966-dc1403e4f2e9.png)

Reading

![image](https://user-images.githubusercontent.com/80642682/118426153-b00f2980-b698-11eb-8bd1-538cbccaee50.png)


How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade

Math

![image](https://user-images.githubusercontent.com/80642682/118426659-a20dd880-b699-11eb-83ea-1246e1536a08.png)

Reading

![image](https://user-images.githubusercontent.com/80642682/118426719-bc47b680-b699-11eb-9727-b49706e0c6dc.png)


Scores by school spending

The scores by school spending had not been affected at all by the replacement of Thomas High School 9th grader's scores, because school budget and per student spending were not dependent on the individual student scores.

![image](https://user-images.githubusercontent.com/80642682/118426839-ffa22500-b699-11eb-9762-ae167e5ea9a8.png)


Scores by school size

Scores by school size remained the same after replacement of Thomas High School 9th grade scores.

Replaced Thomas High School 9th Grade student scores
![image](https://user-images.githubusercontent.com/80642682/118427185-a38bd080-b69a-11eb-8248-aa57adfc9630.png)

Removed Thomas High School 9th Grade student scores
![image](https://user-images.githubusercontent.com/80642682/118427088-6aebf700-b69a-11eb-8478-9678481e0164.png)

Scores by school type

Scores by school type remained the same after replacement of Thomas High School 9th grade scores.

Replaced Thomas High School 9th Grade student scores
![image](https://user-images.githubusercontent.com/80642682/118427505-5b20e280-b69b-11eb-8876-e0acca9e11e4.png)

Removed Thomas High School 9th Grade student scores
![image](https://user-images.githubusercontent.com/80642682/118427524-6d028580-b69b-11eb-9d74-9c8b80090a3f.png)

# Summary

After replacing the Thomas High School ninth graders’ math and reading scores with NaNs, there were a couple of changes in the analysis results on the district and school levels. For the district, by replacing the Thomas High School ninth graders’ math and reading scores with NaN, the “Average Math Score”, “Average Reading Score”, “% Passing Math”, and “% Passing Reading” all dropped slightly causing the “% Overall Passing” for the district as a whole to decrease by 0.1%. When comparing Thomas High School’s performance relative to other schools in the district, while it remained in the same standing, the “% Overall Passing” had decreased by over 0.3%. In the school summary for Thomas High School, the “Average Math Score” and “% Passing Math” decreased by 0.1 points and 0.1% respectively. Significantly, the “Average Reading Score” increased by 0.05 points, but the “% Passing Reading” decreased by 0.3%.
