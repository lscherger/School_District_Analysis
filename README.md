# School_District_Analysis

## Overview of Project

### Background
Maria, a member of the PyCitySchools district board, requested an analysis of the district's math and reading scores this year with the help of Python in Jupyter Notebooks. The deliverables for this project included an analysis of scores based on several factors including school, school spending per student, school size, school type and grade level. Additionally, due to evidence of academic dishonesty of 9th graders at Thomas High School, the script needed to re-run the audit with those scores removed to compare the score summaries. 

### Purpose
As an introduction to Jupyter Notebook, the purpose of this project was to utilize Pandas DataFrames with Python to complete the analysis. Since the script needed to be refactored, it gave extra opportunity to practice using Pandas DataFrames, such as loc, merge and groupby, to wrangle data. 


## Results
The results of this analysis include charts produced before and after changing the 9th grade scores at Thomas High School to NaNs due to evidence of academic dishonesty. For each metric, there will be an original summary and a refactored summary, which are labeled. 

* **District Summary:**
  - Here, the refactored district summary shows a slight decrease in average math scores (-0.1 pt) after the 9th grade scores from Thomas High School were changed to NaNs. Due to the large district size, 39,170 students, a change of 461 scores (~1% of the  total score count) did not drastically affect the district results. 

  - **Original District Summary:**
  - <img width="772" alt="Screen Shot 2021-07-15 at 12 54 24 AM" src="https://user-images.githubusercontent.com/85946042/125736512-12519127-aec6-4d95-aa0a-4f4a8766dc04.png">
  - **Refactored District Summary:**
  - <img width="768" alt="Screen Shot 2021-07-15 at 2 24 52 PM" src="https://user-images.githubusercontent.com/85946042/125845839-ed2ca29c-7f0b-4132-a97c-bb33fc091105.png">

* **School Summary:**
  - After replacing the grades, the Thomas High School summary changed slightly at the hundreths place for each metric. There are decreases in the following metrics: % overall passing changed from 90.95% to 90.63%, the % passing reading changed from 97.31% to 97.02%, % passing math changed from 93.27% to 93.19% and math scores changes from 83.42% to 83.35%. Reading scores increased from 83.85% to 83.90%. The changes here are minimal since the majority of scores came from students in grades 10 through 12. Still, the small decreases reflect that the 9th graders' scores were slightly higher. 
  - Original School Summary:
  - <img width="830" alt="Screen Shot 2021-07-15 at 1 52 48 PM" src="https://user-images.githubusercontent.com/85946042/125842070-67ed7016-3599-4347-aa6d-cae738593017.png">


  - Refactored School Summary: 
  - <img width="829" alt="Screen Shot 2021-07-15 at 1 54 46 PM" src="https://user-images.githubusercontent.com/85946042/125842086-525ce6a9-9151-4359-8c30-70ec0a9bd749.png">


* **Thomas High School's Performance Relative to the Other Schools:**
  - Before replacing the ninth graders' math and reading scores, Thomas High School ranked 2nd out of 14. After replacing the scores with NaNs, Thomas High School still ranked 2nd out of 14 after Cabrera High School. 
  - **Original Rankings Based on % Overall Passing:**
  - <img width="830" alt="Screen Shot 2021-07-15 at 1 52 48 PM" src="https://user-images.githubusercontent.com/85946042/125842070-67ed7016-3599-4347-aa6d-cae738593017.png">


  - **Refactored Rankings Based on % Overall Passing:**
  - <img width="829" alt="Screen Shot 2021-07-15 at 1 54 46 PM" src="https://user-images.githubusercontent.com/85946042/125842086-525ce6a9-9151-4359-8c30-70ec0a9bd749.png">


* **Math and Reading Scores by Grade:**
  - Only the 9th grade scores at Thomas High School are affected by the replacement, as those are the scores that are getting replaced. The 10th-12th grade scores at Thomas High School and all other scores at other high schoools are not affected. The average of the district's 9th grade scores changes from 78.94 to 78.74 for math and from 81.91 to 81.84 for reading when the scores from Thomas High School are replaced. 

  - **Original Math and Reading Scores (Math on the left):**
  - <img width="248" alt="Screen Shot 2021-07-15 at 1 59 42 PM" src="https://user-images.githubusercontent.com/85946042/125842661-7577a8d9-28fd-4509-86de-fd94fe4e3faa.png"> <img width="243" alt="Screen Shot 2021-07-15 at 1 59 48 PM" src="https://user-images.githubusercontent.com/85946042/125842673-eaee034d-6e9e-4c5e-9f43-f7eff0dc3e95.png">
  - <img width="282" alt="Screen Shot 2021-07-15 at 2 59 06 PM" src="https://user-images.githubusercontent.com/85946042/125849954-27806ee2-07de-4585-879e-f9cbdc6f481f.png">

 
  - **Refactored Math Reading Scores (Math on the left:**
  - <img width="245" alt="Screen Shot 2021-07-15 at 1 58 07 PM" src="https://user-images.githubusercontent.com/85946042/125842412-fd4bff48-adff-4a37-abb0-ec50c2088311.png"> <img width="246" alt="Screen Shot 2021-07-15 at 1 58 02 PM" src="https://user-images.githubusercontent.com/85946042/125842429-912c6241-197b-4803-bfb3-e8a0d61a3f7c.png">
  - <img width="326" alt="Screen Shot 2021-07-15 at 3 02 45 PM" src="https://user-images.githubusercontent.com/85946042/125850319-46c65a44-827d-4e5d-8e97-a4687406ae66.png">


* **Scores by School Spending:**
  - There is no noticeable difference in the scores by school spending before and after grades were replaced for 9th graders at Thomas High School. The scores are equal to the tenth place for average scores and ones place for passing percentages.
  -  In both cases, there is a negative trend between school spending per student and % overall passing; as average spending per student increases, average % overall passing tends to decrease. 
  
  - **Original Scores by School Spending:**
  - <img width="681" alt="Screen Shot 2021-07-15 at 2 00 45 PM" src="https://user-images.githubusercontent.com/85946042/125842891-2f773065-691b-41f6-9e92-4a01bcfd89fe.png">

  - **Refactored Scores by School Spending:**
  - <img width="680" alt="Screen Shot 2021-07-15 at 2 03 21 PM" src="https://user-images.githubusercontent.com/85946042/125843335-a0e07823-71ec-4a23-be31-968e1576d377.png">


* **Scores by School Size:**
  - There is no noticeable difference in the scores by school size before and after grades were replaced for 9th graders at Thomas High School. The scores are equal to the tenth place for average scores and ones place for passing percentages. 
  - In both summaries, small and medium sized schools have comparable % overall passing (90% passing for small schools, 91% passing for medium schools), while large schools have a lower % overall passing rate (58% passing), on average. 

  - **Original Scores by School Size:**
  - <img width="630" alt="Screen Shot 2021-07-15 at 2 00 58 PM" src="https://user-images.githubusercontent.com/85946042/125842931-d24835ce-b4b9-46a4-8ba5-285faa5ab4a8.png">

  - **Refactored Scores by School Size:**
  - <img width="622" alt="Screen Shot 2021-07-15 at 2 03 38 PM" src="https://user-images.githubusercontent.com/85946042/125843364-0de9ccfc-542b-4854-bd66-f79c5aa9436f.png">


* **Scores by School Type:**
  - There is no noticeable difference in the scores by school type before and after grades were replaced for 9th graders at Thomas High School. The scores are equal to the tenth place for average scores and ones place for passing percentages. 
  - In both summaries, charter schools have a 90% average overall passing rate, compared to district schools, which average a 54% overall passing rate. 
  
  - **Original Scores by School Type:**
  -  <img width="588" alt="Screen Shot 2021-07-15 at 2 01 24 PM" src="https://user-images.githubusercontent.com/85946042/125842933-f7897de0-f62b-45a8-9408-c745af7e07b7.png">
  - **Refactored Scores by School Type:**
  - <img width="589" alt="Screen Shot 2021-07-15 at 2 03 50 PM" src="https://user-images.githubusercontent.com/85946042/125843380-1578e627-12ec-4f0f-bcb1-f0aba8725973.png">


## Summary
After re-conducting the school district analysis after replacing the 9th graders' scores at Thomas High School, there are a few differences in the updated results compared to the original results. At the highest level, there was a 0.1 point decrease in the average math score for the district. Since only 461 scores out of 39,170 were replaced, for the average score to change by a tenth is still significant. Next, the Thomas High School summary average math score changed from 83.42 to 83.35 when the scores were replaced. Additionally, the % Overall Passing for Thomas High School changed from 90.95% to 90.63%. While there is only a 0.32% change, this is the metric that school ranking is based on, so small changes can affect school performance. Finally, the average of the district's 9th grade scores changed from 78.94 to 78.74 for math and from 81.91 to 81.84 for reading when the scores from 9th graders at Thomas High School were replaced. Though these changes are small, it was important to perform the re-run to visualize the extent that academic dishonesty affected school and district summaries. 



