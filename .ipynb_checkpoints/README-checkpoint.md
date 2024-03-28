# Machine_Learning_Trading_bot

##Base Model:

![alt text](base.png)

The base model predicts higher returns than the actual retuns.

## Step 1: Tune the training algorithm by adjusting the size of the training dataset.
To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing the training window? I decresed the trainning perios to 2 months and the and then increased it to 7. The results show that a shorter trainning period predicts actual returns closer as seen in these graphs: 

![alt text](2months.png)

![alt text](7month.png)

##Step 2: Tune the trading algorithm by adjusting the SMA input features. What impact resulted from increasing or decreasing either or both of the SMA windows?

SMA1
short_window = 7
long_window = 90
![alt text](sma1.png)

SMA2
short_window = 2
long_window = 110
![alt text](SMA2.png)


Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?
Logistic regression Model
![alt text](lr.png)

Resources
Berkeley Fintech Bootcamp Class Materials
ASKBCS LEarning 3/28/24
