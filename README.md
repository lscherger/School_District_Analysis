# School_District_Analysis

## Overview of Project

### Background
Maria, a member of the PyCitySchools district board, would like an analysis of the district's math and reading scores this year with the help of Python in Jupyter Notebooks. The deliverables for this project include an analysis of scores based on several factors including school, school spending per student, school size, school type and grade level. Additionally, due to evidence of academic dishonesty of 9th graders at Thomas High School, the script will also re-run the audit with those scores removed to compare the score summaries. 

### Purpose
As an introduction to Jupyter Notebook, the purpose of this project is to utilize Pandas DataFrames with Python to complete the analysis. Since the script needs to be refactored, it gives extra opportunity to practice using Pandas DataFrames, such as loc, merge and groupby, to wrangle data. This project will help to understand the benefits of analyzing large, messy data sets using Pandas DataFrames and Jupyter Notebook. 


## Results
The results of this analysis include charts produced before and after changing the 9th grade scores at Thomas High School to NaNs due to evidence of academic dishonesty. For each metric, there will be an original summary and a refactored summary, which are labeled. 

* District Summary:
  - Here, the refactored district summary shows a slight decrease in math scores (-0.1) , % Passing Math (-0.2%), % Passing Reading (-0.3%)  and % Overall Passing   (-0.1%) after the 9th grade scores from Thomas High School were changed to NaNs. Due to the large district size, 39,170 students, a change of 461 scores (~1% of the  total score count) did not drastically affect the district results. There were decreases, but only to the tenth place at most. 

  - **Original District Summary:**
  - <img width="772" alt="Screen Shot 2021-07-15 at 12 54 24 AM" src="https://user-images.githubusercontent.com/85946042/125736512-12519127-aec6-4d95-aa0a-4f4a8766dc04.png">
  - **Refactored District Summary:**
  - <img width="771" alt="Screen Shot 2021-07-15 at 12 44 39 PM" src="https://user-images.githubusercontent.com/85946042/125833369-a4586f9e-8f39-4429-b20e-e5dfd539fff8.png">



* School Summary:
  - Original School Summary:
  - <img width="830" alt="Screen Shot 2021-07-15 at 1 52 48 PM" src="https://user-images.githubusercontent.com/85946042/125842070-67ed7016-3599-4347-aa6d-cae738593017.png">


  - Refactored School Summary: 
  - <img width="829" alt="Screen Shot 2021-07-15 at 1 54 46 PM" src="https://user-images.githubusercontent.com/85946042/125842086-525ce6a9-9151-4359-8c30-70ec0a9bd749.png">



* Thomas High School's Performance Relative to the Other Schools:
  - Before replacing the ninth graders' math and reading scores, Thomas High School ranked 2nd out of 14. After replacing the scores with NaNs, Thomas High School still ranked 2nd out of 14. 
  - **Original Rankings Based on % Overall Passing:**
  - <img width="830" alt="Screen Shot 2021-07-15 at 1 52 48 PM" src="https://user-images.githubusercontent.com/85946042/125842070-67ed7016-3599-4347-aa6d-cae738593017.png">


  - **Refactored Rankings Based on % Overall Passing:**
  - <img width="829" alt="Screen Shot 2021-07-15 at 1 54 46 PM" src="https://user-images.githubusercontent.com/85946042/125842086-525ce6a9-9151-4359-8c30-70ec0a9bd749.png">



* Math and Reading Scores by Grade:
  - **Original Math and Reading Scores:**
  - <img width="248" alt="Screen Shot 2021-07-15 at 1 59 42 PM" src="https://user-images.githubusercontent.com/85946042/125842661-7577a8d9-28fd-4509-86de-fd94fe4e3faa.png"> <img width="243" alt="Screen Shot 2021-07-15 at 1 59 48 PM" src="https://user-images.githubusercontent.com/85946042/125842673-eaee034d-6e9e-4c5e-9f43-f7eff0dc3e95.png">


 
  - **Refactored Math and Reading Scores:**
  - <img width="245" alt="Screen Shot 2021-07-15 at 1 58 07 PM" src="https://user-images.githubusercontent.com/85946042/125842412-fd4bff48-adff-4a37-abb0-ec50c2088311.png"> <img width="246" alt="Screen Shot 2021-07-15 at 1 58 02 PM" src="https://user-images.githubusercontent.com/85946042/125842429-912c6241-197b-4803-bfb3-e8a0d61a3f7c.png">


* Scores by School Spending:
  - **Original Scores by School Spending:**
  - <img width="681" alt="Screen Shot 2021-07-15 at 2 00 45 PM" src="https://user-images.githubusercontent.com/85946042/125842891-2f773065-691b-41f6-9e92-4a01bcfd89fe.png">

  - **Refactored Scores by School Spending:**
  - <img width="680" alt="Screen Shot 2021-07-15 at 2 03 21 PM" src="https://user-images.githubusercontent.com/85946042/125843335-a0e07823-71ec-4a23-be31-968e1576d377.png">


* Scores by School Size:
  - **Original Scores by School Size:**
  - <img width="630" alt="Screen Shot 2021-07-15 at 2 00 58 PM" src="https://user-images.githubusercontent.com/85946042/125842931-d24835ce-b4b9-46a4-8ba5-285faa5ab4a8.png">

  - **Refactored Scores by School Size:**
  - <img width="622" alt="Screen Shot 2021-07-15 at 2 03 38 PM" src="https://user-images.githubusercontent.com/85946042/125843364-0de9ccfc-542b-4854-bd66-f79c5aa9436f.png">


* Scores by School Type:
  - **Original Scores by School Type:**
  -  <img width="588" alt="Screen Shot 2021-07-15 at 2 01 24 PM" src="https://user-images.githubusercontent.com/85946042/125842933-f7897de0-f62b-45a8-9408-c745af7e07b7.png">
  - **Refactored Scores by School Type:**
  - <img width="589" alt="Screen Shot 2021-07-15 at 2 03 50 PM" src="https://user-images.githubusercontent.com/85946042/125843380-1578e627-12ec-4f0f-bcb1-f0aba8725973.png">




## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. 

