
# 🛠️ Predictive Maintenance for CT Scanners using LSTM

A deep learning project that forecasts **CT scan equipment failure types** and **maintenance urgency levels** using multivariate time-series data. This pipeline leverages **LSTM neural networks**, smart data simulation, and classification transformation to drive predictive maintenance and reduce unplanned downtime.

---

## 🚀 Features

- ✅ Predicts **Failure Types** (multiclass classification)
- ✅ Estimates **Maintenance Urgency**: High / Medium / Low
- ✅ Uses **Keras TimeSeriesGenerator** for sequence modeling
- ✅ Applies **EarlyStopping** to prevent overfitting
- ✅ Simulates noisy, real-world sensor data (drift, missing values, outliers)
- ✅ Achieves ~**95% classification accuracy** on noisy datasets
- ✅ Visualizes model performance (confusion matrix, class distributions)

---

## 🧠 Model Overview

- Model: LSTM (Long Short-Term Memory)
- Input: Time-series sensor data (temperature, torque, wear, etc.)
- Output:
  - Failure Type (Multiclass: TWF, HDF, OSF, etc.)
  - Maintenance Urgency (High/Medium/Low)

---

## 📁 Project Structure

```
├── data/
│   └── realistic_noisy_maintenance_dataset.csv
├── notebooks/
│   └── model_training.ipynb
├── models/
│   └── lstm_classifier.h5
├── utils/
│   └── data_preprocessing.py
├── README.md
```

---

## ⚙️ How to Run

1. Clone this repo:
```bash
git clone https://github.com/your-username/ct-maintenance-lstm.git
cd ct-maintenance-lstm
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook notebooks/model_training.ipynb
```

---


## 🧪 Technologies Used

- Python, Pandas, NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter

---

## 🤖 Use Case

Ideal for teams in healthcare tech, industrial IoT, or manufacturing looking to:
- **Minimize equipment downtime**
- **Forecast failures proactively**
- **Make maintenance scheduling smarter**

---

## 📬 Contact

Have questions or want to collaborate?  
**[Your Name]** – [Your Email or LinkedIn/GitHub profile]
