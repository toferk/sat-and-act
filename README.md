# SAT & ACT Data Exploration and Analysis: 
## Maximizing Participation Rates for the College Board

### Problem Statement
For this project, we're going to take a look at aggregate SAT and ACT scores and participation rates from each state in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states. 

Sample prompt:
"The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. Your presentation and report should be geared toward non-technical executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in a state of your choice."

### Executive Summary
The College Board faces certain challenges when it comes to increasing participation rates across staes. Noteably, some states mandate and/or freely provide the alternative ACT, which can deter students from taking the SAT altogether. To combat this, the College Board can work with these states' Board of Education to shift their policies, as they did with Colorado and Illinois. Otherwise, they can focus on engaging states with relatively low SAT participation rates, where there is no such imposed requirement, such as Georgia, Oregon, and California, by making the SAT more accessible to students in a variety of ways. When SAT participation rates in these states rise, they might notice a decline in average total scores. 


### Contents
Code
 - Jupyter Notebook 
   - Data Import & Cleaning
   - Exploratory Data Analysis
   - Data Visualization and Descriptions
   - Conclusions and Recommendations  

Presentation  

Data  
- [2017 SAT Scores](./data/sat_2017.csv) ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
- [2017 ACT Scores](./data/act_2017.csv) ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
- [2018 SAT Scores](./data/sat_2018.csv) ([source](https://reports.collegeboard.org/sat-suite-program-results/state-results))
- [2018 ACT Scores](./data/act_2018.csv) ([source](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf))
- [Final](./data/final.csv) (created in Jupyter Notebook)

Images  


--------------------

### Data Dictionary
Data dictionary for `final` dataset, a complete and clean combination of the 4 previously cited datasets:

Column | Type | Description
--- | --- | --- | 
state | object | 50 states
sat_2017_part | float64 | 2017 SAT participation rates
sat_2017_erw | int64 | 2017 SAT Evidence-based Reading and Writing Scores
sat_2017_math | int64 | 2017 SAT Math Scores
sat_2017_total | int64 | 2017 SAT Total Scores (Sum of Subject Scores)
act_2018_part | float64 | 2018 ACT participation rates
act_2018_composite | float64 | 2018 ACT Composite Scores (Average of Subject Scores)
sat_2018_part | float64 | 2018 SAT participation rates
sat_2018_erw | int64 | 2018 SAT Evidence-based Reading and Writing Scores
sat_2018_math | int64 | 2018 SAT Math Scores
sat_2018_total | int64 | 2018 SAT Average Total Scores (Sum of Subject Scores)
act_2017_part | float64 | 2017 ACT participation rates
act_2017_english | float64 | 2017 ACT English Scores
act_2017_math | float64 | 2017 ACT Math Scores
act_2017_reading | float64 | 2017 ACT Reading Scores
act_2017_science | float64 | 2017 ACT Science Scores
act_2017_composite | float64 | 2017 ACT Composite Scores (Average of Subject Scores)
act_part_change | float64 | % change in ACT participation rates
act_score_change | float64 | % change in Composite Score for ACT
sat_part_change | float64 | % change in SAT participation rates
sat_score_change | float64 | % change in Total Score for SAT

































