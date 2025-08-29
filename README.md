# 📱 Android Phone Price Predictor

A machine learning project that predicts the price of Android smartphones based on their specifications (RAM, storage, battery, display, etc.).

## 🔍 Overview

This project uses **Scikit-learn, Pandas, and NumPy** to train a regression model that estimates the price of Android smartphones.

* Input: Device specifications (e.g., RAM, storage, camera, processor, etc.)
* Output: Predicted price of the smartphone

The model achieves an accuracy of **\~88%** on the test dataset.

## ⚡ Features

* Data preprocessing and feature engineering with **Pandas**
* Machine learning model training with **Scikit-learn**
* Price prediction based on real-world smartphone specifications
* Error percentage calculation to evaluate predictions

## 🛠️ Tech Stack

* **Python 3**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**

## 📊 Example Predictions

### Motorola G85

* **Actual Price:** ₹16,099
* **Predicted Price:** ₹16,333.028
* **Error %:** \~1.45%

### Samsung Galaxy A35

* **Actual Price:** ₹20,534
* **Predicted Price:** ₹20,781.725
* **Error %:** \~1.20%

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/imtiyazallam07/smartphone-price-ml.git
cd smartphone-price-ml
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then run `Predictor.ipynb` to train the model and test predictions.

## 📂 Project Structure

```
.
├── Predictor.ipynb     # Main notebook with training & prediction
├── data/               # Dataset
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

## 📈 Model Performance

* Accuracy: **≤ 88%**
* Evaluation Metric: **Error % between predicted vs. actual price**

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## 📜 License

This project is licensed under the MIT License.
