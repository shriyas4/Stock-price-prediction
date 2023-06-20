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


LSTM Model
Memory Cell: LSTM uses a memory cell to store and process information over time. The memory cell has a self-loop that allows it to maintain its state and selectively update it using input and output gates.

Input gate: An input gate is used to regulate the amount of new information that is fed into the memory cell. It is controlled by a sigmoid function, which decides which parts of the input to let in.

Forget gate: The forget gate is used to selectively remove information from the memory cell. It is controlled by another sigmoid function, which decides which parts of the memory cell to forget.

Output gate: The output gate regulates the amount of information that is output from the memory cell. It is controlled by a third sigmoid function, which decides which parts of the memory cell to use in the output.

Backpropagation through time: LSTM uses backpropagation through time (BPTT) to learn from sequential data. This involves calculating the gradient of the loss function with respect to the parameters of the model at each time step and propagating it back through time to update the model parameters.

Vanishing gradient problem: LSTM is designed to address the vanishing gradient problem, which can occur in deep learning models that use recurrent connections. The problem arises when the gradient signal becomes too small to be useful for learning, causing the model to converge slowly or not at all. LSTM uses gates to control the flow of information, which helps to prevent the gradient signal from vanishing or exploding.

Applications: LSTM is commonly used in a wide range of applications, including natural language processing, speech recognition, image captioning, and time series analysis.
