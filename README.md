You can go here to view the paper I worked on with Ankita Posam, Ethan Broder, Mary Kate Whelan, and Bryce Coggin, where we predicted NBA salaries in future years given there performance statistics & salaries from previous years:
https://jdavidpeery.github.io/PredictingNBASalaries/STOR320-Final-Project-3.html

The slides for the presentation we did for our project can be found here: 
https://docs.google.com/presentation/d/1s9UVLwzT22zpDHXNWnomd2XvysbJuVPNAy2NBy5LQO8/edit?usp=sharing

When players enter the NBA draft, most sign contracts that last two years. After those two years, they can re-sign a contract for the same team or switch to a different team. We models that predict what a player will be payed in that third year and the probability that they will switch teams from their second to third year based on their performance statistics and salaries from their first two years in the NBA. We web-scraped the salary data from https://www.basketball-reference.com and the performance statistics from https://basketball.realgm.com and joined the two datasets to make predictions. We predicted whether a player would switch teams with a logistic model and predicted their salary in the third year with a linear model. 
