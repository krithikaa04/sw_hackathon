# sw_hackathon

The problem statement is to collect closed price AAPL stock data from the Quantrocket platform and apply algorithms to build  a simple model to make decision based 
on the stock prices.
</br></br>The statistical model I used is a **MARKOV CHAIN MODEL** whose future state depends only on the current state and not the previous states. A state transition diagram was drawn, transition probability matrix was deduced and the portfolio value along with the buy indices based on the pre-specified logic was calculated. Apart from this, I also derived that these stock prices were in a stationary distribution both mathematically and visually. 
</br>Further, time series forecasting was done using ARIMA model and the predicted results were plotted.


</br>The detailed report and explanation of my approach is given in: https://github.com/krithikaa04/sw_hackathon/blob/main/sigmaWedge-report.pdf
</br>COLAB notebook:  https://github.com/krithikaa04/sw_hackathon/blob/main/stock%20(1).ipynb
