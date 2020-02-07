# Data Analysis of SAT & ACT of 2017 & 2018

### Overview

Our analysis will contain:
- basic statistics (distributions, confidence intervals, hypothesis testing)
- visualizations
- ACT & SAT exam dataset from 2017 to 2018
- Jupyter notebooks

---
### Problem Statement
There is a low participation for SAT exam as compared to ACT, the analysis will look for correlations in the data and make inferences to ensure that any hypothesis is true

---

### Datasets

#### Provided Data

For this project, there have four datasets:

- [2017 SAT Scores](../data/sat_2017.csv)
- [2017 ACT Scores](../data/act_2017.csv)
- [2018 SAT Scores](../data/sat_2018.csv)
- [2018 ACT Scores](../data/act_2018.csv)
---

#### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**State**|*object*|ACT/SAT|The name of one of United States of America's National state| 
|**ACT_Participation**|*float*|ACT|Percentage of actual number people attending the ACT examination compared to the number people registered | 
|**SAT_Participation**|*float*|SAT|Percentage of actual number people attending the SAT examination compared to the number people registered | 
|**ACT_English**|*float*|ACT|Mean score of participants taking ACT exam for english| 
|**ACT_Math**|*float*|ACT|Mean score of participants taking ACT exam for math| 
|**ACT_Reading**|*float*|ACT|Mean score of participants taking ACT exam for reading| 
|**ACT_Science**|*float*|ACT|Mean score of participants taking ACT exam for science| 
|**ACT_Composite**|*float*|ACT|Mean score of participants taking ACT exam for all examinations|
|**SAT_Evidence-Based_Reading_and_Writing**|*float*|SAT|Mean score of participants taking SAT exam for all examinations| 
|**SAT_Math**|*float*|SAT|Mean score of participants taking SAT exam for maths|
|**SAT_Total**|*float*|SAT|Total score of participants taking SAT exam for all examinations|

#### References
https://blog.prepscholar.com/act-vs-sat
https://blog.prepscholar.com/new-sat-vs-old-sat-quick-summary
