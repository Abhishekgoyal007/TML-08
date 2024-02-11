# TML-08
Ps :- Build a model to predict whether a stock's closing price will go up or down compared to the previous day based on its opening, high, low, and volume. Metrics: Accuracy, F1-score.
<br>
<br>
a)Team Details Contact info
<br>
<br>
    Team Name : TML-8
    <br><br>
    Members name : <br>
    1) Abhishek Goyal - 9166403437 <br>
    2) Dheeraj Vishwakarma - 8104430962 <br>
    3) Pratik Vishwakarma - 8169438869 <br>
    <br>
b) Introduction<br><br>
    In today's volatile stock market, predicting price movements is crucial for investors to make informed decisions. This model aims to forecast whether a stock's closing price will         rise or fall compared to the previous day, using key metrics like opening price, high, low, and volume. Leveraging machine learning techniques and historical data, our model provides     valuable insights to guide investment strategies.<br><br>
**Problem Statement** The goal is to develop a binary classification model that predicts whether a stock's closing price will increase (1) or decrease (0) relative to the preceding day       based on its opening, high, low, and volume metrics.<br><br>
**Data and Methodology** We preprocess historical stock data, focusing on relevant features such as opening price, daily high and low, and trading volume. XGBoost, a powerful ensemble        learning algorithm, is employed for modeling due to its effectiveness in classification tasks.<br><br>
**Model Development** The dataset, primarily from Tesla, is split into training and testing sets. Following model training, performance evaluation is conducted using accuracy and F1-         score metrics to assess predictive effectiveness.<br><br>
**Results and Evaluation** Visualizing predicted versus actual labels provides insights into model performance, demonstrating its ability to predict stock price movements accurately.<br><br>
**Conclusion** Our model offers a robust solution for predicting stock price movements, empowering investors with data-driven insights to navigate market uncertainties confidently.
<br>
<br>
c) Dataset Description<br><br>
The provided CSV file contains historical financial market data, likely pertaining to a specific financial instrument such as a stock or index. It includes information for each trading day, spanning multiple columns. The "Date" column denotes the date of the trading day, while the "Open", "High", "Low", and "Close" columns represent the opening, highest, lowest, and closing prices, respectively, of the financial instrument on that particular day. The "Adj Close" column typically signifies the adjusted closing price, which accounts for any corporate actions such as dividends or stock splits. Lastly, the "Volume" column indicates the total volume of trading activity, representing the number of shares or contracts traded during the trading day. This dataset provides valuable insights into the historical price movements and trading activity of the financial instrument, enabling various analyses such as trend identification, volatility assessment, and trading volume analysis.
<br><br>
d. Dataset Split info<br><br>
The dataset comprises historical financial market data for Tesla stock, encompassing opening, highest, lowest, closing, adjusted closing prices, and trading volume, restricted to the first 500 entries. For model training and evaluation, the data undergoes an 80-20 split using the `train_test_split` function from `sklearn.model_selection`, with 80% allocated for training and 20% for testing. This split, governed by a random state of 42, ensures reproducibility and consistency in model evaluation. Consequently, 400 entries are utilized for training, while the remaining 100 entries serve for assessing the model's predictive performance on unseen data, facilitating insights into its generalization capabilities.
<br><br>
e) Approach<br><br>
The approach involves building a predictive model to forecast whether a stock's closing price will increase or decrease compared to the previous day. This is a binary classification task where the dataset is preprocessed to include features such as opening, high, low, and volume, along with a binary label indicating whether the closing price increased (1) or decreased (0) relative to the previous day. The XGBoost algorithm is employed for modeling due to its effectiveness in classification tasks. The dataset is then split into training and testing sets, with 80% of the data used for training and 20% for testing. Model performance is evaluated using accuracy and F1-score metrics, providing insights into the model's predictive capabilities. Additionally, the actual versus predicted labels are visualized to further analyze the model's performance. Overall, the approach emphasizes leveraging machine learning techniques and historical stock data to develop a robust predictive model for guiding investment decisions.
<br><br>
f) Results<br><br>
Accuracy: The accuracy of the model on the test set is calculated to be approximately 0.72, indicating that around 72% of the predictions are correct.
F1-score: The F1-score of the model on the test set is approximately 0.73, providing a balanced measure of precision and recall.
<br><br>
g) Dependencies<br><br>
1. **NumPy:** For array manipulation and mathematical operations.<br>
2. **Pandas:** For data manipulation and analysis using DataFrames.<br>
3. **scikit-learn:** For machine learning algorithms and evaluation metrics.<br>
4. **XGBoost:** For gradient boosting algorithm implementation.<br>
5. **Matplotlib:** For data visualization.<br><br>
h) Performance and Accuracy<br><br>
**Accuracy:** The accuracy of the model on the test set is approximately 72%. This means that around 72% of the predictions made by the model are correct.<br>
**F1-score:** The F1-score of the model on the test set is approximately 73%. The F1-score provides a balance between precision and recall and is particularly useful for imbalanced datasets or binary classification tasks.<br>
Overall, the model demonstrates moderate performance in predicting whether a stock's closing price will increase or decrease compared to the previous day, achieving an accuracy and F1-score of approximately 72% and 73%, respectively.<br><br>
i) F1 Score<br>
The F1-score of the model on the test set is approximately 73%. The F1-score provides a balance between precision and recall and is particularly useful for imbalanced datasets or binary classification<br><br>
j) Novelty Factor
<br><br>
The novelty factor in this approach lies in the combination of features utilized for predicting stock price movements, the adoption of the XGBoost algorithm for modeling, and the use of accuracy and F1-score metrics for evaluation. These elements contribute to a comprehensive and effective approach to address the problem of stock price prediction.<br><br>
k) References<br>
- GeekforGeeks<br>
- StackOverFlow<br>




