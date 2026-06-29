# 🛸 UFO Sighting Country Predictor

A Flask web application that utilizes a Logistic Regression classification model to predict the country most likely to have reported a UFO sighting based on spatial and temporal inputs.

The underlying model evaluates evaluations with an accuracy score of approximately **95.0%**.

---

## 🚀 Features & Variables

The application processes three independent operational variables to classify and determine the geographic source:

* **Seconds:** The duration of the observed UFO sighting (bounded between 1 and 60 seconds).
* **Latitude:** The geographic latitude coordinate of the sighting.
* **Longitude:** The geographic longitude coordinate of the sighting.

### Target Classification Class
* **Country:** The predicted country of the sighting, mapped from the encoded classification outputs: `Australia`, `Canada`, `Germany`, `UK`, or `US`.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3
* **Backend Framework:** Flask (Python)
* **Machine Learning Core:** Scikit-Learn, NumPy, Pandas
* **Model Serialization:** Pickle

---

## ⚙️ Installation & Local Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
cd YOUR_REPOSITORY_NAME
