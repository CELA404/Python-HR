This project involves an exploratory data analysis (EDA) on a dataset comprising 8,336 observations, with each observation representing a worker in a specific department.
The key focus areas for investigation are age, gender (every personed identified as a female or a male only in the survey,hence no other outputs for this part) , absent hours, and job title. 
The primary goal is to gain insights into the distribution of total hours of absence within the workforce and identify potential patterns that may emerge from the data.

The analysis will involve examining the distribution of total absence hours across the workforce.
Various statistical measures, such as mean, median, and standard deviation, will be employed to describe the central tendency and spread of the data.
Additionally, visualizations, such as histograms and scatter plots, may be generated to provide a clearer understanding of the data distribution.
The code file includes comments marked with '#' symbols to provide clarity on each step of the analysis.
These comments serve as a guide for the reader, explaining the rationale behind specific decisions or operations performed during the EDA.

It is important to note that the dataset used in this analysis is based on real-world data from a specific context.
However, the analysis is conducted for personal purposes, meaning that the insights gained are not intended for external publication or commercial use.
The primary aim is personal exploration and understanding of patterns within the data.

Key findings:
(Note: The hours of absence are mesured within a year and a shift lasts 8 hours)

i) Although the size of the 'Produce' and 'Processed foods' departments is significanlty  (as a number of
people in the workforce) lower than the other three main departments, the average total hours of absence per
employee are almost identicall. This shows that the average hours of absence per employee is not only
affected by the individual behavior of each employee, but also by the size of the department. A larger
department will have a lower average hours of absence per employee, even if it has a higher total hours of
absence, because it has more employees to share the burden of absence. A smaller department will have a
higher average hours of absence per employee, even if it has a lower total hours of absence, because it has
fewer employees to spread the load of absence. Therefore, when mparing the average hours of absence per
employee across different departments, we need to take into account the number of employees in each
department as well

ii) While the dataset cosnists  of almost the same number of men and women , from the analysis we see that women on average have more absence hours yearly than men do (10% more).

iii) From the final scatter plot we derive that there is a positive correlation between age and absence hours
of a worker. The plot shows us the the older an employee is the more his absence hours are increased .

Conclusion: 
From this EDA the HR department can proceed to specific actions depending on the goals and and the ethics 
of the company
