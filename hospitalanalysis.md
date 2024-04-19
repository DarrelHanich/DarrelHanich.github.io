### How are Hospitals Doing to Manage Care

<br><br>
<img src="images/Hospital Image.jpg?raw=true"/>
<br><br>
---
<br><br>
We have either been to a hospital for ourselves or for a loved one.  Depending on the issue, our stay can be short, i.e. for lab work, or a quick procedure.  Our stay could also be long.  Each hospital is limited to the number of beds that they have.  Certain hospitals also specialize in specific procedures.  It would be interesting to know how each hospital does for specific procedures and how they treat different groups based on current stereotypical trends.  
The hospital in question asked me to analyze the data given and to determine how they are doing.  They provided the data in 2 separate tables, specifically about demographics and health information. The data was originally collected on Kaggle and then formatted to create the tables in MySQL.  I then utilized SQL to collect and analyze the data for specific procedures as directed.
<br><br>
##THE QUESTIONS
<br><br>
The questions I was asked to analyze were as follows:
1.	Verify the length of stay for patients.
2.	Top 5 Specialties provided at the hospital.
3.	Correlation of Lab Procedures by race/ethnic group.
4.	Relationship between lab procedures and length of stay.
5.	Assembling a list of people to further research for deeper reasonings.
6.	Success Stories 
<br><br>
##THE ANALYSIS
<br><br>
#Length of Stay for Patients
<br><br>
For analyzing the length of stay for patients, I drew a histogram.  Here is the code I used to do the histogram within SQL, along with the results.
<br><br>
Code for Histogram
<br><br>
Visual of Histogram
<br><br>
The analysis of the histogram
<br><br>
#Top 5 Specialties
<br><br>
For determining the top 5 specialties, we filtered out of the health table the medical specialties with the most average procedures and the count of all these procedures.  
<br><br>
Code for Specialties
<br><br>
Snapshot of Table with Specialties
<br><br>
Analysis of Table
<br><br>
#Correlation of Lab Procedures by Race
<br><br>
To do this, I tied the demographic table with the health table and counted the lab procedures and sorted by race to build this data.
<br><br>
Code for Correlation
<br><br>
Snapshot of Table
<br><br>
Analysis of Table
<br><br>
#Relationship of Procedures to Length of Stay
<br><br>
For this analysis, I analyzed the average number of procedures with the length of stay.  I would say that the results are self-explanatory.
<br><br>
Code for Analysis
<br><br>
Snapshot of Results
<br><br>
Analysis of results
<br><br>
#List of Patients to research
<br><br>
For this analysis, I looked for patient numbers that are both African American and had an increase in Metformin.
<br><br>
Code for Analysis
<br><br>
Snapshot of Results
<br><br>
Analysis of Results
<br><br>
#Success Stories
<br><br>
For this analysis, I created statements that identified patients that did not return and the number of medications and lab procedures.  
<br><br>
Code for Analysis
<br><br>
Snapshot of Results
<br><br>
Analysis of Results
<br><br>
##Summary
<br><br>
1.	Verify the length of stay for patients.
2.	Top 5 Specialties provided at the hospital.
3.	Correlation of Lab Procedures by race/ethnic group.
4.	Relationship between lab procedures and length of stay.
5.	Assembling a list of people to further research for deeper reasonings.
6.	Success Stories 
<br><br>
##Call to Action
<br><br>
With this analysis, we can see how hospitals work to be efficient and effective with the care that they administer.  If this kind of analysis is of interest to you, please contact me.  I find analysis of data to be incredibly insightful.  I am also looking to get into data analytics.  If you have a position where these skills would be useful, please contact me.
