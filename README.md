# Stock Price Prediction Using Deep Learning 📈🧠

This research leverages deep learning to predict stock prices across 100 S&P 100 stocks, evaluating models like LSTM, CNN, RNN and CNN_LSTM. What makes this project unique is its dual focus: identifying the most accurate model and determining which model is better at generating Alpha excess returns, providing actionable insights for trading strategies

## Presentation
Below are the key slides summarizing the findings and approach:
![698ppt1](https://github.com/yinaS1234/Deep-Learning-Stock-Price-Prediction/blob/main/resource/698ppt1.png)
<br>
![698ppt2](https://github.com/yinaS1234/Deep-Learning-Stock-Price-Prediction/blob/main/resource/698ppt2.png)
![698ppt3](https://github.com/yinaS1234/Deep-Learning-Stock-Price-Prediction/blob/main/resource/698ppt3.png)


### Key Highlights:
- **Objective**: To assess the predictive accuracy and practical trading utility of different deep learning architectures.
- **Results**:
  - **LSTM** emerged as the most reliable model for both short- and long-term forecasts, achieving the lowest prediction error across all forecast windows.
  - **CNN+LSTM** performed well but did not surpass LSTM, while **CNN** excelled in short-term forecasting but struggled with longer horizons.
  - **RNN** had the highest prediction errors, making it the least effective model.
  - **Alpha analysis** demonstrated LSTM's potential for generating short-term excess returns, emphasizing its suitability for trading-focused applications.
- **Future Scope**: Exploration of transformer models and integration of external factors like economic indicators or investor sentiment to further enhance prediction accuracy and profitability.

---

> **Note**: Full project details and raw data are available upon request.

---

## Tools and Technologies
- **Data Processing**: Python (Pandas, NumPy)
- **Deep Learning Models**: LSTM, CNN, RNN, CNN+LSTM (TensorFlow, Keras)
- **Evaluation Metrics**: RMSE, MAE, Alpha
- **Visualization**: Matplotlib, Seaborn
- **Presentation**: PowerPoint

---

## Contact
For more details or inquiries, feel free to contact me via email me at [yina.qiao84@spsmail.cuny.edu.
