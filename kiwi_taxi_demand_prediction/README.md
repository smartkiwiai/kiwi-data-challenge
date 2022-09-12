# kiwi-data-challenge
Kiwi Data Challenge
Problem Definition
 
We have a 8x8 grid shaped city. We have recorded number of times people call taxis from each grid from 2023-04-01 to 2026-03-31. Our goal is to predict how many times taxis are being called from each grid in each day in the next 2 months.
 
The data is synthetic and provided in sparse format.

We have the data for all the days in 3 years except one time when our app was broken and couldn’t collect the data. It was broken between 2024-04-10 and 2024-04-23.
 
 
Data Format
 
train.csv
x: x coordinate of the grid, integer between 0 and 7
y: y coordinate of the grid, integer between 0 and 7
date: date in yyyy-mm-dd format
count: this is our target
 
 
Evaluation

We expect you to send us a submission.csv as the same format as train.csv.  We also want you to provide the code which generates this csv file. Target “count” should be an integer. Evaluation metric is MAE. You will be evaluated based on your score and your code quality. Please don’t hesitate to add the codes or your findings for all the experiments you did.
