# Data-Exploration-with-R
Problem 1. FiveThirtyEight, a data journalism site devoted to politics, sports, science, economics,
and culture, recently published a series of articles on gun deaths in America. Gun violence in the
United States is a significant political issue, and while reducing gun deaths is a noble goal, we must first
understand the causes and patterns in gun violence in order to craft appropriate policies. As part of the
project, FiveThirtyEight collected data from the Centers for Disease Control and Prevention, as well as
other governmental agencies and non-profits, on all gun deaths in the United States from 2012-2014.You
can find this dataset, called ”gun deaths.csv”, on blackboard.
(a) Generate a data frame that summarizes the number of gun deaths per month. Print the data
frame as a formatted kable() table.
(b) Generate a bar chart with labels on the x-axis. That is, each month should be labeled “Jan”,
“Feb”, “Mar” and etc.
(c) Generate a bar chart that identifies the number of gun deaths associated with each type of intent
cause of death. The bars should be sorted from highest to lowest values.
(d) Generate a boxplot visualizing the age of gun death victims, by sex. Print the average age of
female gun death victims.
Answer the following questions. Generate appropriate figures/tables to support your conclusions.
(e) How many white males with at least a high school education were killed by guns in 2012?
(f) Which season of the year has the most gun deaths? Assume that
– Winter = January - March
– Spring = April - June
– Summer = July - September
– Fall = October - December
– Hint: You need to convert a continuous variable into a categorical variable.
(g) Are whites who are killed by guns more likely to die because of suicide or homicide? How does
this compare to blacks and Hispanics?
(h) Are police-involved gun deaths significantly different from other gun deaths? Assess the relationship between police involvement and other variables.

Problem 2. Read the “weightLoss.csv” file into R.
(a) Rename the 1st column to “id”; the 3rd to the 5th columns respectively to “WeightLoss month1”, “WeightLoss month2”, and “WeightLoss month3”; and the 6th to the 8th
columns to “SelfEsteem month1”, “SelfEsteem month2”, “SelfEsteem month3”, respectively.
(b) Use the melt() function from the “Reshape2” package to reshape the dataset based on the
WeightLoss month variables into a single column. Use “id” and “group” as the “id variables”.
Let’s call this reshaped data frame “wl.data”.
(c) Rename the 3rd and 4th columns of wl.data to “WeightLoss Month” and “WeightLoss”.
(d) This time use the melt() function to reshape the data based on “SelfEsteem month” variables.
Call this dataset “we.data”. Rename the 3rd and 4th columns of we.data to “SelfEsteem Month”
and “SelfEsteem Score”.
(e) Combine the two datasets “wl.data” and “we.data” and call the new dataset as “data.long”.
Make sure each column is repeated once.
(f) Use the Weight Loss (pounds) as a categorical data and get the weight loss frequencies by
groups.
(k) How do you interpret the results provided in the graphs that you have generated. Please briefly
explain your findings from these graphs.
(l) Add a new variable to the long.data, with the subjects’s weight in kilograms (kg) (1 kg = 2.204
pounds).
(i) Generate similar scatter plots for “Weight Loss vs Self-Esteem - Month 2” and “Weight Loss vs
Self-Esteem - Month 3”.
(j) Write the R code that generates the following boxplot (Use ggplot() function)
(k) How do you interpret the results provided in the graphs that you have generated. Please briefly
explain your findings from these graphs.
(l) Add a new variable to the long.data, with the subjects’s weight in kilograms (kg) (1 kg = 2.204
pounds).
