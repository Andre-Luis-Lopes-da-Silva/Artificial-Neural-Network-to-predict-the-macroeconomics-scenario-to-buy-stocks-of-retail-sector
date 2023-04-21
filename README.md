# Artificial-Neural-Network-to-predict-the-macroeconomics-scenario-to-buy-stocks-of-retail-sector

DOI: 10.6084/m9.figshare.22674865

INTRODUCTION 

An artificial neural network is an information-processing paradigm that is inspired by the way biological nervous systems, such as the brain. The key element of this paradigm is the novel structure of the information processing system. It is composed of a large number of highly interconnected processing elements (neurons) working in unison to solve specific problems.

The retail sector consists of all companies that sell goods and services to consumers and macroeconomic scenarios are multi-year projections of economic variables. The retail sector is sensitive to macroeconomic variations, especially when there are low gross domestic product (GDP) projections, high interest rates and high inflation rates.

Therefore, the aim of this study was to establish a model using artificial neural network to predict the macroeconomics scenario to buy or sell stocks of retail sector.

MACROECONOMIC INDICATORS AND RETAIL STOCKS

Lojas Renner (LREN3) was chosen to be a representative stock of the retail sector of companies traded on B3 (brazilian stock exchange).  The indices Broad National Consumer Price Index (IPCA), Special System for Settlement and Custody (selic), Central Bank Economic Activity Index (IBC-Br), Broad Retail Trade Confidence Index (ICOM), Future Expectations Index, Dollar (exchange), Consumer Stock Index (ICON) and Ibovespa Index (IBOV) were initially analysed by correlation. See the file (correlação_repository.ipynb). Data from during 10 years were used (2011-2021). 

STOCK TREND

The trend of the stock was considered only bullish or bearish (binary classification). When the trend was sideway and followed by a uptrend, the trend was considered uptrend because it would be a good opportunite to buy. This same reasoning was used when there was a lateralization followed by a bearish trend.

CONCLUSIONS

The model needs to be improvement, the metrics obtained were: 

Accuracy .:  0.78

Precision :  0.80

Recall ...:  0.91

F1 Score .:  0.72
