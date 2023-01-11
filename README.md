# DSI_SRP_explore
In this project, we will try to use machine learning and deep learning methods to predict stock returns or bond yields. These studies are primarily concerned with developing algorithmic trading strategies and using machine learning and deep learning techniques to forecast bond yields or stock returns.

## In the **explore** section
* **predictive analysis**: involves using data science methods to estimate the value of a quantify necessary for decision making. This application of machine learning algorithms and by implementing predictive analytics methods over the data collected in the past and historical stock data, companies can chanelise themselves in the direction of rapid growth. 
* **classification system:** require the understanding of data and use a subset of features to classify them. The object would be analyze the stock data and determine whether to "sell, hold, buy" the stock in the next day.
* **sample**: Use the stock data of Apple as an example, this folder explores the stock data in linear methods, tree-based methods, and deep learning methods. Insightful findings will be implemented and continued in this research project.

## In the **quant** section

The experimental results are collected using 453 stocks (comprised of those that were in the S&P company list for all of 2019 and 2020) and 11 Algorithms (Logistic Regression, KNN, SVM, Bayes Theorem, Decision Tree, Random Forest, Bagging Classifier, Gradient Boosting, AdaBoost, CNN, RNN_LSTM). We use the one-step forward forecast of predicting action signals one day at a time and iterate the process 21 times to get the prediction results for 21 days (average number of trading days in a month). 
 
In the first run, 11 algorithms are applied on only stock data. In the second run, 11 algorithms are applied to both stock data and sentiment data. Then we design a table that shows which difference (algorithm or data) matters the most in the domain of prediction performance. 
 
The performance is measured in two dimensions. The first dimension uses the accuracy score (one rate calculated from the confusion matrix, which describes the performance of a classification model by telling how often the classifier is correct). The second dimension uses an equally weighted portfolio simulation. To compute this portfolio, we assume that investors start with 1 million dollars for each stock. If we receive a buy signal, we buy the stock using up all the dollar amount; similarly, if we receive a sell signal, we sell all shares in the account; if we receive a hold signal, we take no action. We then create a stock portfolio by averaging the returns on each of the 453 stocks to calculate the final portfolio stock return. 

