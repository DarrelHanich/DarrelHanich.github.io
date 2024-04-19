### How are Hospitals Doing to Manage Care
---
<br><br>
<img src="images/Hospital Image.jpg?raw=true"/>
<br><br>
---
<br><br>
We have either been to a hospital for ourselves or for a loved one.  Depending on the issue, our stay can be short, i.e. for lab work, or a quick procedure.  Our stay could also be long.  Each hospital is limited to the number of beds that they have.  Certain hospitals also specialize in specific procedures.  It would be interesting to know how each hospital does for specific procedures and how they treat different groups based on current stereotypical trends.
<br><br>
The hospital in question asked me to analyze the data given and to determine how they are doing.  They provided the data in 2 separate tables, specifically about demographics and health information. The data was originally collected on Kaggle and then formatted to create the tables in MySQL.  I then utilized SQL to collect and analyze the data for specific procedures as directed.
<br><br>
---
**THE QUESTIONS**
---
<br><br>
The questions I was asked to analyze were as follows:
- Verify the length of stay for patients.
- Top 5 Specialties provided at the hospital.
- Correlation of Lab Procedures by race/ethnic group.
- Relationship between lab procedures and length of stay.
- Assembling a list of people to further research for deeper reasonings.
- Success Stories 
<br><br>
---
**THE ANALYSIS**
---
<br><br>
_Length of Stay for Patients_
<br><br>
For analyzing the length of stay for patients, I drew a histogram.  Here is the code I used to do the histogram within SQL, along with the results.  The specific question that I was asked to obtain is "Are a majority of our patients staying longer than 7 days?"
<br><br>
<img src="images/Histogram of time query.png?raw=true"/>
<br><br>
<img src="images/Histogram of Time in Hospital.png?raw=true"/>
<br><br>
As we can see in the histogram, I discovered that the majority of patients are staying less than 7 days.  This would show that the hospital works to be efficient with their care.
<br><br>
_Top 5 Specialties_
<br><br>
For determining the top 5 specialties, I filtered out of the health table the medical specialties with the most average procedures and the count of all these procedures.  I was asked to determine the top 5 procedures for average procedures and the count.
<br><br>
<img src="images/Top 5 Procedures Query.png?raw=true"/>
<br><br>
<img src="images/Top 5 Procedures Results.png?raw=true"/>
<br><br>
From this table, we see that surgery for the cardiovascular and thoracic area are among the top surgical procedures, which would be an indicator that this hospital is a major thoracic surgery center.  Radiology is common as this deals with imaging and certain treatments.  Cardiology deals with the heart and those issues.
<br><br>
_Correlation of Lab Procedures by Race_
<br><br>
To do this, I tied the demographic table with the health table and counted the lab procedures and sorted by race to build this data.  I was asked to determine if there is a level of racial profiling or bias at the hospital.
<br><br>
<img src="images/Race Analysis Query.png?raw=true"/>
<br><br>
<img src="images/Race Analysis for Procedures Results.png?raw=true"/>
<br><br>
From the table, I found that there is no real difference on the number of procedures performed to different racial groups.
<br><br>
_Relationship of Procedures to Length of Stay_
<br><br>
For this analysis, I analyzed the average number of procedures with the length of stay.  I would say that the results are self-explanatory.
<br><br>
<img src="images/Time to Procedures Query.png?raw=true"/>
<br><br>
<img src="images/Time to Procedures Count Results.png?raw=true"/>
<br><br>

<br><br>
_List of Patients to research_
<br><br>
For this analysis, I looked for patient numbers that are both African American and had an increase in Metformin.
<br><br>
<img src="images/Metformin and African American Query.png?raw=true"/>
<br><br>
<img src="images/Metformin and African American Results.png?raw=true"/>
<br><br>
Analysis of Results
<br><br>
_Success Stories_
<br><br>
For this analysis, I created statements that identified patients that did not return and the number of medications and lab procedures.  
<br><br>
<img src="images/Patient Summary Query.png?raw=true"/>
<br><br>
<img src="images/Patient Summary Results.png?raw=true"/>
<br><br>
Analysis of Results
<br><br>
---
**Summary**
---
<br><br>
- Verify the length of stay for patients.
- Top 5 Specialties provided at the hospital.
- Correlation of Lab Procedures by race/ethnic group.
- Relationship between lab procedures and length of stay.
- Assembling a list of people to further research for deeper reasonings.
- Success Stories 
<br><br>
---
**Call to Action**
---
<br><br>
With this analysis, we can see how hospitals work to be efficient and effective with the care that they administer.  If this kind of analysis is of interest to you, please contact me.  I find analysis of data to be incredibly insightful.  I am also looking to get into data analytics.  If you have a position where these skills would be useful, please contact me.
