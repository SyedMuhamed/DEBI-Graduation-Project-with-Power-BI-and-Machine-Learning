# Integrative Analysis of U.S. Stock Market Movements

Explore a comprehensive project presentation on Major U.S. Market Stock Analysis under the Digital Egypt Builders Initiative. This project integrates machine learning algorithms like Decision Trees, Random Forests, and LSTM models to enhance stock price predictions. Delve into research challenging traditional market beliefs and demonstrating the impact of data analytics on stock forecasting. Efficiently managed using Trello, this project showcases a multifaceted approach to understanding market movements and financial health correlations. 

Using Power BI, Python & Machine Learning, and Trello Project Management - Completed during my time at DEBI (Graduation Project).

This project integrates machine learning algorithms like Decision Trees, Random Forests, and LSTM models to enhance stock price predictions. By analyzing financial metrics such as EVA, ROA, ROS, and Net Debt against Interest Coverage, the project explores the relationship between financial health and stock performance in the S&P 500. The findings provide insights into risk factors and deviations from market sentiment.

---

## Project Structure

### 1. Data Collection and Cleaning
- **Tool**: Python's `yfinance` library.
- **Description**: Extracted historical financial data for S&P 500 companies, including:
  - Balance Sheets
  - Income Statements
  - Cash Flow Statements
  - Trading Data (e.g., stock prices, volumes).
- **Key Steps**:
  - Handled missing and null values.
  - Normalized data using MinMaxScaler for improved model performance.

### 2. Machine Learning Models
- **Objective**: Predict stock prices using historical data.
- **Models Used**:
  - **Decision Tree**
    - Simple and interpretable but prone to overfitting.
  - **Random Forest Regressor**
    - Ensemble model reducing overfitting and variance.
  - **LSTM (Long Short-Term Memory)**
    - Captures long-term dependencies, ideal for sequential data.
- **Evaluation Metrics**:
  - Mean Squared Error (MSE).
- **Results**:
  - LSTM models provided better insights into long-term market cycles but struggled with short-term volatility.

### 3. Fundamental Analysis
- **Tool**: Power BI.
- **Focus**:
  - Economic Value Added (EVA).
  - Return on Assets (ROA) and Return on Sales (ROS).
  - Net Debt and Interest Coverage Ratios.
- **Outputs**:
  - Dashboards for assessing value creation and financial risks across companies and industries.
  - Comparative analysis of financial health vs. stock price trends.

### 4. Project Management
- **Tool**: Trello.
- **Overview**: Trello’s agile boards facilitated organized sprints, tracking tasks from data processing to model training. Weekly reviews supported iterative progress and timely adjustments.
- **Methodology**: Agile.
  - Tasks divided into sprints (e.g., data extraction, model training, visualization).
  - Weekly progress reviews ensured iterative improvements.

---

## Key Findings
- Stock price movements often deviate from fundamental financial health metrics, influenced by external factors like market sentiment and speculation.
- LSTM models captured long-term trends effectively but struggled with short-term market volatility.
- Power BI dashboards highlighted disparities between financial metrics and stock performance, showcasing areas of financial risks and opportunities.

---

## Tools and Technologies
- **Data Extraction & Cleaning**: Python (`yfinance`, `pandas`, `numpy`).
- **Machine Learning**: Scikit-learn, TensorFlow/Keras.
- **Visualization**: Power BI.
- **Project Management**: Trello.

---

## Future Enhancements
- Integrate real-time market sentiment analysis (e.g., social media, news headlines).
- Incorporate additional external economic indicators for improved model accuracy.
- Explore ensemble techniques combining machine learning and fundamental analysis insights.

---

## Contributors
- **Team Members**:
  - Syed Mohamed
  - Karim Hisham
  - Makarius Nader
- **Supervisor**:
  - Dr. Amira

---

## Conclusion
Findings revealed that stock prices often deviate from fundamental health due to factors like market sentiment. Integrating machine learning with financial analysis underscored the need for a multifaceted approach to stock forecasting. Dashboards provided actionable insights into financial risks and long-term trends.

---

## References

### Documentation
1. [YFinance Documentation](https://pypi.org/project/yfinance/)  
   Official documentation for the YFinance Python library, providing tools to access financial market data.
2. [Power BI Overview](https://powerbi.microsoft.com/)  
   Overview and resources for Power BI, Microsoft's interactive data visualization and business intelligence tool.

### Research Papers and Tutorials on LSTM and Financial Analysis
1. [Introduction to Long Short-Term Memory (LSTM) Models](https://medium.com/analytics-vidhya/introduction-to-long-short-term-memory-lstm-a8052cd0d4cd)  
   A beginner-friendly introduction to LSTM networks and their applications, published on Medium.
2. [Long Short-Term Memory](https://www.researchgate.net/publication/13853244_Long_Short-term_Memory)  
   A seminal paper on the LSTM model, available on ResearchGate.
3. [Explaining the Components of a Neural Network](https://galaxyinferno.com/explaining-the-components-of-a-neural-network-ai/)  
   An article breaking down the components of neural networks, with insights into LSTMs.
---

## Contact
- **LinkedIn**: [Syed Abdulhamid](https://www.linkedin.com/in/syedabdulhamid)

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
