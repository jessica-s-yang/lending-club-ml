LENDING CLUB LOAN PORTFOLIO & DATA SCIENCE
-

Provided Data: 

gzipped csvs
- 2 yrs
- quarterly data on Lending Club
- issued (date, amount, term, interest rate)
- customer info (such as employment, annual income, FICO)
- loan status. 
data dictionary 
- located in docs/ directory

Goal:  Inform investors on the best loans to invest in. As an investor, I want to know which loans are the best to invest in with $100, or how can I build a strong loan portfolio with $100. 

Solution:
Iteration 1 - Trained a model that can predict whether a loan should be included in the portfolio or not using the most recent dataset provided (2017, Q4). The current state shows at best 85% test accuracy. There is more work to be done. 

Run Instructions:
0. Create virtual env with the requirements.txt file provided.
1. Run eda.ipynb to better understand our dataset
2. Run feature_engineering.ipynb to get your cleaned data for train/test data
3. Run modeling.ipynb to see the outcomes of several basic supervised learning algorithms provided by scikitlearn.
4. Upsampling, Undersample, and SMOTE were attempted to handle the major class imbalance. No improvements there.

Future Work:
1. Explore XGboost, Neural Nets
2. Increase training/test data
3. Consider the value of former data sets

