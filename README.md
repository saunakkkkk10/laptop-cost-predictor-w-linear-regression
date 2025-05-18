

---

# 💻 Laptop Price Predictor

A machine learning web application that predicts the price of a laptop based on its specifications. The app uses a trained regression model to analyze key hardware and software features and outputs a reliable price estimate. This project demonstrates end-to-end ML deployment, from data preprocessing to web integration.

---

## 🚀 Features

* Predict laptop prices based on user inputs like RAM, CPU brand, GPU, SSD, HDD, screen size, and more
* Real-time predictions using a trained machine learning pipeline (`pipe.pkl`)

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy (Data manipulation)
* Scikit-learn (ML model building)
* Pickle (Model serialization)
* Shell scripting for deployment config

---

## 📁 Project Structure

```
├── laptop-price-predictor.ipynb   # Model training & evaluation
├── laptop_data.csv                # Dataset used for training
├── pipe.pkl                       # Trained machine learning pipeline
├── requirements.txt              # Dependencies for Streamlit app
├── setup.sh                      # Shell script for deployment setup
└── app.py (to be created)         # Streamlit web application script
```

---

## ⚙️ Installation & Run Locally

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd laptop-price-predictor
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```


   ```

---

## 📊 Dataset

The dataset (`laptop_data.csv`) contains laptop specs with their corresponding prices. Features include:

* Brand
* RAM
* Processor (CPU)
* Graphics (GPU)
* Storage (HDD/SSD)
* Operating System
* Weight, Touchscreen, etc.

---


---


