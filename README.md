# 🌊 Flood Prediction Using Machine Learning

This project is a **Machine Learning-based Flood Prediction System** developed using **Python** and **Django**. The model predicts whether a flood may occur based on historical monthly rainfall-related data.

---

# 📌 Project Overview

The main objective of this project is to analyze historical flood-related data and predict flood occurrence using Machine Learning algorithms.

## Project Modules
- Data Preprocessing
- Data Visualization
- Feature Selection
- Machine Learning Model Training
- Model Saving
- Django Frontend Integration
- Prediction System

---

# 🚀 Technologies Used

## 🖥️ Frontend
- HTML
- CSS
- Bootstrap

## ⚙️ Backend
- Python
- Django

## 🤖 Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📂 Project Structure

```bash
FLOOD/
│
├── backend/
│   ├── data.csv
│   ├── Flood.ipynb
│   └── KNN.pkl
│
├── frontend/
│   ├── base/
│   ├── Flood/
│   ├── static/
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── index.html
│   │   ├── login.html
│   │   ├── logout.html
│   │   ├── result.html
│   │   └── signup.html
│   │
│   ├── db.sqlite3
│   ├── KNN.pkl
│   ├── manage.py
│   ├── py3.11.4.txt
│   └── requirements.txt
```

---

# 📊 Machine Learning Workflow

## 1️⃣ Dataset Collection
- Dataset collected from Kaggle
- Historical flood and rainfall-related data used

## 2️⃣ Data Preprocessing
- Handling missing values
- Removing duplicate values
- Data cleaning
- Feature extraction

## 3️⃣ Feature Selection
- Selecting input (X) and output (Y)
- Splitting dataset into train and test sets

## 4️⃣ Model Training

### Algorithms Used
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes (GNB)
- Support Vector Classifier (SVC)

### ✅ Accuracy Results

| Algorithm | Accuracy |
|----------|----------|
| KNN | 97% |
| SVC | 95% |
| GaussianNB | 87% |

## 5️⃣ Model Saving
- Best model saved using `pickle`
- Saved file: `KNN.pkl`

---

# 📈 Data Visualization

## Libraries Used
- Matplotlib
- Seaborn

## Visualizations
- Heatmaps
- Dataset analysis plots
- Flood occurrence patterns

---

# ⚡ Installation Steps

## 1️⃣ Clone the Repository

```bash
git clone <your-github-repository-link>
```

## 2️⃣ Navigate to Project Folder

```bash
cd FLOOD/frontend
```

## 3️⃣ Create Virtual Environment

```bash
python -m venv env
```

## 4️⃣ Activate Virtual Environment

### Windows
```bash
env\Scripts\activate
```

### Mac/Linux
```bash
source env/bin/activate
```

## 5️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

## 6️⃣ Run the Server

```bash
python manage.py runserver
```

---

# 🌐 Open in Browser

```bash
http://127.0.0.1:8000/
```

---

# 🧠 Prediction Process

1. User enters input values
2. Data is sent to backend
3. Saved KNN model predicts output
4. Result displayed on frontend

---

# 📷 Features

✅ User Authentication  
✅ Flood Prediction System  
✅ Machine Learning Integration  
✅ Django Web Interface  
✅ Saved ML Model  
✅ Data Visualization  

---

# 📌 Future Improvements

- Deploy project on cloud platform
- Add live rainfall API integration
- Improve dataset size
- Add deep learning models
- Real-time flood alerts

---

# 👩‍💻 Author

**Yuvapriya S.**  
AI & ML Engineer | Data Science Enthusiast

---

# ⭐ Conclusion

This project demonstrates the complete Machine Learning workflow from dataset collection to deployment using Django and Scikit-learn.

It is a beginner-friendly project for understanding:
- Machine Learning
- Data Preprocessing
- Model Training
- Deployment Integration

---
