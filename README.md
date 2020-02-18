## Lending Club: Loan Pay off Prediction

In this project, I worked with financial lending data from Lending Club. Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. You can read more about their marketplace here. Lending Club evaluates each borrower's credit score using past historical data (and their own data science process!) and assign an interest rate to the borrower. The interest rate is the percent in addition to the requested loan amount the borrower has to pay back. A higher interest rate means that the borrower is riskier and more unlikely to pay back the loan while a lower interest rate means that the borrower has a good credit history is more likely to pay back the loan. The interest rates range from 5.32% all the way to 30.99% and each borrower is given a grade according to the interest rate they were assigned. If the borrower accepts the interest rate, then the loan is listed on the Lending Club marketplace.

The approved loans datasets contain information on current loans, completed loans, and defaulted loans. We are going to investigate:

- Can we build a machine learning model that can accurately predict if a borrower will pay off their loan on time or not?

### Summary of Results
Using the random forest algorithm significantly increased our TPR and reduced our FPR to 16%. For a conservative investor, this means that they make money as long as the interest rate is high enough to offset the losses from 16% of borrowers defaulting, and that the pool of 85% of borrowers is large enough to make enough interest money to offset the losses.

To view the code and graphs accurately, please click on __[this link](https://nbviewer.jupyter.org/github/phtelang/Lending-Club---Loan-Pay-off-Prediction/blob/master/Lending%20Club%20-%20Loan%20Pay%20off%20Prediction.ipynb) as some of the Plotly graphs are not displayed directly on Github.

### Installation
- Download the source csv file on your local folder.
- Download the .ipynb (Jupyter file) and place it in the same folder as the source files.
- Install the requirements using pip install -r requirements.txt. (Make sure you use Python 3.)
