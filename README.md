# (No Show Appointment)
## by (Oni Sodiq Adesola)


## Dataset

This dataset collects information from 110527 medical appointments in Brazil with features like Gender, ScheduledDay, AppointmentDay e.t.c and is focused on the question of whether or not patients show up for their appointment. This analysis looks into those factors that are important for us to know in order to predict if a patient will show up for their scheduled appointment? The dataset can be found [here] (https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv&sa=D&ust=1532469042118000), with features documentation [here] (https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True).

## Summary of Findings
I did some wrangling to detect and clean some quality and tidiness issues in the data set, after cleaning i then focuses on answering the following questions for my analysis:


1. How many patients showed up for their appointment and how many did not?
2. Is there any relationship between Age and Showed?
3. Is there any relationship between Neighbourhood and Showed?
4. Is there any relationship between Scholarship and Showed?
5. What is the relationship between Gender and Showed?
6. What effect does AppointmentDay have on Showed?
7. Does SMS received have effect on patient that Showed for their appointment?



## Key Insights 

In this analysis, various factors that we can look into inorder to predict whether patients will show up for their appointment were looked into and the following results were obtained:

1. A sum plot was used to show the distribution of ages of patients that showed up for their appointment. The maximum appointments are for infants. There is a drop and then a spike at around the age of 50. Finally, as the age progresses less and less people set up appointments.
2. A bar plot was used to show the distribution of neighbourhood of patients that showed up for appointment. The neighborhood data varied alot. Jardim Camburi has very high number of appointments while there are some neighborhoods that have less than 10 appointments.
3. A barplot also shows that more females tends to show up for their appointment compared to males.

4. A bar chart shows that patients tends to show up for their appointment mostly in May compared to April and June, few people showed up in April.
