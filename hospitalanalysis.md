## How are Hospitals Doing to Manage Care

<img src="images/?raw=true"/>

We have either been to a hospital for ourselves or for a loved one.  Depending on the issue, our stay can be short, i.e. for lab work, or a quick procedure.  Our stay could also be long.  Each hospital is limited to the number of beds that they have.  Certain hospitals also specialize in specific procedures.  It would be interesting to know how each hospital does for specific procedures and how they treat different groups based on current stereotypical trends.  
The hospital in question asked me to analyze the data given and to determine how they are doing.  They provided the data in 2 separate tables, specifically about demographics and health information. The data was originally collected on Kaggle and then formatted to create the tables in MySQL.  I then utilized SQL to collect and analyze the data for specific procedures as directed.
THE QUESTIONS
The questions I was asked to analyze were as follows:
1.	Verify the length of stay for patients.
2.	Top 5 Specialties provided at the hospital.
3.	Correlation of Lab Procedures by race/ethnic group.
4.	Relationship between lab procedures and length of stay.
5.	Assembling a list of people to further research for deeper reasonings.
6.	Success Stories 
THE ANALYSIS
Length of Stay for Patients
For analyzing the length of stay for patients, I drew a histogram.  Here is the code I used to do the histogram within SQL, along with the results.
Code for Histogram
Visual of Histogram
The analysis of the histogram
Top 5 Specialties
For determining the top 5 specialties, we filtered out of the health table the medical specialties with the most average procedures and the count of all these procedures.  
Code for Specialties
Snapshot of Table with Specialties
Analysis of Table
Correlation of Lab Procedures by Race
To do this, I tied the demographic table with the health table and counted the lab procedures and sorted by race to build this data.
Code for Correlation
Snapshot of Table
Analysis of Table
Relationship of Procedures to Length of Stay
For this analysis, I analyzed the average number of procedures with the length of stay.  I would say that the results are self-explanatory.
Code for Analysis
Snapshot of Results
Analysis of results
List of Patients to research
For this analysis, I looked for patient numbers that are both African American and had an increase in Metformin.
Code for Analysis
Snapshot of Results
Analysis of Results
Success Stories
For this analysis, I created statements that identified patients that did not return and the number of medications and lab procedures.  
Code for Analysis
Snapshot of Results
Analysis of Results
Summary
1.	Verify the length of stay for patients.
2.	Top 5 Specialties provided at the hospital.
3.	Correlation of Lab Procedures by race/ethnic group.
4.	Relationship between lab procedures and length of stay.
5.	Assembling a list of people to further research for deeper reasonings.
6.	Success Stories 
Call to Action
With this analysis, we can see how hospitals work to be efficient and effective with the care that they administer.  If this kind of analysis is of interest to you, please contact me.  I find analysis of data to be incredibly insightful.  I am also looking to get into data analytics.  If you have a position where these skills would be useful, please contact me.

