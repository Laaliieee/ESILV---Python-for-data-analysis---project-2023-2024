# ESILV---Python-for-data-analysis---project-2023-2024

### Presentation

We do our project on Drug Consumption with the dataset published in the website UCI on 10/16/2016 (URL : https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified). 

Indeed, drugs, whether legal or illegal, are a real scourge in our society given the behavioral, physical and psychological impacts of those who are dependent on them.

We try to follow an approach to see the impacts of the consumption of drug on people with variables given in the dataset such as : extravartion, neuroticism, openness to experience, agreeableness, conscientiousnes, impulsivity and sensation seeing.

Our study also focuses on other characteristics that can drive or explain drug use: age, ethnicity, country, gender and education.

We have chosen to respond through this notebook to different problems: 

- **Can a person's gender be predicted only through their legal drug consumption habits.**
- **Can the gender of a person be predicted through all the parameters of the dataset**
- **Drug use based on personality analysis**

This dataset allows us to apply differents method of prediction :

- RandomForestClassifier
- DecisionTreeClassifier
- KNeighborsClassifier
- LogisticRegression

### Characteristics of our dataset

**Shape**: 1884 rows × 32 columns

**Columns and signification**:

- *Genre*

0.48246 : 'Female'

-0.48246 : 'Male'

- *Education*
 
-2.43591	Left School Before 16 years
  
-1.73790	Left School at 16 years	

-1.43719	Left School at 17 years	

-1.22751	Left School at 18 years	

-0.61113	Some College,No Certificate Or Degree	

-0.05921	Professional Certificate/ Diploma	

0.45468	University Degree	

1.16365	Masters Degree	

1.98437	Doctorate Degree	

- *Age*
  
0.95197: '18-24'
  
0.07854: '25-34'

0.49788: '35-44'

1.09449: '45-54'

1.82213: '55-64'

2.59171: '65+'

- *Country*

-0.09765 : 'Australia',

0.24923 : 'Canada',

-0.46841 : 'New Zealand',

-0.28519 : 'Other',

0.21128 : 'Republic of Ireland',

0.96082 : 'UK',
     
-0.57009 : 'USA'

- *Ethinicity*
-0.50212 : 'Asian',
  
-1.10702 : 'Black',

1.90725 : 'Mixed-Black/Asian',

0.12600 : 'Mixed-White/Asian',

-0.22166 :'Mixed-White/Black',

0.11440 : 'Other',

-0.31685 : 'White'

*Frequence* = {
     'CL0' : 'Never Used',
     'CL1' : 'Used over a Decade Ago',
     'CL2'  : 'Used in Last Decade',
     'CL3' :  'Used in Last Year',
     'CL4'  : 'Used in Last Month',
     'CL5' :  'Used in Last Week',
     'CL6' :  'Used in Last Day'
}


**Participants** : Dounia BOUGAMZA , Joalie CORNELIE, Margaux DELAFOSSE
