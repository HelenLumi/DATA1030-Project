### Predicting S&P 500 Return With Firm Characteristics and Macroeconomic Data

In this project, we address the challenge of measuring empirical asset risk premia inspired by the paper of Gu, Kelly and Xiu (2020). We aim to understand and explain equity return variations using fundamental and macroeconomic factors from empirical data, and our goal is to predict the S&P 500 return from the value-weighted return of individual stocks. The fundamental factors are constructed from 94 firm characteristics data, obtained from Prof. Dacheng Xiu’s website [https://dachxiu.chicagobooth.edu/]. The data file is large so we include the download link here. We also construct eight macroeconomic predictors following the definitions by Welch and Goyal (2008, RFS). The data are available on Prof Goyal's website, including dividend-price ratio (dp), earnings-price ratio (ep), book-to-market ratio (bm), net equity expansion (ntis), Treasury-bill rate (tbl), term spread (tms), default spread (dfy), and stock variance (svar).

The project is built in Python 3.10.5 and the repository organization is as follows:

1. data/ - Stores raw data files
2. figures/ - Stores all visualizations; from EDA to model result comparisons
3. results/ - Trained models
4. report/ - Reports on development pipeline, methodology, and model results.
5. src/ - This directory contains all the code for: data wrangling, EDA and feature engineering in midterm_code.ipynb; group based splitting, preprocessing and model development, model evaluations, result visualiztion and feature importances in final_code.ipynb.

**Check file environment.yml for complete configuration and package dependencies*

**References**
[1] Gu, Shihao and Kelly, Bryan T. and Xiu, Dacheng, Empirical Asset Pricing via Machine Learning (2020). Chicago Booth Research Paper No. 18-04; 31st Australasian Finance and Banking Conference 2018; Yale ICF Working Paper No. 2018-09. Available at SSRN 
[2] Welch, Ivo, and Amit Goyal, A Comprehensive Look at The Empirical Performance of Equity Premium Prediction (2008). Review of Financial Studies 21, 1455–1508.
[3] Github Repository: https://github.com/hrbzkm98/ml-research/tree/master
