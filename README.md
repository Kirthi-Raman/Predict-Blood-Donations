# Predict-Blood-Donations
Predicting if a blood donor will donate blood the next time

The data is stored in datasets/transfusion.data and it is structured according to RFMTC marketing model (a variation of RFM).
RFM stands for Recency, Frequency and Monetary Value and it is commonly used in marketing for identifying your best customers.

TPOT is used to select a model. TPOT is a Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
TPOT will automatically explore hundreds of possible pipelines to find the best one for our dataset. Note, the outcome of this search will be a scikit-learn pipeline, meaning it will include any pre-processing steps as well as the model.
