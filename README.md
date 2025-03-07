# DSE4101_Individual-Project: Forecasting Algorand (ALGO) Volatility - Comparison of GARCH, HAR and SVM-GARCH Hybrid Models  

Luo Xinming (A0240232Y) 

## Motivation 

Earlier in the Group Project, we compared the performance of GARCH(1,1), HAR, Random Forest and 
Long Short-Term Memory in predicting Ethereum price volatility. It was found that HAR gave the overall 
best performance. Following this, this project aims to further explore the performance of the HAR model 
in predicting the volatility of another cryptocurrency, Algorand (ALGO), using GARCH as a benchmark. 
In addition, this project also aims to explore the performance of SVM-GARCH hybrid models, which was 
not done in the group project. ALGO was chosen because it is a widely recognised and used 
cryptocurrency with a market of $2.33B, and its intraday transaction data is available for the purpose of 
this project.  

## Goals 

1. To build at least three models: GARCH, HAR, and SVM-GARCH 
2. To find the best p, q combination in the GARCH model using Box-Jenkins Identification 
3. To find the optimal lag structure in the HAR model  
4. To obtain forecasts for four horizons (1-day, 3-day, 7-day, 30-day) 
5. To compare the models based on MAE, RMSE, R2, QLIKE and VaR 
6. To compare the performance of alternative estimation schemes (Weighted Least Square, Robust 
Regression) against OLS

## Dataset 
The historical intra-day trading data for ALGO can be sourced from Kaggle. The data is available from 
2019-06-21 to 2023-10-08. It includes open, high, low, and close price data. 

## Milestones 
Week 7 (3 Mar - 9 Mar): Proposal submission and Data Pre-processing 
Week 8 (10 Mar - 16 Mar): GARCH development  
Week 9 (17 Mar - 23 Mar): HAR development (with testing of different estimation schemes) 
Week 10 (24 Mar - 30 Mar): SVM-GARCH development 
Week 11 (31 Mar - 6 Apr): Check-in (2nd consultation) 
Week 12 (7 Apr - 11 Apr): Report Write-up and submission  
