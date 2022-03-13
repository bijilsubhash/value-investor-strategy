# Value Investor
Trading strategy built using bollinger bands for 8 publicly traded securities.

## **Price forecasting**
Closing price were forecasted using an LSTM architecture with optimized learning rate, found using TensorFlow [LearningRateScheduler](https://medium.com/@bijil.subhash/deep-learning-how-to-pick-optimal-learning-rate-using-tensorflow-2-x-af278cadbedb "LearningRateScheduler")
![image](https://github.com/bijilsubhash/value-investor-strategy/blob/master/prediction.jpg)

## **Training result**

![image](https://github.com/bijilsubhash/value-investor-strategy/blob/master/training_loss.jpg)

## **Trading strategy**

Using bollinger bands,  a buy position will open when the price hits the lower band and sell when the price hits the upper band. In the example below, highest return of $57662 was reported for the following settings:
- Simple moving average period - 20
- Bollinger band period - 30

![image](https://github.com/bijilsubhash/value-investor-strategy/blob/master/trading_strategy.jpg)

## File Descriptions
- **[daily strategy](https://github.com/bijilsubhash/value-investor-strategy/tree/master/daily%20strategy "daily strategy")**: contains notebook with daily strategies
- **[weekly strategy](https://github.com/bijilsubhash/value-investor-strategy/tree/master/weekly%20strategy "weekly strategy")**: contains notebook with weekly strategies
- **[monthly strategy](https://github.com/bijilsubhash/value-investor-strategy/tree/master/monthly%20strategy "monthly strategy")**: contains notebook with monthly strategies
## Technologies Used
- TensorFlow
- Pandas
- Numpy
- Matplolib
- Sklearn
