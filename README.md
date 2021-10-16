# School_District_Analysis.

## Overview of School District Analysis
Maria need to analyse data from the school district to provide insides for performance trends. We analyse data for budget and test scores in math and reading. 
We have created two analysis, one with the hole information we get, and other excluding Thomas High School ninth grades, because Marie has been notified about academic dishonesty. So we made again the analisys without this infomration to see the influence and compare results.

## Purpose
We need to find trends on this information to help to make decitions for the school budgets and prioryties. We are using pandas to manipale data and show the information.

## School District Analysis results
### How is the district summary affected?
![image](https://user-images.githubusercontent.com/88845919/137596185-d86216e5-13d5-473b-ace4-a55abf2f3d83.png)

This is the district summary considering all the schools without cheating.
![image](https://user-images.githubusercontent.com/88845919/137596143-c92e6c42-9069-465a-81b3-6716535a91ba.png)

This is the district summary considering all the schools without Thomas High School (THS).

We can see that changing the scores of the ninth students in THS for math and reading affect more percetage of passinf the tests. Specially the overall passing% has more impact. We have a dicrease of 0.3%. This represents that 117 students less, didn't pass both exams compare to the first analysis. The reading and math passing percentage were also affected, but with less impact, 0.1% (49 students) and 0.2% (78) respectively.

The average of the math and reading scores is pretty much the same. Just the Math score decrease 0.1.

### How is the school summary affected?
![School_summary](https://user-images.githubusercontent.com/88845919/137596798-80c69725-1838-4fcc-903a-a081fd7c0fca.PNG)

This is the school summary with THS results.
![School_summary_no_THS](https://user-images.githubusercontent.com/88845919/137596827-0ae894d5-337b-4cbc-aa2c-c0b6223bcd62.PNG)
This is the school summary without THS ninth grade results.

We would notice that the only affected school is the THS. Because is the only one that we modify. Actually it has a vey high impact in the passing% for both exams. The math% decrease 26.36% (431 students), reading 27.65% (452 students), overall 25.87% (422 students). It's a very big share the one that was affected. And this made THS the school with the worst % of of approval in math and reading topics.
The average of 
