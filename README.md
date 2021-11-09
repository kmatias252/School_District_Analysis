# School_District_Analysis

## Overview of the school district analysis:

The purpose of this analysis is to  provide evidence of academic dishonesty in the reading and math scores for ninth graders in Thomas High School. To uphold the state-testing standards, we will be replacing the math and reading scores for Thomas High School with NaNs. Lastly, we will rerun our analysis to see if there were any changes in the output for our key metrics that would affect our overall analysis. 

## Results:

### District Summary

1) The difference between the district summary output before and after replacing the ninth grade math and reading scores was very minimal. The % Passing Math was 0.2% lower in the clean student data vs the original district summary. The % Passing Reading was 0.1% lower in the clean student data vs the original district summary. Lastly, the % Overall Passing was 0.3% lower in the clean student data vs the original district summary. Given that all variances are less than 1% it proves that the clean student data did not have a large effect on the overall outcome.  

Below is a screenshot of our original district summary: 
![Screen Shot 2021-11-08 at 8 37 52 PM](https://user-images.githubusercontent.com/91925639/140845818-2d691875-4d64-495c-95be-ddbe780b78c4.png)

Below is a screenshot of our district summary with the clean student data: 
![Screen Shot 2021-11-08 at 8 58 11 PM](https://user-images.githubusercontent.com/91925639/140847726-cf843baa-16ae-4f32-8ea3-687bbfda8cbc.png)

### School Summary

2) Similarly to the district summary, the school summary overall had minimal differences in output. All metrics remained the same for all school except Thomas High School. The follow are a list of metrics and the changes for Thomas High School between the original school summary and the school summary with the clean student data. 
    * Average Math Score - Thomas High School decreased by 0.06 from the original school summary.
    * Average Reading Score - Thomas High School decreased by 0.05 from the original school summary.
    * % Passing Math - Thomas High School decreased by 0.08% from the original school summary.
    * % Passing Reading - Thomas High School by 0.29% from the original school summary.
    * % Overall Passing - Thomas High School by 0.32% from the original school summary.    

Below is a screenshot of our original school summary:
![Screen Shot 2021-11-08 at 9 21 22 PM](https://user-images.githubusercontent.com/91925639/140850014-6f9c1050-4375-469e-bb8e-b5f8af82b214.png)

Below is a screenshot of our school summary with the clean student data:
![Screen Shot 2021-11-08 at 9 22 50 PM](https://user-images.githubusercontent.com/91925639/140850171-b0a0c1d5-724c-42a6-88cd-dd612cbd372a.png)

### Spending Ranges (Per Student) Summary

3) The average reading scores, math scores and % passing by spending ranges per student were uneffected by the changes to the nineth grade student data for Thomas High School. Overall, students that had the lowest spending range (<$584) had higher scores and an overall higher % passing rate of 90%.

Below is a screenshot of our original spending ranges per student summary:
<img width="608" alt="Screen Shot 2021-11-08 at 10 46 33 PM" src="https://user-images.githubusercontent.com/91925639/140858433-42da5567-f05a-41a3-81d1-6b922472fe0c.png">

Below is a screenshot of our spending ranges per student summary with the clean student data:
![Screen Shot 2021-11-09 at 6 55 47 AM](https://user-images.githubusercontent.com/91925639/140919939-c336cf6f-da7c-4f02-bc5a-0e4cf0570088.png)

### School Size Summary

4) The average reading scores, math scores and % passing by school size was uneffected by the changes to the nineth grade student data for Thomas High School. Generally, the small and medium schools had higher scores than large schools. Medium schools had the overall highest passing rate of 91% passing.

Below is a screenshot of our original school size summary:
![Screen Shot 2021-11-09 at 7 05 53 AM](https://user-images.githubusercontent.com/91925639/140921469-8029687c-0bc3-4516-9978-362b0e3d7bf8.png)

Below is a screenshot of our school size summary with the clean student data:
![Screen Shot 2021-11-09 at 7 10 43 AM](https://user-images.githubusercontent.com/91925639/140922001-4d20a853-60f0-4104-a331-a06491b41a10.png)

### School Type Summary:

5) The average reading scores, math scores and % passing by school type was uneffected by the changes to the nineth grade student data for Thomas High School. Charter schools had overall higher scores than district schools and had a overall % passing of 90% vs district schools of 54%.

Below is a screenshot of our original school type summary:
![Screen Shot 2021-11-09 at 7 17 11 AM](https://user-images.githubusercontent.com/91925639/140922921-16e1255e-39e8-4138-a1ed-ca79394fe7d8.png)

Below is a screenshot of our school type summary with the clean student data:
![Screen Shot 2021-11-09 at 7 19 16 AM](https://user-images.githubusercontent.com/91925639/140923101-4074bf41-e3eb-4300-ac3e-6dd5c1c7f817.png)

## Summary:
