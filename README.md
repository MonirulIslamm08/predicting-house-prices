# 🏡 Predicting House Prices

## 📌 Project Overview
This project aims to predict house prices using machine learning techniques. It is based on a dataset containing various house attributes such as square footage, number of bedrooms and bathrooms, location, and more. The goal is to build a model that accurately estimates the price of a house based on these features.

## 📂 Dataset
The dataset used for this project is `kc_house_data.csv`, which contains:
- **21 features** including `price`, `sqft_living`, `bedrooms`, `bathrooms`, `floors`, `waterfront`, `view`, `condition`, and more.
- **21,613 records** of house sales.
- No missing values in the dataset.

## 🛠 Technologies Used
- **Python**
- **Pandas & NumPy** (for data manipulation)
- **Matplotlib & Seaborn** (for visualization)
- **Scikit-learn** (for preprocessing & model selection)
- **TensorFlow & Keras** (for deep learning model)

## 🚀 Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/MonirulIslamm08/predicting-house-prices.git
   cd predicting-house-prices
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run Jupyter Notebook**
   ```sh
   jupyter notebook
   ```

## 📊 Exploratory Data Analysis (EDA)
Key insights from the data analysis:
- `sqft_living` has the highest correlation with `price`.
- Waterfront properties tend to have higher prices.
- Older houses have a lower average price unless renovated.

## 🔥 Model Training
- **Preprocessing:**
  - Dropped irrelevant columns (`id`, `date`, `zipcode`).
  - Scaled features using `MinMaxScaler`.
- **Neural Network Model:**
  - **3 hidden layers**, each with 19 neurons and ReLU activation.
  - **Adam optimizer** and **Mean Squared Error (MSE)** as the loss function.
  - **300 epochs** with batch size 128.
- **Training Performance:**
  - Gradual reduction in loss over epochs.
  - Further optimization possible through hyperparameter tuning.

## 📈 Results & Future Work
✅ The model provides reasonable predictions but can be improved by:
- Experimenting with different architectures and optimizers.
- Feature engineering (e.g., creating new meaningful features).
- Trying other ML models (e.g., Decision Trees, Random Forest, XGBoost).

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo, make changes, and submit a pull request.

## 📜 License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## 📬 Contact
📧 **Monirul Islam**  
🔗 [GitHub Profile](https://github.com/MonirulIslamm08)
