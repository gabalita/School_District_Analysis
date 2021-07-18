# School District Analysis

# Overview of the school district analysis:
The purpose of this project was to analyze and summarize student funding and standardized test scores for a local school district. The analysis will be used to understand the performance of each school and make strategic decisions about future funding. A second round of analysis was performed when inaccurate math and reading scores for 9th graders at Thomas High School were discovered. The impact of removing this false data is highlighted. 

# Results: 
**1. How is the district summary affected?**
 - After removing 9th grade Thomas High School data, the district's performance fell in almost every category. For example, the overall passing percentage decreased from 65.2% and 64.9%. On the other hand, there was no change in the average reading score. 

- In summary, although the change was miniscule, the inclusion of the inaccurate 9th grade Thomas High data artificially increased the district's performance. 
  
<img width="1076" alt="Screen Shot 2021-07-17 at 5 19 26 PM" src="https://user-images.githubusercontent.com/10199828/126049612-6ca71d95-8ddb-462c-86e1-3db559934cd3.png">

 <img width="1076" alt="Screen Shot 2021-07-17 at 5 18 51 PM" src="https://user-images.githubusercontent.com/10199828/126049600-6be7b3d1-7848-4d46-a6dd-e34c9711729a.png">

**2. How is the school summary affected?**
 -  Since only Thomas High School's scores contained inaccurate data, the results for the other schools did not change.  The performance breakdown for each school is shown below.

<img width="976" alt="Screen Shot 2021-07-17 at 7 23 40 PM" src="https://user-images.githubusercontent.com/10199828/126051397-a520fb5e-c7d0-4a5e-8773-ae38883fed0c.png">

- The removal of 9th grade scores from Thomas High School's dataset did not significantly lower the school's performance in either reading or math. The changes are demonstrated below:

<img width="1122" alt="Screen Shot 2021-07-17 at 7 29 51 PM" src="https://user-images.githubusercontent.com/10199828/126051464-9508d4ea-73e2-4dcc-89e2-0beea60bd40e.png">
**Uncorrect data (includes 9th grade)**
<img width="1120" alt="Screen Shot 2021-07-17 at 7 30 39 PM" src="https://user-images.githubusercontent.com/10199828/126051480-c091988b-1e8d-4776-9321-06d78865ca24.png">
**Corrected data (excludes 9th grade)**
<img width="1124" alt="Screen Shot 2021-07-17 at 7 31 09 PM" src="https://user-images.githubusercontent.com/10199828/126051486-93302850-2687-450a-9544-2323b00e747c.png">

**3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
- Overall, the replacement of ninth grade scores did not significantly alter Thomas High School's performance relative to other schools. After the data was corrected, the school's final success rates were still high, with nearly 90% of its student body passing the standardized tests in both math and reading. There performance was in line with other charter schools in surrounding districts. 


**4. How does replacing the ninth-grade scores affect the following:**
- Math and reading scores by grade
  - Average math scores were not altered. 
  
  <img width="662" alt="Screen Shot 2021-07-17 at 8 09 16 PM" src="https://user-images.githubusercontent.com/10199828/126051980-157650a5-e969-4b5f-8785-9cd007aac538.png">
  
  - Average reading scores were not altered. 
  
  <img width="747" alt="Screen Shot 2021-07-17 at 8 09 57 PM" src="https://user-images.githubusercontent.com/10199828/126051985-38eeff4a-111e-4d96-b971-496be0a048bd.png">
 
- Scores by school spending
  - This metric was not significantly affected. For example, eliminating 9th grade only decreased the $630-$644 spending range from 78.51 to 78.50 (a change of less than 0.01%). 
<img width="964" alt="Screen Shot 2021-07-17 at 8 04 21 PM" src="https://user-images.githubusercontent.com/10199828/126051929-3683b69e-16a7-43f5-961a-8ef2d594045b.png">
- Scores by school size
- Scores by school type



# Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
