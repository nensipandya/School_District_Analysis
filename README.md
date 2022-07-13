##  School_District_Analysis

### Purpose:
The purpose of the School District Analysis is to find out the overall percentages of the students and find out if there is any correlation with budget per student. The school board has found some academic dishonesty, specifically, reading and math grades for Thomas High School ninth grades. Therefore the school board and supervisor asked us to do analysis and asked us to replace the math and reading scores of Thomas High School and do the school disctrict analsis and find out how these changes affect the overall analysis. 

* **How is the district summary affected?**

  After taking a closer look at the PyCitySchools and PyCitySchools_Challenge_testing, there is barley any change in the result.
 
 Below results was taken **before** we removed the the math and reading scores of Thomas High School 9th grades.
 
  ![image](https://user-images.githubusercontent.com/107137215/178614791-ef016568-7e4a-4d1d-9656-3af403170463.png)
 
 Below results was taken **after** we removed the the math and reading scores of Thomas High School 9th grades.
 
 ![image](https://user-images.githubusercontent.com/107137215/178615053-2d367c8a-bf19-45a4-ad6b-653e4c34540d.png)

* **How is the school summary affected?**
  The over all passing for Thomas High School was 90.94% in pycityschools, with the 9th graders' math and reading of Thomas High School taken out the overall passing 
  shrinks by 0.31 %.

  Below results was taken **before** we removed the the math and reading scores of Thomas High School 9th grades.

   ![image](https://user-images.githubusercontent.com/107137215/178615483-9b511dc0-055c-4de2-942e-1c9724126633.png)
  
  Below results was taken **after** we removed the the math and reading scores of Thomas High School 9th grades.
  
  ![image](https://user-images.githubusercontent.com/107137215/178615569-3541e432-5395-4869-aa96-b5c928e24e5d.png)

* **How does replacing the ninth graders's math and reading score affect Thomas High School's performance relative to the other schools?**
  
  Overall it does not affect to the other schools results, either the reading scores or math scores. We are doing an investigation because we believe they are not 
  including most of the 9th graders  because they might bring the school even further down in test scores.
  
* **How does replacing the ninth-grade score affect the following:
    
    * **Math and reading scores by grade**
        There is no much difference in the math and reading scores in the other school, the only differnce is that the score that under 9th graders who attended from 
        Thomas High School shows as NaN.
    * **Scores by school spending**
        The numbers are exactly identical with and with 9th graders of Thomas High School. 
    * **Scores by school size**
        Overall passing percentage does not affected by replacing 9th graders of Thomas High School results.
    * **Scores by school type**
        Scores by school type are not altered at all.
       
 ### Summary
 
  After we have replaced the scores of the 9th grade students we learn that not much has changed. We have nullified the values that we felt would alter size,district,
  spending and overall passing percentage of the students.



