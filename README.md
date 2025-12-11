# HomeIQ-Predictor
HomeIQ-Predictor is a machine-learning powered Streamlit web application that predicts residential property prices based on key features such as location, size, bedrooms, bathrooms, furnishing type, luxury category, and more. The app delivers instant predictions along with SHAP explainability to help users understand how each feature influences the estimated price.


# 🚀 Features

🔮 Price Prediction using a trained ML pipeline

🏙️ Interactive UI built with Streamlit

📊 SHAP-based feature importance visualization

🧹 Clean preprocessing pipeline for structured & categorical data

📦 Pickled model & dataset integration

🔧 Easy to run locally

🎨 Custom-themed UI + Sidebar Info


# 🛠️ Tech Stack

Python 3

Streamlit

Pandas, NumPy

Scikit-Learn

SHAP

Matplotlib


# 📂 Project Structure
│── app.py                 # Main Streamlit application

│── pipeline.pkl           # Trained ML model pipeline

│── df.pkl                 # Preprocessed dataset for dropdowns

│── README.md              # Documentation

│── requirements.txt       # Project dependencies


# 🏗️ Installation & Setup
# 1️⃣ Clone the repository
git clone https://github.com/your-username/EstateSense-AI.git
cd EstateSense-AI

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Run the Streamlit app
streamlit run app.py

# 📘 Usage

Select property features (location, area, rooms, furnishing, etc.)

Click Predict Price

View the estimated price range

Explore SHAP feature importance to understand the prediction


# 🧠 Machine Learning Model

Uses a Scikit-Learn Pipeline with preprocessing steps

Handles categorical + numerical features

Uses log-transformation for stable prediction

Predicts price in Crores (INR)

SHAP provides explainable AI output

🖼️ Screenshots (Optional)

You can add your own screenshots here:

![App Screenshot](path_to_image)


# 📈 Future Enhancements

🗺️ Geo-based price heatmaps

📊 Advanced visual analytics dashboard

🏘️ Rental price prediction model

🔗 Backend database for storing user inputs


# 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to modify.


# 📜 License

This project is licensed under the MIT License.


# 👨‍💻 Developed By

Shalini Kumari
