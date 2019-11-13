# Prosper Loan Data Exploration


# Dataset
The data consist of information regarding 113,937 loans with 81 variables. The loan listings are from late 2005 - 2014 with various characteristics of those loans. My selected data consisted of 8 discrete variables and 6 continuous variables. The Loan Origination Quarter was the critical feature base line. I was most interested to see the Loan Origination Quarter and how the market loan company's data and find insights related to the borrowers, the loan they lend and the grade represents the borrower's credit score, annual income, and among other things.



Loan Data from Prosper: Last updated 03/11/2014.

    • Data url: https://docs.google.com/document/d/1qEcwltBMlRYZT-l699-71TzInWfk4W9q5rTCSvDVMpc/pub?embedded=true
    
    
# Summary of Findings


In the exploration, there was a strong positive relationship between credit score and loan amount. The larger the loan, the higher the credit score. I saw a negative relationship between loan amount and interest rate. The larger the loan, the lower the interest rate on average, mostly because the borrowers have higher credit scores. Most of the borrowers with lower monthly income have higher debt to income ratio due to mostly they borrow more money. From Q4 2005, Prosper took 3 years for listing levels to reach the Q2 2008. Then, there was a big dip from Q4 2008 – 2009, even until 2010. This time period concurs with the fall of the market in Fall 2008 with the huge effect by the collapse of the major investment firm Lehman Brothers and, the succeeding fallout in the global financial system. It appears the Prosper business was susceptible to the global economic crisis. 


Looking at the credit score over time, it was clear that Prosper changed its policies from one that had no minimum credit score to one that had very strict lower limits. That lower limit rose over time from 520 in Q2 2007 to 600 in Q3 2009 (after the credit crisis) to 640 most recently. Debt consolidation is the highest number of loans and with the largest loan amount. There was a strong positive relationship between term and loan amount. The longer the term, the larger the loan amount. I also observed the self-employed is the second highest with loan amount (not accounting the "Other".) Since personal loans for self-employed are harder to get, borrowers must have extra qualification to convince the lender to approve a request for money. 


The credit scores distinguished borrowers by worthiness when looking at the loan amounts vs interest rate. The majority of the loans are with 3-year term and they are mostly the current and completed loans. Per loan status, it demonstrated the majority of the completed and current loans are the debt consolidations. Prior to 2008, it looks like Prosper did not capture the loan category, and debt consolidation dominated the category subsequently every year. 


I saw the prosper struggle initially with their first few years of loans. But their business grew very quickly after the downturn and market fall in 2009. Their main loan exposures were in debt consolidation and I’m sure the low interest rate environment has helped the supply of lenders looking for yield. The influence of borrower interest rate and term in over time was clear when Prosper changed its policies and improved the overall risk profile of its loans. It shows a correlation between interest rate and terms (36 and 60) from year 2012 to 2014 where the 36 term is not necessarily more expensive. Also, the income ranges uptick in loans in 2012-2013. It grew initially in 50k-75k, 75k-100k, and 100k+.




# Key Insights for Presentation 


For the presentation, I focus on the loan origination quarter to understand the conditions of number of loans. I start by introducing the loan origination quarter variable, followed by the loan amount and interest rate distribution, then plot the transformed count and histogram plot. 


Afterwards, I introduce each of the categorical and numeric variables. Most of my analysis efforts on re-ordering default factors levels to make more intuitive sense when displayed in a histogram. Some categorical plots I have to re-order by value counts and in chronological order. I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.



# Feedback from someone

• What relationships do you notice?
Loan requirements before and after the crash were at opposite ends. Prosper was stricter after the crash with regards to loan qualification and credit scores.

• What do you think is the main take away from the slide deck?
The financial crisis caused many lenders to re-evaluate the way they approved their loans. They required more documentation and better credit scores and improved debt to income ratios. 

• Is there anything that you don’t understand from the plots? No, the explanation after each slide made it easy to understand.



# Resources:
https://knowledge.udacity.com

https://pbpython.com/categorical-encoding.html

https://stackoverflow.com/questions/50319614/count-plot-with-stacked-bars-per-hue

https://stackoverflow.com/search?q=value+error+max+arg+is+an+empty+sequence

https://stackoverflow.com/search?q=move-legend-outside-figure

https://jakevdp.github.io/PythonDataScienceHandbook/04.06-customizing-legends.html
