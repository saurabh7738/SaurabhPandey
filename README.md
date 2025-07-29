# Objective
Analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed). Identify hidden trends or signals that could influence smarter trading strategies.
readme_content = f"""
# Trader Behavior vs Market Sentiment Analysis

This project analyzes how trading behavior (profitability, volume, risk, leverage) aligns or diverges from overall market sentiment (Fear vs Greed). 
We use EDA, clustering (KMeans), correlation, and regression (including lagged sentiment) to uncover trading patterns.

## Repository Structure

ds_Saurabh_pandey/

├── notebook_1.ipynb # Full analysis (EDA, clustering, regression)

├── notebook_2.ipynb # (Optional) Additional exploration

├── csv_files/ # Processed data and outputs

├── outputs/ # Plots, charts, cluster visuals

├── ds_report.pdf # Final insights report

└── README.md # Setup instructions and overview

## Key Insights
- Fear periods often lead to higher profitability, even with lower volume.
- Greed phases attract high volume but lower returns due to risk.
- Price volatility tends to **lead sentiment changes** (a predictive signal).
- Lagged sentiment (yesterday’s mood) can help forecast profitability.

## Usage
1. Open `notebook_1.ipynb` in Google Colab.
2. Upload raw data CSVs when prompted.

# Dataset Links
1. Historical Trader Data:
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing
2. Fear & Greed Index:
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Also available in Repo in CSV-files folder
