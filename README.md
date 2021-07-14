# School_District_Analysis

## Overview of Project: School district analysis

This proyect has the main object to analyze from different perspectives the relationship and behavior between all the variables tha we have in our database to detect some kind of patterns from this variables that affect or not the students performace.

![School Analysis](https://3k7by215ywuf340yi3alsfso-wpengine.netdna-ssl.com/wp-content/uploads/sites/5/2019/06/FB-People-Climbing-Books-Busines-260968798_1_640_367_c1_c_c.jpg)

## Analysis of the results

Through all this analysis between the original data and the final analysis with the modified database we can notice certain changes in the final results that we can answer in the following questions

- How is the district summary affected?

We can see that the resulting values change but not in a meaningful way, this is because we are calculating the idicators for the performances for all the district schools, thats why this change is not to significat, but we can se a small change in our final district summary

    - District Summary 

        -Original

![Original District Summary](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Original_District_Summary.JPG)

        -Modified with NaNs DataFrame

![Modified District Summary](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Modified_District_Summary.JPG)

- How is the school summary affected?

In this summary we can see the different only in the Thomas Higth School row, because of this the change is little more visible, because we can see that average math and reading score is little bigger that the original school summary, this as a result that we´re not considering the 9th grade students in total students count for that specific school.

    - Original

 ![Original School Summary](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Original_School_Summary.JPG)

    - Modified considering the 10th and 12th grade for Thomas Higt School

![Modified District Summary](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Modified_School_Summary.JPG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The diferent between the first analysis and after the changes of ninth graders’ students isn't to noticeable in the big picture considering all the grades in that school, because of that the different is not to significat if we compare the result against the others students performace in each school.

- How does replacing the ninth-grade scores affect the following:

    - Math and reading scores by grade

    We can see in the next too tables that the change of not consider the performance of the student of ninth grade from Thomas Higth School is affecting the result since we can see a nan value in both Math and Reading average:

     - The average math score for each grade level from each school 
    
    ![average math per level](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/AverageMath_PerGrade.JPG)

    - The average reading score for each grade level from each school 

    ![average reading per level](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/AverageReading_PerGrade.JPG)


    - Scores by school spending

    This scores by school spending were not affected by not considering the ninth grade students from Thomas Higth School since the spending its independence from this specific data that we modified.

    ![speanding per student](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Score_spending%20per%20student.JPG)

    - Scores by school size

    This scores by school size didn't transform regret the change in the number of students that we made in the total number of students in Thomas Higth School, as we can see the score of Thomas Higth School remains Medium (1000-2000), this because the total number of student on that grade and that school was 461, but despite this we can see the change in the school performace in the average math and reading, the percentaje of passing math and reading and overall passign:

    - General view summary

    ![scores school size](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Score_school%20size.JPG)

    - Summary per school

    ![scores school type](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Score_school%20type.JPG)

    - Scores by school type

        This scores by school by type they were not affected by not considering the ninth grade students from Thomas Higth School since the school type its independence from this specific data that we modified, but despite this we can see the change in the school performace in the average math and reading, the percentaje of passing math and reading and overall passign:

    ![scores school type]()



## Summary: 

Some of the changes that we can se in the updated school anlysis is that the performance of the Thomas Hight School change since we change the math and reading scores for the ninth grade:

    - The average reading score gets better after the change in consecuense the percentaje of passing reading gets better too, this could mean that the score that the ninth grade students they weren't the best and not consider them improve performance

    - The average math score gets worse after the change in consecuense the percentaje of passing reading gets worse too, this could mean that the score that the ninth grade students they was good and not consider them got worse the performance.

    -In the big picture we can see much different in the district summary since we´re consider a global view of the distric and not the particular performance of each school

    -In regard of the score by school type, school size and school spending we can see a diferent relating to the bins that we assign in order that the change that we did it is not directly affecting this.

- Complete School DataFrame with NaNs in 9th grade students in Thomas High School

![NaNs DataFrame](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/Complete_DataFrame_NaNs.JPG)


- The top 5 performing schools, based on the overall passing rate

![Top 5 performing](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/top%205%20performing%20schools.JPG)

- The bottom 5 performing schools, based on the overall passing rate

![bottom 5 performing](https://github.com/alesandelmoral/School_District_Analysis/blob/main/Resources/bottom%205%20performing%20schools.JPG)





