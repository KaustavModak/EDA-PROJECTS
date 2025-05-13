
# Flight Price Prediction

This project focuses on predicting flight ticket prices using machine learning. The dataset includes various features such as airline, source, destination, departure time, arrival time, total stops, and more.

## 📁 Files Included

- `flight_price.ipynb`: Jupyter Notebook containing the full data analysis, feature engineering, model training, and evaluation pipeline.
- `flight_price.xlsx`: Dataset used for training and testing the model.

## 📊 Dataset Description

The dataset (`flight_price.xlsx`) includes the following columns:

- **Airline**: The airline operating the flight
- **Source**: The departure city
- **Destination**: The arrival city
- **Route**: Route taken by the flight
- **Dep_Time**: Departure time
- **Arrival_Time**: Arrival time
- **Duration**: Total duration of the flight
- **Total_Stops**: Number of stops
- **Additional_Info**: Additional information
- **Price**: Target variable (flight price)

## 🧪 Project Workflow

1. **Data Preprocessing**  
   - Handling null values  
   - Extracting and converting date/time features  
   - Encoding categorical features

2. **Feature Engineering**  
   - Duration parsing  
   - Label/One-Hot encoding  
   - Feature scaling

3. **Modeling**  
   - Multiple regression models used (e.g., Linear Regression, Random Forest)  
   - Hyperparameter tuning  
   - Performance evaluation using RMSE, MAE, R²

4. **Evaluation**  
   - Model comparison  
   - Visualizations  
   - Final model selection

## 🛠️ Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- openpyxl (for reading `.xlsx` files)

Install dependencies with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

## 🚀 How to Run

1. Clone the repository or download the files.
2. Open the `flight_price.ipynb` notebook.
3. Run all cells to reproduce the analysis and model training.

## 📌 Notes

- Make sure `flight_price.xlsx` is in the same directory as the notebook.
- The model predictions can be further improved with advanced feature engineering and model optimization.

## 📬 Contact

For questions or feedback, feel free to reach out.
