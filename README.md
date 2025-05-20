EV Charging Demand Forecasting
This project aims to forecast electric vehicle (EV) charging demand using machine learning and deep learning models. The three models consisted of ARIMA, XGBoost, and LSTM, all of which, however, were directed towards achieving one common goal: to promote charging station efficiency and reduce congestion in EV infrastructure.
Project Structure
.ipynb: The complete Jupyter notebook containing all code, visualizations, preprocessing steps, and model evaluations.
Word.docx: Final written report including the project background, methodology, results, literature review, and conclusion.
Dataset
This dataset includes 3,395 sessions of EV charging at 25 workplace locations with 105 charging stations. It contains entries like:
Energy used (kWh)
Charging time
Time and date
Charging platform
Location and station ID
The dataset is public and licensed under CC0 1.0 (no usage restrictions).
🔍 Models Used
1. ARIMA (AutoRegressive Integrated Moving Average)
Best for: Linear time series
Limitations: Poor performance on non-linear data
Evaluation: Moderate accuracy
2. XGBoost
Best for: Complex and non-linear relationships
Result: Best performance
MAE: 0.0168 | R²: 0.9997 | MAPE: 0.0081%
3. LSTM (Long Short-Term Memory)
Best for: Long-term sequence patterns
Result: Poor accuracy due to tuning challenges
R²: 0.01 | MAPE: 67.85%
🛠️ Features & Tools
Python
Google Colab
Pandas, NumPy, Seaborn, Matplotlib
Scikit-learn
Statsmodels
XGBoost
TensorFlow / Keras for LSTM
 Results Summary
XGBoost outperformed both ARIMA and LSTM in all accuracy metrics.
ARIMA was only good for simple trends.
LSTM showed potential but needs better tuning and more data.
Key Takeaways
Predicting EV charging demand helps improve smart grid planning and reduce overload at charging stations.
Using machine learning, cities can end up preparing future progressive ways for themselves, for electric mobility.
License
This project utilizes open data and is exclusively for educational and research use.

