# Personal Loan Campaign

Designed the loan campaign for converting the existing customers to liability customers by building a classification model that identifies the existing customers that are more likely to buy a loan. 

## Context

This case is about a bank (TheraBank) whose management wants to explore ways of converting its  liability  customers  to  personal  loan  customers  (while  retaining  them  as  depositors).  A campaign that the bank ran last year for liability customers showed a healthy conversion rate of over  9% success.  This  has  encouraged  the  retail  marketing  department  to  devise  campaigns with better target marketing to increase the success ratio with a minimal budget. 

## Data

The dataset contains  data  on  5000  customers.  The  data  include  customer  demographic information (age, income, etc.), the customer's relationship with the bank (mortgage, securities account,  etc.),  and the  customer  response to  the  last  personal  loan  campaign  (Personal  Loan). Among these 5000 customers, only 480 (= 9.6%) accepted the personal loan that was offered to them in the earlier campaign.

## Model Performance

Model performance on recall: 85.9%. The metric measures the True Positive rate (how accurately the model can identify relevant data). Recall is key; we want to decrease false negatives because the bank wants more customers to take the loan.

## Built with

- [Scikit-learn](https://scikit-learn.org/) - Simple and efficient tools for predictive data analysis.
- [NumPy](https://numpy.org/) - A library adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- [Pandas](https://pandas.pydata.org/) - A data analysis and manipulation library.
- [Matplotlib](https://matplotlib.org/) - A comprehensive library for creating static, animated, and interactive visualizations in Python.
- [Yellowbrick](https://www.scikit-yb.org/) - A suite of visual analysis and diagnostic tools designed to facilitate machine learning with scikit-learn.
