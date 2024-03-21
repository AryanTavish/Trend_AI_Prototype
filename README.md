## README for TREND AI Prototype

### Overview
This repository contains a prototype for a Stock Trend Prediction application named TREND AI. The application utilizes Long Short-Term Memory (LSTM) neural networks to predict stock prices based on historical data. It provides visualizations of the historical stock prices along with moving averages to aid in trend analysis.

### Requirements
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - pandas_datareader
  - keras
  - streamlit

### Installation
1. Clone this repository to your local machine.
2. Install the required libraries using pip:
   ```
   pip install numpy pandas matplotlib pandas_datareader keras streamlit
   ```

### Usage
1. Run the Streamlit application:
   ```
   streamlit run trend_ai_prototype.py
   ```
2. Enter a stock ticker symbol in the text input field.
3. Explore the descriptive statistics of the stock data from 2010 to 2019.
4. Visualize the closing price over time.
5. Analyze the closing price over time with a 100-day moving average.
6. Analyze the closing price over time with both 100-day and 200-day moving averages.

### Files
- `trend_ai_prototype.py`: Python script containing the prototype code for the TREND AI application.
- `README.md`: This README file providing an overview, installation instructions, and usage guidelines for the prototype.

### Contributions
Contributions to the TREND AI project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

### License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
