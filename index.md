# Project: Identifiers for making better health insurance strategies

In the world of health insurance, one of the most important task is the development of different health insurance packages and strategies catering to the background of the costumers. This task can prove to be highly fruitful if the new strategies and insurance packages are designed using informed data and trend changes from past to present.

To see the change in trends, it is essential to not only look at the current data trends but also, to look and compare it to past data trends, which can be used to provide much better insight into the long running changes.

```
The main focus of the project is to highlight identifiers that a married 
will have health insurance with how much probability. 
Combining it with current data of similar kind, can give insight into 
changing behaviors and variables that have been important in getting 
more and more people into the health insurance net from past to present. 
This can be used to make assessments about the lack of insurance 
deals present and how they can be improved upon.
```
This project is aimed at developing and recognising patterns for the background common information of people from different regions in the US from year 1993 which could be used to amalgamate into the current data to identify changes which could be used to develop better insurance packages catering to the needs and affordability of future potential health insurance buyers.


### Data Science tools at work

#### First Plot

The image below shows the frequency of working wives with different levels of education in different regions of US.

![1st image](https://cloud.githubusercontent.com/assets/28226371/25567124/69ab6064-2e00-11e7-8abc-68e97cc1dd06.jpg)

It can be fairly deduced that the in all the regions, the most number of working wives, covered by husbands health insurance, have 12 years of education.
This is a great indicator which can be further refined by taking in the working hours per week of working wives, if the working wives have kids from ages 1 to 6 or 6 to 18 and monthly income of husband.

##### Deductions

Not much can deduced than what has already been stated. But the most promising aspect is the introduction of new variables, which will surely provide with much meaningful identifiers and many amazing strategic points can be made if these identifiers be compared side by side with current data of similar kind.

#### Second Plot

This image shows the working hours per week of working wives with and without the coverage of husbands health insurance.

![2nd image](https://cloud.githubusercontent.com/assets/28226371/25567131/7441150a-2e00-11e7-95ee-6ff4715d6b23.jpg)

##### Deductions

The bars in the image can be grouped and divided into four merged columns. O working hours, less than full week (<40 hrs), full week (40 hrs) and more than full week (>40 hrs). It is apparent than almost half the wives wrking o hours are covered with health insurance and half of them are not. So, there isn't much of any indicator. Most prominent is the full week working wives majority of which are not covered by the health insurance. Higher number of working wives work less than full week while being insured and higher number of working wives work more than full week while not being covered by the health insurance. There seems to be a general pattern here. 

It can be fairly computed what is the probability of a working wive having an insurance if working "x" hours per week.
This result can be used in conjunction with other variables like having kids, working experience and husbands income to have better idea of the probability that any married women has health insurance if she works "X" hours with "Y" years of experience having "Z" extra income of husband.

###### Further Analysis

As stated above
```
The main focus of the project is to highlight identifiers that a married 
will have health insurance with how much probaility. 
Combining it with current data of similar kind, can give insight into 
changing behaviors and variables that have been important in getting 
more and more people into the health insurance net from past to present. 
This can be used to make assessments about the lack of insurance 
deals present and how they can be improved upon.
```
Much analysis is needed before any solid assessment can be made. The analysis will extend to include all the 13 variables in the 
dataset with pairwise and multivariate probabilistic numeric and graphical results. In the end, following type of answers could 
be easily answered,

What is the probability that a married women with three kids under 18, living in southern US, is covered health insuance?

What percentage of married women having no health insurance, are likely to be working more than 40 hours?

If I pick a random women with three kids under 18, what is the probability of her having health insurance from her own job?

If the husbands income in the first quartile, how much probability is there that wive is working full week without any health insurance?

The answer to these and similar questions can be beneficial in assessing the pros an cons in health insurance packages and policies of the past and if the similar data of current time is analysed the same way, it can deduced that which factors are beneficial in getting more people into health insurance and which factor backfired. Future changes in strategies of health insurance packages made keeping these deductions in mind. 

## Background on the data

The dataset consists of 22272 data points with 13 variables, about the working wives with or without husbands health insurance coverage in different parts of US. The collected data is for the year 1993, thus is perfect for assessing the changes in insurance coverage of working wives from the past by comparing with current data of such type. The 13 variables include Working hours per week 
by wife (numeric), wife covered by husband's health insurance (yes/no), wife has health insurance through her job (yes/no), Husband has health insurance through his job (yes/no), Education level of wife (6 parameters), race (3 parameters), Hispanic (yes/no), Number of kids under age 6 (numeric), number of kids between 6-18 ages (numeric), Husband's income (numeric), US region (4 regions), sampling weight (numeric).

Image below represents the number of data points collected from different parts (4) of the US.

![3rd image](https://cloud.githubusercontent.com/assets/28226371/25567115/44d9c032-2e00-11e7-8e6d-ecad5915b3e0.jpg)

Image below represents the normalised bars of working experience of working wives in different parts(4) of the US.

![4th image](https://cloud.githubusercontent.com/assets/28226371/25567133/79498122-2e00-11e7-90f8-a8d2b4eccd80.jpg)

The detailed description of the source data can be viewed [here](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/HI.html).
