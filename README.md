# PyCity Schools Analysis

The object of this project was it hyperanalyze the coorelation between 15 different highschools to their students academic abilities as well as the average budget for each school. 
We have discovered that as a whole, schools with higher budgets, did not yield better test results. By contrast, schools with higher spending 645-675 per student actually underperformed compared to schools with smaller budgets (585 per student). However, smaller and medium sized schools dramatically out-performed large sized schools on passing math performances (89-91% passing vs 67%).
Charter schools out-performed the public district schools across all metrics. However, more analysis will be required to glean if the effect is due to school practices or the fact that charter schools tend to serve smaller student populations per school.
Within this project we have broken down each analysis between schools, students, scores, and budgets as explained below:
    
    * District Summary
        The following have been calculated in order to obtain the average of all the schools:
            - the total school count
            - the total number of students
            - the total budget
            - the average math score
            - the average reading score
            - passing math/reading %
            - overall passing %
        With all this information, it has been put into a dataframe so all the averages are displayed for the overall 15 schools.
        
    * School Summary
        Now the average has been taken per each school so the viewer can see the statistics for all of them. We have done this by creating the schools as the main index so the information can show for every high school.
        All the following in district summary have been calculated for school summary. Per school budget has also been added per each school.
        
    * Highest Performing Schools
        The data frame created for School Summary has been re-organized so the rows show the highest performing school to the least performing school based off the overall passing %. The top five show the best performing schools.
        
    * Bottom Performing Schools
        The data frame created for School Summary has been re-organized so the rows show the bottom performing school to the best performing school based off the overall passing %. The top five show the worst performing schools.
        
    * Math Scores By Grade
        The math scores has been individually grouped so we can see it for each school organized by grade. The average math score for each grade per school has been calculated and put into a data frame for analysts to see.
   
    * Reading Scores By Grade
        The reading scores has been individually grouped so we can see it for each school organized by grade. The average reading score for each grade per school has been calculated and put into a data frame for analysts to see.
        
    * Scores By School Spending
        Through the binning technique, each school has been put into four categories depending on the price range of spending ranges per student. It has been added to the data frame and each price range has been assigned to a specific school.
    
    * Scores By School Size
        Through the binning technique, each school has been put into four categories depending on the school size for each high school. It has been added to the data frame and each range of student sizes has been assigned to a specific school.        
        
    * Scores By School Type
        The average math and reading scores, as well as their percentages(including overall %) has been calculated and organized by school type. The types being Disctric and Charter. This has been organized and put within a data frame.
        
---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
