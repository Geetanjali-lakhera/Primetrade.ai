# Hyperliquid Trader Analysis: Market Sentiment Impact

##Overview
This project analyzes how Fear & Greed sentiment affects trader behavior and performance on Hyperliquid. The goal is to uncover actionable patterns that can inform smarter trading strategies.

##Files Included
- `NotebookPrimetrade.ipunb` - Main Jupyter notebook with complete code Part A and Part B
- `PART C 2 stragies.docx` - Document giving 2 best Strategies based on my findings
- `charts/` - 3 charts of all the 3 questions
- `Short write-up.docx` - One-page summary of methodology, insights, and recommendations
- - `README.md` - This file (setup instructions + documentation)

## Setup Instructions

### Prerequisites
- Google account (for Colab)
- Data files downloaded to your Google Drive

### Step 1: Download the Data
1. Download both datasets from the provided links:
   - `fear_greed_index.csv`
   - `historical_data.csv`
2. Upload them to your Google Drive in a folder called `Colab Notebooks`

### Step 2: Open in Colab
1. Go to [Google Colab](https://colab.research.google.com/)
2. Upload `NotebookPrimetrade.ipynb` or create a new notebook and paste the code
3. Make sure the file paths in the code match where you saved the data:
   ```python
   fear_greed = pd.read_csv('fear_greed_index.csv')
   trades = pd.read_csv('historical_data.csv')
