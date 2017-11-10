# Tableau-Projects
This repository contains the analysis and visualizations I have created in Tableau.

### Prosper Loan Data Visualization
#### About
Prosper is a peer-to-peer lending platform that aims to connect people who need money with those people who have the money to invest. In this data analysis project, I have explored the Prosper dataset and used Tableau to create my visualizations.

#### Dataset
The Prosper loan data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset and data-dictionary can be found on below links.
- [Prosper Loan Dataset](https://raw.githubusercontent.com/jubins/Tableau-Projects/master/ProsperLoanData/data/prosperLoanData.csv)
- [Prosper Loan Data - VariableDefinitions](https://github.com/jubins/Tableau-Projects/blob/master/ProsperLoanData/data/ProsperLoanData-VariableDefinitions.csv)

#### Summary
In peer-to-peer lending, there are three main stakeholders: borrowers, lenders and the company itself. In my Tableau story I have done exploration on the relationship between these people, what affects borrowers Prosper Score and who defaults the most. First, I have done a time series analysis ranging from year 2007 – 2014 about the number of loans taken by borrowers, the amount of their loans and how their ProsperScore got affected in this duration. I noticed that since 2009, the loan business increased and climbed up quickly since 2013 and then dropped down at beginning of 2014 while the borrower credit scores constantly dropping over this time and some states having default rates more than 30%.
Then I have explored the defaulters, reason for defaults, and reason for borrowers to take loan, I found out that the people with $0 income have highest default rates and most defaulters invest in the loan type ‘D’. Breaking down to occupation-wise, an interesting pattern was found that the college student group which are enrolled in higher grade studies have more loans, higher borrower and default rates. While this made sense with $0 income, the sophomore students were the top defaulters and having lower number of loans. Lastly, I have looked at the incomes and losses on different loan ratings – the ‘HR’ loan rating had the highest loss even though this type of loan is given to most credit-worthy borrowers. However, looking at the net principal returns over the time I noticed loans C&D had highest losses than other loans and are most risky.

- You can view final version of my [Prosper Loan Data Story](https://public.tableau.com/profile/jubin.soni#!/vizhome/ProsperLoanData_7/ProsperLoanStory-Version2) by clicking on image below:

[![visualization image](https://github.com/jubins/Tableau-Projects/blob/master/ProsperLoanData/data/pld_screenshot.png)](https://public.tableau.com/profile/jubin.soni#!/vizhome/ProsperLoanData_7/ProsperLoanStory-Version2)

- Version 1 of my Tableau story can be viewed by clicking on below image:

[![visualization image](https://github.com/jubins/Tableau-Projects/blob/master/ProsperLoanData/data/pld_screenshot_v1.png)](https://public.tableau.com/profile/jubin.soni#!/vizhome/ProsperLoanData_Version1/ProsperLoanStory-Version1)


## References
- [Prosper About.](https://www.prosper.com/plp/about/contact-us/)
- [Prosper Loan Data Project on Kaggle.](https://www.kaggle.com/jschnessl/prosperloans)
- [Repo on the same project.](https://github.com/grace-pehl/ProsperLoan) 
- [MIT page showing stats usage on same project.](http://courses.media.mit.edu/2008fall/mas622j/Projects/CharlieCocoErnestoMatt/data/)
- [Udacity Tableau Course.](https://www.udacity.com/course/data-visualization-in-tableau--ud1006)
- [Tableau Tutorials.](https://www.tableau.com/learn/training)
- A lot of googling to figure out how to do stuff.