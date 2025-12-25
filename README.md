# 📈 Stock Price Prediction using RNN

This project demonstrates **stock price prediction using Recurrent Neural Networks (RNN)** on historical time-series data. It was built as part of the **Deep Learning A-Z course on Udemy** to understand practical implementation of deep learning models for sequential data.

---

## 🧠 Project Overview

Stock prices are time-dependent and sequential in nature. In this project, an RNN model is trained on historical stock price data to learn temporal patterns and make future price predictions.

The model is trained on past data and evaluated on **unseen future data**, following correct time-series forecasting practices and avoiding data leakage.

---

## 📂 Dataset

* Historical stock price data (CSV format)
* Training data: Earlier time period (e.g., 2012–2016)
* Test data: Future period (e.g., January 2017)

> Note: Even if future data exists in the dataset, it is **not used during training** and is kept only for evaluation.

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* TensorFlow / Keras
* Recurrent Neural Networks (RNN)

---

## 🔄 Workflow

1. Data loading and preprocessing
2. Feature scaling for time-series data
3. Creating sequences using sliding window technique
4. Building and training the RNN model
5. Making predictions on unseen data
6. Visualizing real vs predicted stock prices

---

## 🏗️ Model Architecture

The model is built using a **Recurrent Neural Network (RNN)** to capture temporal dependencies in stock price data.

**Architecture Overview:**

* Input Layer: Time-series sequences created using a sliding window approach
* RNN Layer: Learns sequential patterns from historical stock prices
* Dense Layer: Maps learned features to the final prediction
* Output Layer: Predicts the next stock price value

**Typical Flow:**

```
Input Sequence → RNN Layer → Dense Layer → Predicted Price
```

This architecture is suitable for time-series forecasting where past values influence future outcomes.

---

## 📊 Results

* The model learns overall trends and temporal dependencies in stock prices
* Predictions are compared against real stock prices for evaluation
* Visualization helps analyze model performance

---

## 🚀 How to Run

1. Clone the repository
2. Install required libraries
3. Run the Jupyter Notebook or Python script step by step

```bash
git clone <your-repo-link>
cd stock-price-prediction-rnn
```

---

## 📌 Key Learnings

* Understanding time-series forecasting
* Proper train-test split for sequential data
* Avoiding data leakage
* Working with RNNs for real-world data

---

## 🔗 GitHub Repository

👉 Add your GitHub repository link here

---

## 🙌 Acknowledgements

* **Deep Learning A-Z™: Hands-On Artificial Neural Networks** (Udemy)

---

## 📬 Feedback

Feedback and suggestions are always welcome!
