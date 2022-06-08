# Lending Club Case Study by Harsha and Gokul
> An analysis of lending data to find patterns using univariate and bivariate analysis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
The goal of this project is to identify key factors / patterns in the lending data 
which can be used to assess the risk for lending future loans.
The dataset used can be found as part of the repository (loan.csv)


## Conclusions
  1. If loan term is 60 months then it has 25% average who default on loans as compared to loan term of 36 months which has 11% average who default on loans.
  2. Among the subgrades too of lower Grades A to D - bad loan % increments in a consistent manner between the sub grades in each grade.Grades E to G already determined as higher risks.
  3. Those who have high income are less likely to default on loans. Income>82000 have 11% average of bad loans. Whereas those who have very low income are more likely to default on loans. Income <=40000 have 18% average of bad loans.
  4. Those who have annual income as not verified have 13% average of bad loans whereas those who have annual income as verified have 17% average of bad loans. Also in each annual income category, the impact of income verification status seems strange. Those who have annual income verified or source verified have higher bad loan average than those who have annual income as not verified.
  5. Those who are approved loan for small business are more likely to default on loans with an average of 27%. And those who are approved loans for purpose such as major purchase, wedding, car or credit card are least likely to default on loans with an average of around 10 to 11%. Renewable energy and Education follow as top reasons in terms of bad loans % while Debt Consolidation is the biggest reason interms of bad loan count.
  6. Bad loan % increases steadily as the interest rate increases.
  7. Those who have public record bankrupt record are more likely to default on loans with an average of 22%.
  8. Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit. Plot reveals that bad loan % increases steadily as the Revolving line utilization rate increases.
  9. Among the employee length, applicants with 0 years of exp are having higher probability of bad loans that is 25%. When grouped with loan amount we can also observe large amount loans are performing badly across all employee lengths. Also in 10+ category the variance is significant.
  10. Zip Codes 301-400 and 900-901 have higher bad loan % as compared to other zip codes groups.
  11. Candidate with a home ownership of OTHER and from a zip group of 801-900 have a 40% probability of bad loans.
  12. 'CA' is one of the worst performing states in terms of number of bad loans. And 'NE' has the highest bad loan% (60%).


## Technologies Used
Following python libraries have been used
- pandas
- plotly
- matplotlib
- numpy
- seaborn


## Contact
Created by [@gklsndr] - feel free to contact me!
