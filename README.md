# Clean-and-Analyze-employee-exit-surveys

In this guided project, I'll work with exit surveys from employees of the [Department of Education, Training and Employment (DETE)](https://en.wikipedia.org/wiki/Department_of_Education_and_Training_(Queensland)) and the Technical and Further Education (TAFE) institute in Queensland, Australia. You can find the TAFE exit survey [here](https://data.gov.au/dataset/ds-qld-89970a3b-182b-41ea-aea2-6f9f17b5907e/details?q=exit%20survey) and the survey for the DETE [here](https://data.gov.au/dataset/ds-qld-fe96ff30-d157-4a81-851d-215f2a0fe26d/details?q=exit%20survey).

In this project, I'll play the role of data analyst and pretend our stakeholders want to know the following:

1)Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?<br>

2)Are younger employees resigning due to some kind of dissatisfaction? What about older employees?

Below is a preview of a couple columns we'll work with from the dete_survey.csv:

ID: An id used to identify the participant of the survey<br>
SeparationType: The reason why the person's employment ended<br>
Cease Date: The year or month the person's employment ended<br>
DETE Start Date: The year the person began employment with the DETE<br>
Below is a preview of a couple columns we'll work with from the tafe_survey.csv:<br>

Record ID: An id used to identify the participant of the survey<br>
Reason for ceasing employment: The reason why the person's employment ended<br>
LengthofServiceOverall. Overall Length of Service at Institute (in years): The length of the person's employment (in years)<br>
Let's start by reading the datasets into pandas and exploring them.<br>
