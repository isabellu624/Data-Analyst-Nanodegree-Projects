# Data-Analyst-Nanodegree-Projects
This repository contains a collection of all the capstone projects conducted for the Data Analyst Nanodegree Certification - Udacity
## Project 5: PISA 2012 Test Data Exploration: A Focus on Family Factors
## Dataset

> PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

> Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

> The dataset consisted of _485490_ observations with _636_ variables. It can be download [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000), with feature documentation available [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000).

> After looking into the raw data and data dictionary, we decided to focus on the effects of family-based factors((e.g., language at home, household possessions, family status, parents' working status, and parents' education levels) on the students' academic performance. We started the exploration by wrangling the data accordingly.


## Summary of Findings

> We plotted the score as boxchart for each country according to the decreasing order ranked by the average performance of countries. We noticed that: Most countries ranking from 10th to 40th seem to perform comparably to each other, while the top players outperform significantly over the other countries for all three subjects, espcially the 1st player - China-Shanghai. The box-and-wiskers plot allows us to see the outliers for each country. For example, we find that, the outstanding results of math come from China-Shanghai, while the outstanding results of reading come from Japan, and that of science from Singapore. Although it's not the focus of this study, the underlying reasons can be explored by checking the influencing factors of the difference among countries.

> Language at home is supposed to influence the test score as students who speak the same language as test language is likely to perform better than students who speak a different language. However, the violinplot shows no significant difference between these two categories. One possible reason is that English has been widely used around the world. Even in non-English-speaking countries, it has become the most popular second language.

> As an indicator of household possession, number of books at home does have a positive relationship with test scores, not only for reading or science but also math.

> We also find that family status has significant effect on test scores. In general, students in homes with two parents do better in all three subjects. Students in a single parent household tend to do better when that parent is the Mother. Students with neither parent living at home have the lowest achievement.

> Parent employment status is also an important predictor of academic achievement. Students with fully employed parents do better in tests. Having a mother who works part-time or full-time is associated with test outcomes. Students with a father employed less than full-time have lower test scores than if the father had a full-time postion. A stay-at-home (Other) parent does not improve scores.

> Results show that parent education level is associated with scores as well. Students with higher educated parents do better in tests. Students with one or two parents whose whose education level equal or higher than ISCED 5A,6 have the highest scores. The difference between ISCED 3B,C and ISCED 3A,4 is not significant.

> In multivariate section, the positive correlationship between Math_score, Reading_score, and Science_score is identifed. I also extended the investigation of the influence of family-based factors on test scores by looking at the variation across countries. The results showed that the general influence of family-based factors is valid for most countries, with a few exceptions. Since we only focus of family-based factors in this study, there could be other factors such as school factors or society factors that make the divergence.


## Key Insights for Presentation

> For the presentation, I focus on the effects of family-based factors((e.g., language at home, household possessions, family status, parents' working status, and parents' education levels) on the students' academic performance. I start by introducing the score variable, followed by the bivariate exploration of the influence of each family-based variable. Afterward, the Facetgrit and Pointplot are plotted to illustrate the multivariate exploration on Score, Family-based factors, and Country.

## Project 4
