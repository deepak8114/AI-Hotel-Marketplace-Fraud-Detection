# AI-Hotel-Marketplace-Fraud-Detection
AI-powered solution for hotel booking platforms integrating a Marketplace Experience Index (MEI) and Fraud &amp; Anomaly Detection module. Detects fake reviews, price manipulation, and booking anomalies while improving customer trust and hotel reputation.

🔹 Overview

This project builds an AI-driven platform to tackle major challenges in the online hotel booking industry:

Price manipulation by reception staff

Fake reviews misleading customers

Hidden charges & fraudulent practices

Our solution integrates two major modules:

Marketplace Experience Index (MEI) → Quantifies customer trust & satisfaction.

Fraud & Anomaly Detection Module → Identifies pricing fraud, fake reviews, and booking anomalies.
🔹 Features

✅ Marketplace Experience Index (MEI)

Price consistency scoring

Review sentiment analysis (TF-IDF, NLP)

Hotel performance (ratings, cancellation history)

✅ Fraud & Anomaly Detection

Price consistency checker (App vs Hotel)

Guest count manipulation anomaly detection

Fake review classifier (TF-IDF + ML, BERT/RoBERTa)

Anomaly detection using Isolation Forest, One-Class SVM, Autoencoders

✅ Visual Dashboards

Correlation matrix & fraud score distribution

Heatmap of fraud hotspots

Time-series fraud trend analysis

Review sentiment word cloud

🔹 Dataset

Source: Kaggle + Synthetic Dataset

Size: 793 rows

Key Features: Booking IDs, Customer IDs, Reviews, Ratings, Prices, Guests, City, Discounts

Preprocessing Includes:

Handling missing values

Outlier detection

Encoding categorical variables

Sentiment analysis of reviews

Feature engineering (price consistency, cancellation rate, fraud score)

🔹 Methodology

Data Preprocessing & Feature Engineering

Model Development

MEI: Random Forest, XGBoost, LightGBM

Fraud Detection: Isolation Forest, One-Class SVM, Autoencoder, NLP Models

Model Evaluation

RMSE, R² (for MEI)

Accuracy, Precision, Recall (for fraud detection)

Deployment

API built with FastAPI

Integrated with hotel booking systems

Real-time fraud alerts & dashboards

🔹 Results

MEI Generated: 0–100 scale (higher = better experience)

Fraud Detection Accuracy: ~X% (from experiments)

Fake Review Detection Accuracy: ~Y%

Insights: Fraud hotspots mapped, anomaly trends identified

🔹 Tech Stack

Languages: Python 3.9+

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, CatBoost, TensorFlow, Transformers, NLTK, SHAP, Matplotlib, Seaborn, Plotly

Deployment: FastAPI, Uvicorn, Docker, Cloud (AWS/GCP)

Visualization: Power BI, Matplotlib, Seaborn, Plotly

🔹 Deployment Workflow

Train model → Save (.pkl)

Deploy API with FastAPI → /predict, /fraud-check endpoints

Integrate with booking frontend (React / booking system)

Monitor fraud score in real-time dashboards

🔹 Business Impact

For Customers: Transparent pricing, trusted reviews, safer bookings
For Hotels: Reputation protection, reduced disputes, customer loyalty
For Platforms (OYO/Booking.com): Reduced fraud losses, improved trust, competitive edge

🔹 Future Enhancements

🚀 Blockchain-based price locking
🎙️ Voice-based fraud alerts (hands-free assistant)
🤖 LLM-powered review authenticity checks
✈️ Expansion to airlines & car rentals

🔹 Project Structure
📂 AI-Hotel-Fraud-Detection
│── 📁 data/                # Raw + processed dataset
│── 📁 notebooks/           # Jupyter notebooks (EDA, training, evaluation)
│── 📁 models/              # Saved ML models (.pkl/.h5)
│── 📁 api/                 # FastAPI deployment scripts
│── 📁 visualization/       # Graphs, dashboards, insights
│── 📄 requirements.txt     # All dependencies
│── 📄 LICENSE              # MIT License
│── 📄 README.md            # Project overview
│── 📄 report.pdf           # Full project report (35-40 pages)

🔹 Installation & Usage
# Clone repo
git clone https://github.com/deepak8114/AI-Hotel-Fraud-Detection.git
cd AI-Hotel-Fraud-Detection

# Create environment & install dependencies
pip install -r requirements.txt

# Run model training
jupyter notebook notebooks/AI_based_hotel_integrated_model_.ipynb

# Deploy API
cd api
uvicorn main:app --reload

🔹 License

This project is licensed under the Apache2.0 License – free to use, modify, and distribute with attribution.

🔹 Contact

👨‍💻 Deepak Patro
📧 Email: [deepakpatro73@gmail.com]
🔗 LinkedIn: [https://www.linkedin.com/in/deepak-patro-2a0330228?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BTy6DtI9xQguO71TKDi3bFw%3D%3D]
🌍 Portfolio: [https://foxna-intelligence.b12sites.com/index]
