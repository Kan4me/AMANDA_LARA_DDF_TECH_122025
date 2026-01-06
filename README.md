# AMANDA_LARA_DDF_TECH_122025
Technical Challenge for Dadosfera. Use of a Kaggle database to assess technical capabilities of interest to the company.
Complete implementation of a data engineering and analytics pipeline for Olist's Brazilian e-commerce dataset.

## Data Modeling
Kimball's principals selected, as following:
<img width="2486" height="1496" alt="dataschema_olist" src="https://github.com/user-attachments/assets/4f77bff8-8e36-496b-a006-dd385fec8d1a" />

## Architecture
1. **Data Ingestion**: Kaggle API to download dataset
2. **Data Quality**: Great Expectations validation suite
3. **AI Enrichment**: OpenAI GPT for sentiment analysis
4. **Visualization**: Interactive Streamlit dashboard
5. **Deployment**: Cloud-accessible web application

## Key Features
- Automated data validation with 10+ quality checks
- LLM-powered sentiment analysis of product reviews
- Interactive dashboard with real-time filtering
- Geographic analysis of sales distribution
- Performance metrics and trend analysis

## How to Run
1. Configue KAGGLE_USERNAME, KAGGLE_KEY and OPENAI_API_KEY on Secrets's Colab
2. Run all cells sequentially
3. Access dashboard via provided URL

## Technologies Used
- Google Colab
- Pandas, Great Expectations v. 0.18.12 
- OpenAI GPT-3.5
- Streamlit, Plotly
- Kaggle API

## Results
- Data Quality Report: `data_quality_report.json`
- Interactive Dashboard: Public URL (generated at runtime)
- Processed Dataset: Available for download from dashboard
