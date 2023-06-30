# Stock-price-prediction

Project Goal: The goal is to develop a user-friendly interface for the ML model that allows investors to input their preferences and receive similar predictions and recommendations. 

Elaboration of the Goal: There are four main things one must notice while they are preparing the model. Firstly, the interface that will be developed must be easy to navigate and use. Secondly, there must be scope for the person to input their preferences in the interface. Thirdly, the output of the model must be easily readable in the interface. Finally, there must be a feedback mechanism in the interface. This feedback must be relayed back to the model. 

       
          
About the Project Topic: 

Important formulae regarding Financial Accounting Foundations: 

1. Assets = Liability + Equity
2. Revenue - Expenses = Net Income
3. Return On Equity = Net Income/ Equity.
4. Return on Equity = profit margin * asset turnover * asset to equity 
5. Debt Ratio = total liabilities/ total asset
6. Operating cycle = Number of days between purchase and sale + Number of days from sale till cash collection
7. Number of day's sales in inventory = Inventory/ Average daily cost of sales
8. Average Collection period = Accounts recievable/ Average daily sales
9. PE Ratio = Price/ Earnings

Source: Linkedin Course: Financial Accounting foundations 


Introduction:
The aim of this project was to develop a machine learning model for predicting stock prices based on historical data. The dataset used for this project spanned a period of five years and included various features such as Date, Open, High, Low, Close, Adj Close, and Volume.

Data Exploration and Preprocessing:
The project began with data exploration, where statistical analysis and visualizations were used to gain insights into the dataset. Key visualizations included line plots of stock prices over time, box plots to identify outliers, and correlation matrices to examine feature relationships. Data preprocessing techniques were applied to handle missing values, normalize numerical features, and encode categorical variables.

Feature Engineering:
Feature engineering is a crucial step in building predictive models. The dataset was enriched by creating additional features such as moving averages (MA), relative strength index (RSI), price range, and average true range (ATR). These features provided valuable insights into trends, volatility, and momentum, enabling the model to capture relevant patterns.

Data Splitting:
To assess the model's performance accurately, the dataset was split into training, validation, and testing sets. The common practice of an 80-10-10 split was employed, where 80% of the data was used for training, 10% for validation, and 10% for testing.

Model Selection and Training:
For simplicity and ease of implementation, a linear regression model was chosen as the prediction model. The model was trained using the training data, where the input features were the Open, High, Low, and Volume columns, and the target variable was the Close column representing the stock price. The model was fitted to the training data using the LinearRegression algorithm.

Model Evaluation:
The trained model was evaluated using the validation dataset. The predictions were compared against the actual stock prices, and the mean squared error (MSE) was calculated as an evaluation metric. The MSE measured the average squared difference between the predicted and actual values. A lower MSE indicated better performance, and in this project, the obtained MSE value demonstrated the model's accuracy in predicting stock prices.

Prediction on New Data:
Finally, the trained model was used to make predictions on new, unseen data. The new data was prepared in a similar format as the training data, including the Open, High, Low, and Volume features. The model was then applied to the new data, and the predicted stock prices were obtained.

Vanishing gradient problem: LSTM is designed to address the vanishing gradient problem, which can occur in deep learning models that use recurrent connections. The problem arises when the gradient signal becomes too small to be useful for learning, causing the model to converge slowly or not at all. LSTM uses gates to control the flow of information, which helps to prevent the gradient signal from vanishing or exploding.

Applications: LSTM is commonly used in a wide range of applications, including natural language processing, speech recognition, image captioning, and time series analysis.
