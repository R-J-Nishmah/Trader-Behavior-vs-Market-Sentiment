# Trader-Behavior-vs-Market-Sentiment
Data science analysis of trader behavior against Bitcoin market sentiment (Fear vs Greed), including EDA, behavioral segmentation, predictive modeling, and actionable trading insights using real Hyperliquid trading data.

Setup Instructions
1️⃣ Environment

This project is designed to run on Google Colab.

Required Python version:

Python 3.9+

2️⃣ Required Libraries

All required libraries are available by default in Google Colab.
If running locally, install dependencies using:

pip install pandas numpy matplotlib seaborn scikit-learn

3️⃣ Dataset Setup

Download the datasets from the following links:

Bitcoin Fear & Greed Index
https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view

Historical Trader Data (Hyperliquid)
https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view

Upload both CSV files to the Google Colab file system before running the notebook.

▶️ How to Run the Project
Step 1: Open the Notebook

Open DS assignment.ipynb in Google Colab.

Step 2: Upload Datasets

In Colab:

Click the Files icon (left sidebar)

Upload:

historical_data.csv

fear_greed_index.csv

Step 3: Run the Notebook

Execute all cells sequentially from top to bottom.

The notebook performs:

Data validation and cleaning

Timestamp normalization and daily alignment

Feature engineering

Sentiment-based analysis

Behavioral segmentation

Bonus predictive modeling and clustering

Step 4: Generated Outputs

After successful execution, the following will be automatically created:

Processed datasets → NISHMAH/

Charts and visualizations → outputs/

Final insights → ds_report.pdf
