# MotoGP_Qualifying_Position_Prediction

🏁 MotoGP Qualifying Prediction (2022–2025)
📌 Description (Short Pitch)

This project is a data-driven analysis and machine learning pipeline designed to predict MotoGP qualifying positions based on historical data from 2022 to 2025. It includes thorough data preprocessing, feature engineering, exploratory visualizations, and model development using Random Forest, Decision Tree, and XGBoost.
📊 Project Highlights

    ✅ Cleaned and analyzed real-world MotoGP qualifying data

    📈 Built visualizations to uncover trends in rider and team performance

    🧠 Trained machine learning models to predict qualifying position

    ⚙️ Evaluated models using MAE, RMSE, and R²

    📊 Francesco Bagnaia achieved the highest number of 1st place starts (24x)

    ⏱️ Fastest qualifying season: 2024 with lowest average lap time

🧪 Key Machine Learning Models
Model	Description
RandomForest	Robust ensemble model for capturing variance
DecisionTree	Interpretable model for initial understanding
XGBoost	High-performance gradient boosting algorithm

All models were evaluated with:

    Mean Absolute Error (MAE)

    Root Mean Square Error (RMSE)

    R² Score

📌 Key Features Engineered

    is_Q2: binary indicator if session was Q2

    team_avg_time: average time per team per event

    rider_track_experience: cumulative count of rider on same track

    gap_to_first: time gap to the fastest rider

    encoded_rider/team: for ML purposes

📈 Visualizations Included

    Qualification time trends by year

    Distribution of qualifying times

    Top 15 riders with most P1 starts

    Boxplot of team performance consistency

    Circuit-based average positions

🧰 Tech Stack

    Python, Pandas, NumPy

    Matplotlib, Seaborn

    Scikit-learn, XGBoost

    Google Colab

