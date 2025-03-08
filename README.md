# Aero Predict – Airline Fare Prediction  

## Overview  
Flight ticket prices fluctuate due to various factors like airline, travel date, total stops, and flight duration. **Aero Predict** is a machine learning project designed to analyze these factors and predict airline fares accurately.  

## Dataset  
The dataset contains **10,683 flight records** with details such as:  
- **Airline** – The airline operating the flight  
- **Date of Journey** – Flight schedule  
- **Source & Destination** – Departure and arrival locations  
- **Departure & Arrival Time** – Timings of the flight  
- **Duration** – Total flight time  
- **Total Stops** – Number of layovers  
- **Price** – Actual ticket cost  

## Approach  
1. **Data Preprocessing** – Handling missing values, converting date-time features, and encoding categorical data  
2. **Feature Engineering** – Extracting useful features like journey month, duration in minutes, and departure time categories  
3. **Exploratory Data Analysis (EDA)** – Analyzing price trends based on airlines, stops, and duration  
4. **Model Training** – Implemented **Random Forest Regressor** for prediction  
5. **Performance Evaluation** – Achieved an **R² score of 0.81** with a **MAPE of 13.17%**  

## Technologies Used  
- **Python**  
- **Pandas, NumPy** – Data processing  
- **Matplotlib, Seaborn, Plotly** – Data visualization  
- **Scikit-Learn** – Machine learning  
- **Pickle** – Model saving  

## Key Insights  
- Airlines and total stops significantly impact airfare  
- Jet Airways Business class has the highest average ticket price  
- Longer flight durations generally result in higher fares  

## How to Run  
1. Install dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```  
2. Run the notebook/script to preprocess data and train the model  
3. Use the trained model to predict ticket prices based on flight details  

## Project Structure  
```
📁 Aero_Predict  
 ┣ 📜 data_train.xlsx    # Dataset  
 ┣ 📜 Aero_Predict.ipynb  # Jupyter Notebook  
 ┣ 📜 model.pkl          # Saved ML model  
 ┣ 📜 README.md          # Project Documentation  
```

---
