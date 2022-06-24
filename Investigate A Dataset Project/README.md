# WeRateDogs Data Exploration
## by Emefiele-Konyeri Awinrin
## Dataset
This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
* ScheduledDay’ tells us on what day the patient set up their appointment.
* ‘Neighborhood’ indicates the location of the hospital.
* ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.
* AppointmentID - Identification of each appointment
* Gender - Male or Female . Female is the greater proportion, woman takes way more care of they health in comparison to man.
* Age - How old is the patient.
* Neighbourhood - Where the appointment takes place.
* SMS_received - 1 or more messages sent to the patient.

> This project has two main parts

1. In Part I, Exploratory data visualization, i used use Python visualization libraries to systematically explore this dataset(consists of information regarding 110527 appointments and 14 features), starting from plots of single variables and building up to plots of multiple variables.

> The Medical Appointments No-Show data consists of 110527 appointments and 14 features('PatientId', 'AppointmentID', 'Gender', 'ScheduledDay','AppointmentDay', 'Age', 'Neighbourhood', 'Scholarship', 'Hipertension','Diabetes', 'Alcoholism', 'Handcap', 'SMS_received', 'No-show'), after data cleaning the dataset was transformed to 110475 observations and 20 features(additional features: 'Scheduleddate', 'Appointmentday', 'Appointmentdate', 'AwaitingDays', 'Awaitingtime', 'Age_group').
       
2. In Part II, Explanatory data visualization, i produced a short presentation that illustrates interesting properties, trends, and relationships that were discovered in my dataset. The primary method of conveying my findings were through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

## Summary of Findings
* This dataset shows an unequal proportion of gender which would lead to a bias during exploratory data analysis. Equal proportion of gender would eliminate bias in conclusion of the analysis
*  Hypertension patients had the most appointments (62%) in those few months followed by Students on Diabetes patients (22%), Alcoholism patients (10%) and Handicap (6%)
* Monthly waiting time has the most number of appointments and highest No Show rate in the chart, with female patients having the most number of appointments in all awaiting times. This analysis enlightens the fact that shorter waiting times would be more appealing to the patients
* Adults(19-59) have the highest number of appointments and highest no-show-rate while Adolescence have the least number of appointments and least no-show-rate
* From the bar plot graph above, the No-Show rate and No of Appointments are higher before midweek and lower after midweek. The No-Show rate and No of Appointments seems to be directly proportional(the higher the appointments the higher the no show rate). Tuesday has the highest number of appointments and no show rate, this tells us patients are like if their appointments where scheduled after midweek when their work for the week has become less intensed
* The graph tells us that the neighbourhood JARDIM CAMBURI has the highest number of no show appointments and no show rate while AEROPORTO has the lowest number of no show appointments and no show rate
* Number of no shows has been increasing over the months even after the awaitingdays have been decreasing. which makes it a negative correlation between the two attributes
* Patients that received SMS had the highest no show rates after a week maybe because 1 text message is not enough to remind them of their appointment,before a week they had low no show rates.


## Key Insights for Presentation

For this presentation i will be revealing the collective factors responsible for this unnecessary high rate of patient no-shows, i will be using this attributes of interest:- No-Show, Waiting time, Age, Appointment day e.t.c, to explain why patients don't show up for their appointments. Patients' failure to attend medical appointments saps resources and waste every business's most valued asset, "time.". Patients who miss doctor's appointments compromise the quality of care and risk undetected and untreated medical conditions. 