# CSE 151B Climate Prediction Competition
Current best: U-Net_LSTM_10years_MAE_MSE_128_dim_64hid  
This repository contains a lot of modifications start from U-Net model, adding LSTM, to tweeking hyperparamter to optimize for best performance.


starter-tempw_adaplr_earlyStop.ipynb contains Simple CNN with adaptive learning rate and early stopping  
Complex U_Net model.ipynb is the second version, which change Simple CNN to U-Net model, this help increase the performance by a bit.  
U_Net_With_ConvLSTM.ipynb implemented LSTM for the feeding input of U-Net, the LSTM in this model contains half a year of memory.  
U-Net_LSTM_10years.ipynb change LSTM memory from half a year to 10 years.  
Lastly, U-Net_LSTM_10years_MAE_MSE_128_dim_64 chang the hidden dimension to 64 with input dimension to 128, this version also have a 0.3MAE and 0.7 MSE loss.  


