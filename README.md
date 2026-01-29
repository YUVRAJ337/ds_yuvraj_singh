# Trader Behavior vs Market Sentiment

This project analyzes how trader performance and behavior vary across market sentiment conditions (Fear vs Greed) using historical trading data and the Bitcoin Fear & Greed Index.

## Structure
- notebook_1.ipynb: Full analysis in Google Colab
- csv_files/: Processed datasets
- outputs/: Visualizations
- ds_report.pdf: Final summarized report

## Key Insights
- Traders show higher average PnL and win rate during Greed phases
- Trade sizes increase during Fear phases, indicating selective risk-taking
- Market sentiment can be used as a contextual signal for trading strategies

## Tools
- Python, Pandas, Matplotlib
- Google Colab
  
 ## Note on Data Files

Due to GitHub file size limitations, large intermediate CSV files
(`merged_data.csv`, `trader_cleaned.csv`) are not included in this repository.

These files are generated programmatically within `notebook_1.ipynb`
and can be reproduced by running the notebook in Google Colab.
