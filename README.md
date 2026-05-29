# AI-Marketing-project-group3
This project is an AI system using ML and NLP to predict and prevent telecom customer churn. Built with Python and Power BI, it clusters subscribers via K-Means, analyzes social media sentiment, and runs predictive classification. Insights are deployed to a dashboard for real-time churn tracking, model governance, and retention execution.
# AI-Driven Marketing Analytics: Customer Churn Prediction & Segmentation

This end-to-end marketing analytics system leverages machine learning, natural language processing, and business intelligence to optimize customer retention for a telecommunications operator. By combining structured CRM data with external social media sentiment analysis, the system identifies high-risk customer segments, profiles cohort behaviors using K-Means clustering, and predicts individual subscriber defection using advanced classification algorithms. The final predictive insights are compiled into an enterprise-grade, interactive Power BI decision support system that provides prescriptive action plans, tracks marketing campaign ROI, and monitors machine learning model governance in real-time.

## Group Members & Contributions
*   Member 1: Zharova Malika — Focused on Data Preprocessing, Feature Engineering, K-Means Clustering, and Predictive Modeling implementation.
*   Member 2: Tokanaeva Aisana — Focused on Social Media Analytics, Sentiment Analysis (NLP), Power BI Dashboard development, and Report writing.

## Dataset Source
The primary dataset utilized in this project is the Telco Customer Churn dataset. 
*   Direct Link to Source: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Tools and Libraries Used
*   Language: Python 3.10+
*   Data Manipulation: pandas, numpy
*   Machine Learning & Processing: scikit-learn (`StandardScaler`, LabelEncoder, OneHotEncoder, KMeans, LogisticRegression, `RandomForestClassifier`)
*   Data Visualization: matplotlib, seaborn
*   Business Intelligence Frontend: Microsoft Power BI Desktop / Service

## Project Folder Structure
The repository is systematically organized according to the following architecture:
```text
ai-marketing-project-groupX/
├── README.md                  # Project overview, documentation, and execution guide
├── data/                      # Data storage directory
│   ├── raw_customer_data.csv  # Original unaltered Telco dataset
│   └── cleaned_customer_data.csv # Final processed data export used for BI modeling
├── notebook/                  # Python executable files
│   └── marketing_analytics_pipeline.ipynb # Core Jupyter Notebook (EDA, ML, NLP)
├── report/                    # Formal written documentation
│   └── Final_Project_Report.pdf # Exhaustive project report in PDF format
├── dashboard/                 # Power BI visual assets
│   ├── Page1_Executive_Overview.png
│   ├── Page2_Customer_Segmentation.png
│   ├── Page3_Churn_Predictive_Drivers.png
│   ├── Page4_Campaign_ROI_Tracking.png
│   ├── Page7_Model_Risk_Governance.png
│   └── Page8_Prescriptive_Recommendations.png
└── presentation/              # Slide deck assets
    └── Project_Defense_Slides.pdf # Final presentation slides
