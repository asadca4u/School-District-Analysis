# School District Analysis

## Overview of the school district analysis
### A district school board has asked us to run the following set of analyses on data collected from 15 schools in the district
1. An overall summary of the district, including the budget of its 15 schools, the total amount of students, their average reading and math scores, as well as the proportion that are passing reading and math as well as both overall. 
2. The analysis in step 1 is to be separated based on each school.
3. This analysis is to be used to determine the top 5 performing schools, as well as the bottom 5 performing schools.
4. The data is to be further sectioned off by grade for each school, in order to determine the average math and reading score by grade at each school.
5. Next, the schools are to be sectioned off into ranges based on their average spending per student, as well as the size of the school, in order to determine how student body size and avrage spending per student affect the average scores for math and reading. 
6. Finally, the schools are sectioned off into District or Charter schools in order to determine if the type of school and all that it entails, has any meaningful effect on average math and reading scores. 

## Results
### How is the district summary affected?
- Originally, the school district had an average math score of 79.0%, this dropped to 78.9% once the scores from the ninth grade at Thomas High School were removed.
- The average reading score remained unaffected by the removal of the questionable data from Thomas High School, remaining at 81.9% through the whole district. 
- There was a drop in the percentage of students passing math, reading as well as both combined, with the minimum passing grade being 70%. 
  - The proportion of students passing math with a minimum grade of 70% throughout the district dropped from 75% to 74%. 
  - The proportion of students passing reading througout the district dropped from 86% to 85%. 
  - The proportion of students passing both math and reading throughout the district dropped form 65% to 64%. 
  
![district summary_OG](https://github.com/asadca4u/School-District-Analysis/blob/master/resources/readme%20images_all/District%20Summary_OG.png)
###### (Summary of the District)

![district summary_Challenge](https://github.com/asadca4u/School-District-Analysis/blob/master/resources/readme%20images_all/District%20Summary_Challenge.png)
###### (Summary of the District after removing the data from the ninth grade at Thomas High School)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? How is the school summary affected overall?
- Since only the data for Thomas High School was altered, it will be the only one affected, hence the last 5 schools by alphabetical order are shown in the images below.
- The average math score among the whole school dropped slightly from 83.42% to 83.35%.
- The average reading score among the whole school went up slightly from 83.84% to 83.90%.
- The proportion of students passing math, reading and both combined with a minimum score of 70% dropped by approximately 25% across the board.
  - This was due to the data from each of the ninth graders being considered a fail, since there was a discrepency which invalidates the data. 
  - This data could alternatively be removed from the calculation altogether, giving a proportion of students passing math, reading and both combined as if those scores had never      been submitted. 

![School Summary_OG](https://github.com/asadca4u/School-District-Analysis/blob/master/resources/readme%20images_all/School%20Summary_OG2.0.png)
###### (Summary of Each School)
![School Summary_Challenge](https://github.com/asadca4u/School-District-Analysis/blob/master/resources/readme%20images_all/School%20Summary_Challenge2.0.png)
###### (Summary of Each School after removing data from the ninth grade at Thomas High School)


### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?



### How does replacing the ninth-grade scores affect the following:
##### Math and reading scores by grade
##### Scores by school spending
##### Scores by school size
##### Scores by school type



# Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
