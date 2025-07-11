
Using LSTM to Predict 7 Tech Stock Price


##Frame work
initial stage for model building for the 7 tech stock prediction
Prerequisite: separate the stocks by symbols, loop all the symbols for following steps
1. Get the data
2. Do the cleaning
3. Calculation the stock indicators
4. Do the correlation analysis,
5. Do the Random Forest
6. Do the RFE
7. Do the Permutation Importance check
8. Combine all the common and drop the uncommon the few uncommon
9. Do the scaling
10. Set up the LSTM model
11. Test the parameters of the model by using keras tuner and check the validation loss of each epoch
12. Determine the parameters
13. Split the data to 70/30 chronologically
14. Train the model and check the validation loss of each epoch
- using moving window logic, actual week 1,2,3,4 to predict week 5, then include week 2,3,4,5 to predict week 6
15. Track the validation loss
16. Do the back testing
17. Track the model performance
18. Do the prediction if the model is OK
19. Save model, features, scalers for each stock
  
Weekly/ Bi- weekly Operation
1. Get the data
2. Do the cleaning
3. Calculation the stock indicators
4. Do the scaling
5. Use the most recent data for pre-training
6. Track the validation
7. Do the prediction
