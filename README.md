# Car_Price_Prediction_ML_Project

Live Application link in Below

https://car-price-prediction-model-app.streamlit.app/




# 🚗 Car Price Prediction ML Project

## 📋 Description

The **Car Price Prediction ML Project** is a machine learning–based web application that predicts the selling price of a car based on its features such as brand, year of manufacture, fuel type, transmission, mileage, and other specifications.

The project aims to help users (buyers, sellers, and dealers) estimate the fair market value of a car by leveraging data-driven insights. It demonstrates the application of **Regression Algorithms** in real-world business use cases, specifically in the automobile resale domain.

---

## 🚀 Features

* 🧠 Predicts car prices using a trained regression model
* 💻 Interactive web interface built with **Streamlit**
* ⚙️ Accepts multiple car attributes as inputs
* 📊 Displays instant prediction results
* 💾 Model trained on real-world car dataset for better accuracy

---

## 🧩 Tech Stack

* **Programming Language:** Python
* **Framework:** Streamlit
* **Libraries Used:**

  * Pandas
  * NumPy
  * Scikit-learn
  * Matplotlib / Seaborn
  * Pickle (for saving and loading models)

---

## 🧠 How It Works

1. The user inputs car details such as:

   * Car Company / Brand
   * Year of Manufacture
   * Fuel Type (Petrol / Diesel / CNG / Electric)
   * Transmission Type (Manual / Automatic)
   * Kilometers Driven
   * Owner Type
   * Engine & Mileage details
2. The app processes and encodes the input data.
3. The trained machine learning model (saved as `.pkl` file) predicts the estimated selling price.
4. The result is displayed instantly on the Streamlit interface.

---

## ⚙️ Setup and Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/car-price-prediction-ml-project.git
   cd car-price-prediction-ml-project
   ```
2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application:

   ```bash
   streamlit run app.py
   ```

---

## 📈 Model Training (Optional)

If you wish to retrain the model:

1. Open `model_training.ipynb`.
2. Load and explore the dataset (e.g., `car_data.csv`).
3. Perform preprocessing (encoding, scaling, feature selection).
4. Train using regression algorithms such as:

   * Linear Regression
   * Random Forest Regressor
   * XGBoost Regressor
5. Save the trained model:

   ```python
   import pickle
   pickle.dump(model, open('car_model.pkl', 'wb'))
   ```

---



---

## 📚 Future Enhancements

* Integrate real-time market data for dynamic pricing
* Add visual dashboards for car price trends
* Deploy the app on **Streamlit Cloud / Heroku / AWS**
* Improve model accuracy using ensemble and tuning methods

---

## 👨‍💻 Author

**Developed by:** Om Bankar
**Email:** [ombankar25@gmail.com](mailto:ombankar25@gmail.com)
