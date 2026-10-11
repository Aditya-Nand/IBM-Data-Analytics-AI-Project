# Retail Sales Analytics with AI

## Project description
This project analyses retail transaction data with Python. It includes data quality checks, basic cleaning, sales summaries, category and monthly trend visualisations, and a baseline Random Forest regression model to estimate transaction amounts from available features.

## Dataset
Download the Retail Sales Dataset from Kaggle:
https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

After downloading, place the CSV in the project folder and set `DATA_FILE` in the notebook to the exact filename. Dataset availability and licensing are controlled by the dataset publisher.

## Technologies used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Files
- `AdityaNand_RetailSalesAnalytics.ipynb` — complete project notebook
- `requirements.txt` — Python dependencies
- `AdityaNand_ProjectReport.docx` — project report
- `README.md` — project overview and run instructions

## Setup and run
1. Download the dataset CSV from the Kaggle link above.
2. Install Python 3.10+ and Jupyter, or open the notebook in Google Colab.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Put the CSV beside the notebook and update `DATA_FILE` if its name differs.
5. Run all notebook cells from top to bottom.
6. Review the generated charts, model metrics, and `retail_sales_cleaned.csv`.

## Notes
- Dataset columns can vary. The notebook attempts to detect common column names; if detection fails, adjust the column variables in the data-cleaning cell.
- Model metrics are generated when you run the notebook. Do not report unverified or fabricated results.
- This is an educational baseline, not a production sales forecasting system.
