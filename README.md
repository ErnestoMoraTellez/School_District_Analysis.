# School_District_Analysis.

## Overview of School District Analysis
Maria need to analyse data from the school district to provide insides for performance trends. We analyse data for budget and test scores in math and reading. 
We have created two analysis, one with all information we got, and other excluding Thomas High School ninth grade, because Marie has been notified about academic dishonesty. So we made again the analisys without this infomration to see the influence and compare results.

## Purpose
We need to find trends on this information to help to make decitions for the school budgets and prioryties. We are using pandas to manipale data and show the information.

## School District Analysis results
- How is the district summary affected?

This is the district summary considering all the schools without cheating.
![image](https://user-images.githubusercontent.com/88845919/137596185-d86216e5-13d5-473b-ace4-a55abf2f3d83.png)

This is the district summary considering all the schools without Thomas High School (THS) ninth grade.
![image](https://user-images.githubusercontent.com/88845919/137596143-c92e6c42-9069-465a-81b3-6716535a91ba.png)

We can see that changing the scores of the ninth students in THS for math and reading affect more the  passing percentage the tests than the average of the scores. Specially the overall passing% has a bigger impact. We have a dicrease of 0.3%. This represents that 117 students less, didn't pass both exams compare to the first analysis. The reading and math passing percentage were also affected, but with less impact, 0.1% (49 students) and 0.2% (78) respectively.

The average of the math and reading scores is pretty much the same. Just the Math score decrease 0.1.

- How is the school summary affected?

This is the school summary with THS results.
![School_summary](https://user-images.githubusercontent.com/88845919/137596798-80c69725-1838-4fcc-903a-a081fd7c0fca.PNG)

This is the school summary without THS ninth grade results.
![School_summary_no_THS](https://user-images.githubusercontent.com/88845919/137596827-0ae894d5-337b-4cbc-aa2c-c0b6223bcd62.PNG)

We should notice that the only affected school is the THS. Because is the only one that we modify. Actually it has a vey high impact in the passing% for both exams. The math% decrease 26.36% (431 students), reading 27.65% (452 students), overall 25.87% (422 students). It's a very big share the one that was affected. And this made THS the school with the worst % of approval in math and reading topics. Not in the overall.
The average of the exams has very few impact, for math the score decrease 0.07 points and for reading it actually increase 0.05 points. This could mean that the 9th grade students probably need to focus more in reading. Beacuse the other grades has better scores in this topic and help the general average. However the impact or difference is very low.

- How does replacing the ninth grader's math and reading scores affect Thomas High School’s performance relative to the other schools?

This is the top five schools considering all information and the overall %.
![Top_5_schools](https://user-images.githubusercontent.com/88845919/137597827-7786e0c0-cd3d-4127-9448-f02b602d162f.PNG)

This is the top five schools with out 9th grade students from THS.
![image](https://user-images.githubusercontent.com/88845919/137597742-b30f42db-a7ee-4c5e-8e5e-c6f715d8c139.png)

Now, updating the information of THS with only the 10-12th grades results we can notice the following. 
In the above charts, we can see that the THS stills in 2nd place. Even the new overall % with this calculation (cosidering just 10-12th grade scores) decrease 0.32%. This impact wasn't enought to let Griffin High School get up to the second place.

- How does replacing the ninth-grade scores affect the following:
-- Math and reading scores by grade
-- Scores by school spending
-- Scores by school size
-- Scores by school type
