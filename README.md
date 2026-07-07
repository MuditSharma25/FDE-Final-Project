# 🚦 Road Traffic Accident Prediction System (India)

A machine learning-based road accident severity prediction system developed using **Python**, **Scikit-Learn**, **Pandas**, and **NumPy**. The project analyzes historical road accident data from India to predict whether an accident is likely to be **Severe** or **Non-Severe**. It follows a complete data engineering and machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

---

## 🚀 Features

- 🚗 Predicts accident severity using machine learning
- 📊 Performs comprehensive exploratory data analysis (EDA)
- 🧹 Handles missing values and cleans raw accident data
- 🔄 Encodes categorical features using One-Hot Encoding
- 📈 Scales numerical features using StandardScaler
- 🤖 Trains and compares multiple machine learning models
- 📉 Evaluates models using accuracy and performance metrics
- 📍 Identifies accident trends based on weather, location, vehicle type, and road conditions

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Computation |
| Scikit-Learn | Machine Learning Models |
| Matplotlib | Data Visualization |
| Jupyter Notebook | Model Development & Analysis |

---

## 📂 Project Structure

```text
Road-Traffic-Accident-Prediction/
│
├── dataset/
│   └── road_accident_data.csv
│
├── notebooks/
│   └── Accident_Prediction.ipynb
│
├── models/
│   └── logistic_regression.pkl
│
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Road-Traffic-Accident-Prediction.git

cd Road-Traffic-Accident-Prediction
```

### 2. Create a Virtual Environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the Jupyter Notebook and execute all cells.

```bash
jupyter notebook
```

---

## 📖 How It Works

### Step 1: Data Collection

Historical road accident data is collected containing features such as:

- Weather Conditions
- Road Type
- Vehicle Type
- Time of Day
- Accident Location
- Traffic Conditions

### Step 2: Data Preprocessing

The dataset undergoes several preprocessing steps:

- Handle missing values
- Remove duplicate records
- Perform One-Hot Encoding for categorical variables
- Detect and treat outliers
- Scale numerical features using StandardScaler

### Step 3: Exploratory Data Analysis (EDA)

Different visualizations are created to understand accident patterns:

- Bar Charts
- Pie Charts
- Heatmaps
- Scatter Plots
- Correlation Analysis

### Step 4: Model Training

The processed dataset is split into training and testing sets, and multiple machine learning models are trained.

Models Used:

- Logistic Regression
- Decision Tree
- Random Forest

### Step 5: Model Evaluation

The models are evaluated using standard performance metrics.

Final Model:

- **Logistic Regression**
- **Accuracy:** Approximately **85%** (depending on the train-test split)

---

## 🧠 Machine Learning Models

### Logistic Regression

Used as the final prediction model because it achieved the highest accuracy while maintaining good generalization.

### Decision Tree

Used for comparison and understanding feature importance.

### Random Forest

Tested to improve prediction performance through ensemble learning.

---

## 📊 Exploratory Data Analysis Highlights

- 🌙 Higher accident frequency during evening and night hours
- 🌧️ Fog and rainy weather significantly increase accident severity
- 🛣️ Rural roads experience more severe accidents than urban roads
- 🏍️ Two-wheelers are involved in a large percentage of severe accidents
- 🚦 Road and weather conditions have a strong influence on accident outcomes

---

## 📈 Model Workflow

```text
Road Accident Dataset
          │
          ▼
Data Cleaning
          │
          ▼
Feature Engineering
          │
          ▼
One-Hot Encoding
          │
          ▼
Feature Scaling
          │
          ▼
Train-Test Split
          │
          ▼
Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Accident Severity Prediction
```

---

## 📦 Requirements

```text
python
pandas
numpy
scikit-learn
matplotlib
jupyter
```

---

## 🎯 Future Improvements

- 🌐 Deploy the model using Streamlit or Flask
- 📡 Integrate real-time weather and traffic data
- 🚗 Add GPS-based accident prediction
- ⚡ Experiment with XGBoost and LightGBM
- 🧠 Explore Deep Learning models for improved accuracy
- ☁️ Deploy the application on the cloud

---

## 👨‍💻 Author

**Mudit Sharma**

Engineering Student | AI & Machine Learning Enthusiast

- Skilled in Python, Machine Learning, Data Analysis, and Data Engineering
- Passionate about solving real-world problems using Artificial Intelligence and Machine Learning

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgements

- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- RV University
