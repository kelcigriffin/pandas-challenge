# pandas-challenge
Week 4 homework

# Background:

You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.

# Written Report Instructions:
To receive all points, the written report presents a cohesive written analysis that summarizes the analysis and draws two correct conclusions or comparisons from the calculations.

# Written Report:
Our dataset includes 15 schools, with a population of 39,170 students and a total budget of $24,649,428 across the district. We have also been provided with academic performance data, and will be leveraging this information to uncover trends and influence strategic decisions for the upcoming school year. My goal, with that information in mind, is to look at each school to see if there is correlation between academic performance, school size, school type, and budget. If smaller schools, or higher budgets per student, seem to result in higher scores (especially in math), I will note those trends and make recommendations based on my findings. 

Our initial findings show that the average math and reading scores across all 15 schools are 78.985 and 81.878 respectively, with scores being rounded to the nearest thousandth. In our district, students are passing math at a rate of 74.98%, and passing reading at a rate of 85.5%. For reference, a passing grade is considered a score of 70 or higher. We can see that on average, our district is producing passing grades, but there is obvious disparity in the passing rates of math vs reading. Additionally, only 65% of students are passing in both subjects. At first glance, it is clear that students are scoring lower in math than in reading, and the passing rate for the subject is lower as well. Now, we must look further into the available data to attempt to uncover why this might be the case. 

In my analysis, I compared each school's scores to their budgets, total population, and whether the schools were charter or district institutions. Surprisingly, each school's budget had no positive influence on math and reading scores. Huang High School had a per captia budget of $655, the highest dollar amount of our dataset, but produced some of the worst academic results in the district. Their overall passing rate was 53.5%, compared to Cabrere High School who spent $582 per student and had an overall passing rate of 91.3% of students. With spending showing little correlation to academic success, we moved to the next parameter: school size. Contrary to per capita budget, school size does seem to have an influence on academic performance in some way. Schools with up to 2000 students are able to produce high levels of academic success, whereas schools with populations exceeding 2000 students show worse performance. It can be surmised that in large schools (2000-5000), it's easier for underperformance to go unnoticed, leading to poor scores and students who have not received the specialized attention they may need. 

The final category analyzed was the school type. Inarguably, Charter schools outperformed District schools, but I do not believe that these results imply that Charter schools are inherently better, or that we should convert our entire district into Charter schools. The key here is to recognize that all Charter schools in our district have a population size under 2000 students. In order to improve the performance of District schools, thus making them comparable to the success of Charters, we must reduce school sizes in order to better serve each student in attendance. This can be done by redistricting or building a new school. Additionally, I would recommend studying further into the nuances of curriculum, class sizes, and additional resources like access to tutoring, ESL, and Special Ed offerings. Charters do not always follow the same curriculum, teaching styles, or inclusion metrics as District schools, thus resulting in false equivilency, when looking beyond the high-level snapshots we addressed today. 

# References:

I was able to complete this project by referring back to previous lessons.
