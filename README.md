# Enterprise-fraud-detection-full-ml-pipeline.ipynb
We also trained the Machine learning model use the best and good model whos is good achieve.
    
## Download the Dataset using the follwing the Link :- https://www.kaggle.com/datasets/mohamedasak/enterprise-fraud-detection-dataset/data 
   
Dataset Explanation :-
  
This dataset simulates enterprise-level financial transaction data designed   
for fraud detection research and machine learning development.
It contains 200,000 transactions spanning 4 months (January–April 2025),  
with a realistic fraud rate of approximately 2.8%.

The dataset covers 5 fraud types:

Card Testing
Identity Theft
Account Takeover
Fraud Ring
Concept drift is injected after day 90 to simulate real-world
model degradation scenarios.

Features:

Customer behavioral profiles (credit score, account age, spending history)
Real-time velocity features (transaction counts over 1h, 24h, 7d windows)
Geolocation signals (distance from home, foreign transactions, high-risk countries)
Device fingerprinting (VPN/Tor detection, new device flags)
Graph/network features (fraud rings, shared device counts)
Merchant risk scoring by category
Ideal for:

Binary fraud classification
Anomaly detection
Imbalanced learning (SMOTE, class weights)
SHAP explainability
Concept drift experimentation
Recommended Models: XGBoost, LightGBM, Random Forest, Graph Neural Networks
