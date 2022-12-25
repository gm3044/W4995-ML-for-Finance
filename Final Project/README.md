
# 
The final project is written as part of the evaluation of the Machine Learning with
Applications in Finance summer course at Columbia University. The portfolio manager is
Ganghua Mei, with an initial $1 million AUM. The investment portfolio is simulated from
June 13, 2022 to July 1, 2022, with a total of 15 trading days.

The portfolio manager developed a three-stage process for portfolio construction:

A. The first stage is to select mid-large cap companies based on fundamental and
technical analysis following Steven Downey (2020).

B. The second stage use neural networks to predict the stock returns in the spirit of
Gu, Kelly and Xiu (2020) and Van Binsbergen, Han and Lopez-Lira (2020).

C. The third stage use predicted returns for mean-variance optimization and select
stocks that maximize the sharpe ratio.


![plot](https://github.com/gm3044/W4995-ML-for-Finance/blob/main/Final%20Project/Daily%20Returns.PNG)
![plot](https://github.com/gm3044/W4995-ML-for-Finance/blob/main/Final%20Project/Cumulative%20Returns.PNG)
![plot](https://github.com/gm3044/W4995-ML-for-Finance/blob/main/Final%20Project/Descriptive%20Statistics.PNG)

# Performances:

1. The average daily return of our portfolio in the investment period is .367% (or 148.5% annually) versus 0.148% (or 39.905% annually).
2. The total cumulative return is 5.57% which is 2.75 times the returns of SP500. Moreover,
3. This portfolio is much less volatile (0.010) than the SP500 (0.018) with a sharpe ratio
of .35.
4. This portfolio has generated excess return over SP500 while the
correlation between our portfolio and SP500 is relatively low: Alpha is 0.003 and beta is 0.488; both are statistically significant at the 10
percent level.
5. This portfolio’s active risk is low (0.01) and with a decent information
ratio (0.276). 


# Replication:

Step0. Download Sharadar Core US Fundamentals Data (SHARADAR_SF1.csv), Sharadar Equity Prices(SHARADAR_SEP.csv)， and Tickers Name（SHARADAR_SF1.csv) from  https://data.nasdaq.com/databases.

Step1. Upload all the csv files into your jupter notebook dictionary.

Step2. Run Final Project_1.

Step3. Run Final Project_2.

Step4. Run Fama_French 5 Factor Model.
