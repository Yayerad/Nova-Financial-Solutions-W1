Project Title: News Sentiment Analysis and Stock Market Correlation

Project Description

This project explores the relationship between financial news sentiment and stock market movements using data-driven techniques. By analyzing large volumes of financial news headlines and historical stock data, the study uncovers patterns and correlations that can provide insights for investment strategies.

The analysis focuses on sentiment scores derived from financial news articles and their potential influence on stock price changes, trading volume, and volatility. The project leverages machine learning and data engineering tools to process and analyze the data efficiently.

Objective

The core objective of this project is to:

Analyze sentiment from financial news data.

Correlate news sentiment with stock market metrics, including:

Stock price changes (open vs. close).

Trading volume.

Stock price volatility.

Identify actionable insights for potential investment strategies based on the findings.

Data Sources

Financial News Data: A collection of headlines and articles related to selected companies.

Historical Stock Market Data: Daily stock price data including the following attributes:

Date

Open

High

Low

Close

Adjusted Close

Volume

Dividends

Stock Splits

The dataset covers multiple decades, offering a robust basis for the analysis.

Tools and Technologies Used

The following tools, libraries, and techniques were used to complete this project:

Programming Language: Python

Libraries:

Pandas and NumPy: Data manipulation and analysis

NLTK and VADER: Sentiment analysis

Matplotlib and Seaborn: Data visualization

Scikit-Learn: Machine learning model development and evaluation

Techniques:

Sentiment Analysis (using VADER)

Correlation Analysis (Pearson Coefficient)

Data Aggregation and Visualization

Methodology

Data Preprocessing

Cleaned and prepared the financial news data.

Processed the historical stock market data for selected companies.

Sentiment Analysis

Used VADER to calculate sentiment scores for each news headline.

Aggregated sentiment scores on a daily basis to align with stock data.

Correlation Analysis

Measured the Pearson correlation coefficient to identify relationships between sentiment and:

Stock price changes.

Trading volume.

Volatility.

Visualization

Plotted trends and correlations to visualize patterns.

Insights and Recommendations

Interpreted results to propose actionable investment strategies.

Key Findings

Stock Price Correlation

Positive news sentiment often correlated with an increase in stock prices.

The strength of this correlation varied by company (e.g., Tesla showed a strong correlation, while Google’s was weaker).

Impact on Trading Volume

Extreme positive or negative sentiment days were associated with spikes in trading volume, indicating investor reaction to strong news signals.

Volatility

Higher volatility was observed on days with extreme sentiment scores, reflecting increased market uncertainty and trading activity.

Actionable Insights

Investors can monitor financial news sentiment to identify short-term trading opportunities.

A potential strategy includes buying stocks on days with strong positive sentiment and being cautious during strongly negative sentiment periods.

Limitations

Sentiment analysis alone cannot predict stock movements as the stock market is influenced by many other factors.

The observed correlations are not causal relationships.

Sentiment analysis results may vary depending on the sentiment analysis tool or dataset used.

Future Improvements

Integrate additional data sources, such as social media sentiment and macroeconomic indicators.

Enhance the sentiment analysis using more advanced natural language processing (NLP) techniques.

Explore causal relationships using time-series models.

Project Structure

The project files are organized as follows:

root/
|-- data/
|   |-- financial_news.csv          # Raw financial news dataset
|   |-- stock_prices.csv            # Historical stock market data
|-- notebooks/
|   |-- sentiment_analysis.ipynb    # Jupyter Notebook for sentiment analysis
|   |-- correlation_analysis.ipynb  # Notebook for correlation and visualization
|-- src/
|   |-- preprocess.py               # Data preprocessing scripts
|   |-- sentiment_analysis.py       # Sentiment analysis module
|   |-- correlation_analysis.py     # Correlation analysis logic
|-- results/
|   |-- visualizations/             # Plots and graphs generated during analysis
|-- README.md                       # Project documentation (this file)
|-- requirements.txt                # Required libraries and dependencies

How to Run the Project

Clone the Repository

git clone <repository-url>
cd <project-folder>

Set Up the Environment

Install the required libraries:

pip install -r requirements.txt

Run Jupyter Notebooks

Open the project notebooks:

jupyter notebook

View Results

Results, including visualizations and insights, are saved in the results/ folder.

Dependencies

Python 3.8+

Libraries listed in requirements.txt

Author

Yayerad Mekonnen

License

This project is licensed under the MIT License - see the LICENSE file for details.