# pandas_challenge


Trends in school data - Pandas Challenge homework

Sam Van de Velde


The file contains data from 15 schools with a total budget of $24.6 million. Both charter and district schools are included.

-	Surprisingly, the top scoring schools based on total passing percentage are schools that have the smallest budget per student. 

-	As expected, small and medium sized schools (up to 2000 students) perform better than large schools. We have no data on number of students per teacher, but this is probably because students are better guided through the coursework in smaller schools.

-	Charter schools perform far better than District schools (overall passing % is 90.4 vs. 53.6). Another metric we could calculate is the average size of charter schools versus public schools.


Taken together, based on student performance, we can conclude that large schools and district schools are underperforming compared to small schools and charter schools. Larger school budgets per student on average don’t result in better outcomes for students.



I imported Numpy as a dependency to extract Reading and Math scores with the grade as conditional using the np.where method.