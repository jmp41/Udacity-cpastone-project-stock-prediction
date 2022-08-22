# Udacity-cpastone-project-stock-prediction
This project is for Udacity AWS Machine Learning Capstone Project.
# Files and Folders in this Repo
proposal.pdf is the Capstone Project Proposal
report.pdf is the Capstone Project Report
capstone.ipynb is the main code jupyter notebook for this project. All related work presented in the report is edited in this file.

# Stock Price Prediction Project
Stock price prediction is always a challenging but attracting task. Various tech- niques have been tried to conquer the market, but few succeed. The key compo- nent for stock price prediction task is to fit a conditional distribution function of stock returns in the context of historical data. And then input updated informa- tion to make a prediction of stock’s return and risk. Based on estimated return and risk, we also need to utilize portfolio optimization to allocate resources on making investment decisions.
The difficulty of such tasks mostly lies in the low signal-to-noise-ratio (SNR) of stock market. Day-by-day transaction in the busy market generates huge amount of data, which is prefect for modern machine learning method. However, it usually takes great effort to extract the valuable part of such data.
In this project, I created a Multi-Precision-Layer (MLP) model with a state- of-art technique, the DPP optimization layer1, for stock price prediction. The trained model uses Microsoft open source qlib Alpha158 dataset2.

# Dataset
qlib Alpha158

# Model Training
Linear Model
MLP model
Optimization MLP model

# Result
| Name               | Linear Model | MLP Model | Opt Model |   | SH000903  |
|--------------------|--------------|-----------|-----------|---|-----------|
| Mean               | -0.000208    | -0.000078 | 0.000021  |   | 0.000383  |
| Std                | 0.003113     | 0.003158  | 0.006127  |   | 0.012031  |
| Annualized_return  | -0.049584    | -0.018501 | 0.005014  |   | 0.091168  |
| Information_ratio  | -1.032555    | -0.379776 | 0.05304   |   | 0.491206  |
| Max_drawdown       | -0.17253     | -0.10017  | -0.126793 |   | -0.347247 |




