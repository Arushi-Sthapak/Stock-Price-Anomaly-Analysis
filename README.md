# Stock Market Anomaly Detection with Python
This project explores stock market anomaly detection using Python libraries like yfinance for data acquisition and statistical methods for anomaly identification.

## What is Stock Market Anomaly Detection?
Anomaly detection aims to identify unusual patterns or behaviors in stock market data that deviate significantly from the norm. These anomalies can potentially indicate opportunities or risks for investors.

## Snapshots
![image](https://github.com/Arushi-Sthapak/Stock-Price-Anomaly-Analysis/assets/99334415/d74dd52e-1185-443f-be62-a2a16306dfae)


## Getting Started
#### 1. Clone this repository:
```
git clone https://github.com/Arushi-Sthapak/Stock-Price-Anomaly-Analysis.git
```

#### 2. Open the Jupyter Notebook: <br>
   Launch Jupyter Notebook or Google Colab.
   Navigate to the project directory and open ``` stock_anomaly_detection.ipynb ```.

#### 3. Install dependencies: <br>
   This project requires the following Python libraries: <br>

  ``` yfinance ```<br>
  ``` pandas ``` <br>
  ``` matplotlib  ```<br>
  ``` numpy (usually included with pandas) ```<br>

  Install the libraries on Jupyter or import directly for Google Colab.

## Data Acquisition

This project utilizes the yfinance API to obtain historical stock market data. You'll need to specify the ticker symbol(s) of the stock(s) you want to analyze and the desired time frame.

## Data Exploration and Feature Engineering

We'll explore the retrieved data (e.g., prices, volumes) and potentially create additional features like moving averages, Relative Strength Index (RSI), or percentage changes to enhance anomaly detection.

## Anomaly Detection with Z-scores

The Z-score method will be used to identify anomalies in both price and volume data. This method calculates the standard deviation from the mean and flags data points as anomalies if they fall outside a specific threshold (e.g., 3 standard deviations).

## Visualization

Data visualization plays a crucial role in identifying anomalies. We'll generate plots that showcase the original data alongside the identified anomalies for better understanding.

## Risk Assessment

Based on the frequency and magnitude of anomalies, a risk rating will be calculated for each stock. This risk rating can be used as a preliminary indicator for investment decisions.

## Important Considerations

Stock market anomaly detection is not an exact science, and anomalies don't guarantee future market movements.
Always consider other factors like company fundamentals, market trends, and economic conditions before making investment decisions.

## Future Enhancements

Explore more sophisticated anomaly detection techniques like machine learning models (e.g., LSTMs, Isolation Forests)
Integrate the risk rating into a trading strategy framework (**Disclaimer: This is for educational purposes only, not financial advice)


