# Covid-19 Malta data 
## What the project does
This repository holds data about Covid-19 cases in Malta, Europe (MT). The data is in CSV format, dates are in dd/MM/yyyy format. The malta.csv file contains all information available of every COVID-19 case in Malta.  Whilst the malta_time_series.csv file contains the summary of cases in Malta by confirmed, deaths, recovered and active. All the original sources are found under DOI directory.

## Why the project is useful
It is useful for data scientists and others who are analysing covid-19 data. It will be kept up to date as new data is made available.

## How users can get started
Just checkout the repository and include the CSV data in your project.

## Where users can get help
It is suggested to file an issue on GitHub with any queries or suggestions.

## Who maintains and contributes to the project
This project is maintained by [Lobeslab Ltd](https://lobeslab.com).

## Clarifications
### Missing Data
Missing data means that the information is not available. This data is gathered manually from the daily media update provided by the health superintendent Profs. Charmaine Gauci.

### Input Errors prior to official infograms being made available
For the period 6th March-16th May 2020 we used to track cases from the audio/video press releases, this prior to official communications from the Sahha site or any official infocards being released. A number of discrepencies (due to human input error) were noted and have been adjusted accordingly using the official repository as reference:

6th March 2020 - First case
From: Malta	06/03/2020	0	0	0	0	0
To: Malta	06/03/2020	1	0	0	1	0

9th March 2020 -
From: Malta	09/03/2020	3	0	0	3	0
To: Malta	09/03/2020	4	0	0	4	0

11th March 2020-
From: Malta	11/03/2020	6	0	0	6	0
To: Malta	11/03/2020	7	0	0	7	0

12th March 2020
From: Malta	12/03/2020	6	0	0	6
To: Malta	12/03/2020	12	0	0	12

13th March 2020
From: Malta	13/03/2020	12	0	1	11	0
To: Malta	13/03/2020	13	0	1	12	0

15th March 2020
From: Malta	15/03/2020	21	0	1	20	0
To: Malta	15/03/2020	21	0	2	19	0

04th August 2020
From: Malta	04/08/2020	916	9	666	231	0
To: Malta	04/08/2020	906	9	666	231	0


### Inclusion of cases by migrants
On Sunday 16th August 2020, the Maltese Authorities announced that cases of COVID-19 from incoming illegal migrants will no longer be included in the total case count. They also reported that past cases will be removed. This has presented a data integrity problem for this repository since it is not entirely clear on which days these cases were removed. We also believe that it is unethical to remove such cases. For this reason, this repository shall not revise the case counts prior to the 16th of August. Should the cases of migrants be reported then this repository shall include them, otherwise if no information is available on the subject matter than such cannot be reported. Following are the noted discrepencies with sources not reporting migrant cases

16th August 2020 - 105 Cases - Sahha declared to stop reporting new migrant cases yet also removed existing migrant cases.
31st August 2020 - 137 Cases - 32 new migrant cases reported over above 105, thus 137 discrepency.
3rd September 2020 - 147 Cases - 10 new migrant cases reported over above 137 cases.
4th September 2020 - 174 Cases - 27 new migrant cases reported over above 147 cases.
21st September 2020 - 179 Cases - 5 new migrant cases reported over above 174 cases.

### Recoveries of migrant cases not removed
Although new cases of COVID-19 amongst illegal immigrants were removed from other repositories and no longer tracked, it is believed, that until the decision was taken some of the migrant cases recovered and were reported together with the local recoveries. This means that the delta in cases for confirmed, recovered and active across repositories that track migrant cases versus those that don't will not be consistent.
