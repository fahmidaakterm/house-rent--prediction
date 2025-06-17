# house-rent--prediction

## 🏡 House Price Predictor

A simple linear regression project that predicts the price of a house based on its area (in square feet). Built using Python and `scikit-learn`.

![Python](https://img.shields.io/badge/Python-3.9-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![ML](https://img.shields.io/badge/Machine%20Learning-Linear%20Regression-blueviolet)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Features

* Predict house prices using area as input
* Built with `scikit-learn` and `pandas`
* Lightweight and beginner-friendly
* Easily expandable to include more features (e.g., number of bedrooms, location)

---

## 📂 Project Structure

```
house-price-predictor/
├── main.py           # Main script for prediction
├── requirements.txt  # List of dependencies
└── README.md         # Project documentation
```

---

## 📊 Sample Dataset

| Area (sqft) | Price (Tk) |
| ----------- | ---------- |
| 1000        | 20000      |
| 1500        | 30000      |
| 2000        | 40000      |
| 2500        | 50000      |
| 3000        | 60000      |

---

## 🛠️ Installation

### ✅ Prerequisites

* Python 3.6 or higher
* pip (Python package manager)

### 📦 Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
python main.py
```

### 💬 Example Interaction:

```
Data Preview:
   Area  Price
0  1000  20000
1  1500  30000
2  2000  40000
3  2500  50000
4  3000  60000

Enter the area of the house in square feet:
2200

Predicted price: Tk 44,000.00
Predicted price: Tk 44,000
```

---

## 🧠 How It Works

1. Loads a simple dataset mapping area to price.
2. Trains a **Linear Regression** model using `scikit-learn`.
3. Accepts user input for house area.
4. Predicts the price based on the learned model.

---

## 📈 Algorithms Used

* **Linear Regression**
  Maps `Area` to `Price` using the equation:
  `Price = m × Area + b`

---

## 📄 requirements.txt

```
scikit-learn
pandas
```

---

## 🚀 Future Improvements

* Add support for more features (bedrooms, location, etc.)
* Load real-world datasets (CSV, API)
* Build a web interface (Streamlit/Flask)

---

## 📄 License

This project is for educational purpose only.

---

## 🙌 Acknowledgments

Thanks to `scikit-learn` and the open-source community.
