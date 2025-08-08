# pm25-forecasting-india-model-vs-baseline
Title
PM2.5 Forecasting in India — Model vs Baseline

Open in Colab
Open in Colab: https://colab.research.google.com/github/SurajChouhan14/pm25-forecasting-india-model-vs-baseline/blob/main/pm2_5_forecasting_india_model_vs_baseline.ipynb

Overview
End-to-end PM2.5 forecasting pipeline with:

Chronological train/test split (no leakage)

24-hour persistence baseline

RandomForest model with time and lag features

Side-by-side evaluation (R2, MAE, RMSE)

Diagnostics: distribution, daily trends, high-episode checks, residuals, error heatmap, error vs magnitude, distribution overlap

Data

Source: Air Quality Data in India (2017–2022) by fedesoriano (Kaggle)

Link: https://www.kaggle.com/datasets/fedesoriano/air-quality-data-in-india

Expected file name in runtime: air-quality-india.csv

Note: Do not commit large datasets to the repo. Upload to Colab or mount Google Drive.
End-to-end PM2.5 forecasting with a 24h baseline, model benchmarking, and diagnostics.
