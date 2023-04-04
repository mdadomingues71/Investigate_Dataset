# Investigate_Dataset

No-show appointments

1 - Introdution

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients 
show up for their appointment. A number of characteristics about the patient are included in each row.

2 - Questions for Analysis

Q1 - Correlation between missing the appointment and the age o patient.

Q2 - Correlation between missing the appointment and the Gender of the patient.

Q3 - Correlation between missing the appointment and the received the SMS.

Results
We have a majority of Female, around 65% of the total are women;

ScheduledDay = 2016-05-06 to 2016-06-08; AppointmentDay 2016-04-29 to 2016-06-08;

Patients are aged between 0 and 115, we have a balance between patients from 0 to 60 in consultations;

There are 81 service locations (neighbourhood), they are located in Grande Vitória (display.Image[89];

Most patients did not have schorlarship, 90% (it would be necessary to verify this information, as it seems to be wrong);

19% of patients have hypertension, 7% Diabetes, 3% alcoholism;

2% reported having a disability (handcap).

32% received SMS and 80% attended the appointment.

Q3 - Avaliation
Low correlation between SMS and appointment attendance;

Most did not receive the SMS 68%;

Already of those who received 43.83% attended;

Even without receiving the SMS, 56.16% of the people attended.

Conclusion

Conclusions of the analyzes follow:

Between 0 and 80 years of age attendance at appointments is very similar, being slightly higher in the 10 to 30 and 60 to 80 age ranges;
There is a low correlation between gender and attendance, female and male have the same attendance rate;
The correlation between attendance and receiving the SMS is also low, in addition to having a large number of patients who do not receive the message;

Limitations

Despite the amount of data, their period is short;
More information about ScheduleDay is missing, how this first contact was made (in person, telephone, e-mail, SMS, etc.), this information could add greater value to the dataset;
Other data tend to be a little superficial and prevent further analysis;
