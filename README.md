# LSTMvsGRU_Forecasting Public Repo

## This is an early learning project in a field I've become quite interested in, any feedback or critiques on my code or approach (especially if I missed any mistakes) is well appreciated!

A comparison of CNN-LSTM and CNN-GRU for financial forecasting tasks. This comparison was based on the task of 1 day forecasting, which both architectures excelled on with unseen data. GRU actually outperformed LSTM, perhaps due to the simpler nature of the dataset and LSTM's extra parameters making it more prone to overfitting. 

While much work is to be done confirming the results (for example: no hyperparam tuning was used), these early experiments show that GRU (the simpler and faster architecture) may potentially outform LSTM on certain trading instruments, which yield potential applications in both desk and automated trading where nanoseconds count.

