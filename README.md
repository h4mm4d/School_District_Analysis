# School_District_Analysis

##overview 
PyCity School District wants to analyze standardized test score for high school in the district and they want to analyze what affects student performance, for example, size of school, funding per student, etc.
In this project data is provided to us is for 39,170 students in 15 high schools from 9th grade to 12th grade for reading and math. 
The goal of this project is to clean data, provide current analysis of student body for grades and funding, and create tables that  summarizes results in meaningful ways. 
###Resources 
Maria, who is chief data scientist of the provided some valuable inputs and Complete school and students data in CSV format. 
Jupyter Notebook 6.3.0 was the main tool used with Pandas 1.2.4, NumPY 1.20 and Python 3.76.   
#### Notes
-	Due to widespread academic dishonesty the math and reading scores for 9th grade of Thomas High School has been nullified and the value for those students are changed to NaN.  
-	For that reason all student data from the schoold 9th grade are not accounted for in this analysis. 
## Current  Analysis 
-	There are 15 schools with 39,170 students 
-	The district spends average of $620 per student 
-	Overall 71% of the students in this district pass both math and reading
-	There are two types of school district and charter.
-	Average student makes about 80% in math and 82.5% in reading
![image](https://user-images.githubusercontent.com/86130579/144741037-05f443d9-76ed-4c7d-990b-58e7d547fefc.png)

## Results
### High and Low Performing Schools
In this task it was discovered that the top five schools are charter schools and bottom five are all district schools. Therefore, it is safe assume that charter schools overall perform better than 
The schools that are in bottom spends more money per students than the ones on top 
![image](https://user-images.githubusercontent.com/86130579/144741083-26084bb0-e4ef-4146-9d76-f0dbd5eab1d1.png)

![image](https://user-images.githubusercontent.com/86130579/144741301-9dd3050e-9005-419f-853d-1d9f83b6ffb2.png)

### Math and Reading Scores by Grade
There seems to be no correlation between math and reading scores by grades. 
Reading Scores Grouped by Grades

![image](https://user-images.githubusercontent.com/86130579/144741094-a9d3f6a8-b3ba-4bd8-b9a3-542ec76dddff.png)

Math Scores Grouped by Grades

![image](https://user-images.githubusercontent.com/86130579/144741137-80f7bdd4-3f41-4d44-924b-770304e3b037.png)


### Scores by School Spending
It seems like there is an inverse correlation between spending per student and passing rates. 
![image](https://user-images.githubusercontent.com/86130579/144741174-9db83ae1-3f88-4174-abf2-579ca5091727.png)

### Scores by School Size
There are no significant difference between grades of a medium sized and small schools. Schools larger that 2000 students are doing poorly compare to others.
![image](https://user-images.githubusercontent.com/86130579/144741314-72aec295-deb0-4de2-8e9d-745b3fa1dde8.png)

## Summary
From this analysis we found out that charter schools do better than district schools. Also, smaller school tens to do better than large ones and spending more money per student does not really mean better performance. 
