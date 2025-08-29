# Trader Behavior Insights

Analyzing **trader performance** vs **Bitcoin market sentiment** (Fear/Greed) to uncover patterns and insights for smarter trading strategies.

## Author
**Tejas Bhosale**  
Junior Data Scientist – Trader Behavior Insights

## Overview
This project explores the relationship between historical trader behavior and Bitcoin market sentiment. Using the **Fear/Greed Index** and trader transaction data, it identifies patterns in:

- Profitability (Closed PnL)
- Trade Size
- Leverage
- Trade volume

## Folder Structure

ds_TejasBhosale/

├── notebook_1.ipynb # Main analysis in Google Colab

├── notebook_2.ipynb # Optional additional notebook

├── csv_files/ # All CSV files (raw & processed)

│ └── *.csv

├── outputs/ # Visual outputs (charts, graphs)

│ └── *.png / *.jpg

├── ds_report.pdf # Summarized insights & explanations

└── README.md # This file


## Data Sources
1. `historical_data.csv` – Trader transaction data (Account, Coin, Execution Price, Size Tokens, Closed PnL, Leverage, etc.)
2. `fear_greed_index.csv` – Bitcoin market sentiment (timestamp, value, classification, date)

## How to Use

1. Open `notebook_1.ipynb` in **Google Colab**.
2. Upload CSV files from `csv_files/` folder.
3. Run the notebook to reproduce EDA, plots, and analysis.
4. Output plots are saved in `outputs/` folder.
5. Refer to `ds_report.pdf` for summarized insights and recommendations.

## Key Insights

- Traders show highest profitability during **Greed** periods.
- Trade sizes and volume peak during **Extreme Greed** and **Fear** periods.
- Most trades occur during **Fear**, indicating cautious trading behavior.
- Leverage analysis shows increased risk-taking during **Extreme Greed**.

## Recommendations

- Adjust trading strategies based on Fear/Greed sentiment.
- Monitor the **Fear/Greed Index** to optimize trade timing.
- Balance trade volume and leverage to maximize profitability while managing risk.

## License
This repository is for educational and assignment purposes only.
