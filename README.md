# Data Visualization or EDA
In this notebook I will walk you through data visualization on the Titanic dataset.

Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. We will be using the Seaborn Library.

1. Identifying the null values (missing values)¶
    First we will check for null values in the data using heatmap with the isnull() method

2. Survival of Male and Female
   ceck for the number of male and female survived ,using count plot.
   outcome: In the overall number of passengers who survived, the majority were females.
   
            It can be approximated that the survival rate of men is around 19% and that of women is around 74%.

4. The number of passengers in the age bracket [20,40] is higher than other age brackets.

5.  what can you infer about how the age of the passengers and whether they were alone or not affects the chances of their survival?
   outcome:
    4.1 People who were alone and survived (age=30) were found to have a higher median age than those who did not survive(age=29).

    4.2 People who were alone and did not survive(age=29) were found to have lowe median age than those who survived(age=30).
    
    4.3 People who were not alone and did not survive (age=27) were found to have higher median age than those who did survive(age=24).
    
    4.4 People who were not alone and survived(age=24) were found to have lower median age than those who did not survive(age=27).

6. what can you say about the impact of fare on the survival dependency differently for all the classes?
   outcome:
   The greater mean fare for class, survived category: who paid more survived with more chances in general for all classes.
   
   In the class "Second", it is found that people who paid higher amount of fare (i.e. >60) haven't survived dominantly in that fare range.
   
8. Correlation:
   outcome:
   From the above heatmap, Identify which of the following is correct?
   
   6.1 features pclass and fare are negatively correlated.
   
   6.2 features alone and adult_male are weakly positively correlated.
   
   6.3 Diagonal features are showing the correlation between themselves and therefore it is 1.
    
