# Introduction
The reason i created these excel projects was to better understand how excel works and to become better at it. My goal is to become a Data Analyst and since excel is a very useful tool for this career, i decided to watch videos and do projects. So i learnt how to do data cleaning, how to use functions and formulas, how to create pivot tables, charts, dashboards, etc. One of the videos that i watched in order to create on of the projects, was Alex's the Analyst that is called "Full Project in Excel", on Youtube. 
So a big thank you to that person.

# Bike_Sales Project
In this project we see demographic information about the bike purchasers. Here are some of the steps that occurred in this project(workingsheet):

✦ Data cleaning (removed duplicates, replaced data in order to make them more readable, decreased decimals)

✦ Creating a new column called "age brackets", (while using IF function ☛ =IF(L2>55;"Old";IF(L2>=31;"middle age";IF(L2<31;"Adolescent";"Invalid"))), L2 stands for a cell in the "Age" column and what we are saying is that if this person with that age is more than 55 years old then call them "Old", if they are less than 31 call them "Adolescent" and anyone else that doesn't fall on those conditions/value if false, call them "Invalid"). The porpuse of this added column was to create groups of ages,for the pivot tables.

✦ Creating pivot tables: The first pivot table gives us information about the average income of someone who either purchased a bike or not. We wanna see if income plays a role in bike purchasement. As a value(area) we picked the income and we changed it from sum to average, in the row area we positioned the gender. Next we picked a chart to visualize the pivot table that we had created and as a result we see that the people who had more income did purchase a bike.
The second pivot table/chart contains information about commute distance and how many people base on that purchased a bike or didnt purchase. As a result, we see that the distance from work is an important factor. More miles equals to less purchases. 
The third pivot table/chart shows which group of age buys more bikes. And middle age group comes first when it comes to bike purchasement and then the eldest people follow and the adolescent group comes last.

✦ Building a Dashboard: coping and pasting the charts in a new sheet. Then for the final touches we created a dashboard title, we align the charts and we inserted slicers to filter the tables. And with the help of those filters(education, marital status and region) we can choose what information we wanna see.
