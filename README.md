# Doctor Semmelweis discovery

------

> <img src="https://raw.githubusercontent.com/m0gr1m/Dr_Semmelweis_discovery/main/semmelweis.png?token=AVVSRLSLFSEYZJKR3LGVFZDBIXNVM" style="zoom: 80%;" align="left"> In 1847, Semmelweiss was appointed as a house officer in one of the two obstetric clinics at the University of Vienna Allgemeine Krankenhaus (General Hospital). He observed that maternal mortality rates, mostly attributable to puerperal fever, were substantially higher in one clinic compared with the other (16% versus 7%). He also noted that doctors and medical students often went directly to the delivery suite after performing autopsies and had a disagreeable odour on their hands despite handwashing with soap and water before entering the clinic. He hypothesized therefore that “cadaverous particles” were transmitted via the hands of doctors and students from the autopsy room to the delivery theatre and caused the puerperal fever [(Source)](https://www.ncbi.nlm.nih.gov/books/NBK144018/).

------

## Data 

[Monthly deaths](https://github.com/m0gr1m/Dr_Semmelweis_discovery/blob/main/monthly_deaths.csv) - cover the time period from January 1841 to March 1849 and include information on the number of births and the number of deaths for the month.

[Yearly deaths by clinic](https://github.com/m0gr1m/Dr_Semmelweis_discovery/blob/main/yearly_deaths_by_clinic.csv) - As above, the database contains information on the number of births and the number of deaths, with additional information on clinic affiliation. The data covers the period from 1841 to 1846 with yearly data.

------

## Motivation

The data that Doctor Semmelweis collected is very well documented, so it is a valuable resource for learning how to perform statistical tests comparing two groups. 

The knowledge gained in this way can then be used to perform similar tests on other data sets. For example, it can help determine whether the risk of heart attack depends on the degree of obesity or whether smoking cigarettes increases the chance of lung cancer. In technical issues, for example, it can determine whether the same product produced on machine A is different from that produced on machine B.

### Main goal

To determine by statistical methods whether:

+ there is a difference between the mortality rate in the first clinic, where doctors and students delivered babies, and the second clinic, where only midwives did so,
+ the mortality rate decreased significantly in Doctor Semmelweis' clinic after he recommended that the attendants wash their hands. Mandatory hand washing before delivered babies: 1 June 1847. 

## Side goal

+ Better understanding of Python and statistical methods.

