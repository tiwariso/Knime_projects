# 🚗 Road Accident Impact Analysis and Prediction

## 📌 Project Overview
This project analyzes road traffic accident data and predicts **accident severity** using machine learning in KNIME Analytics Platform.

The workflow performs **data preprocessing, feature transformation, model training, prediction, and visualization**.  
An interactive dashboard is also created to analyze accident patterns.

The main goal is to understand how factors such as **weather conditions, lighting conditions, driver experience, and collision type** influence accident severity.

---

# 🎯 Objectives
- Analyze road accident data
- Identify factors affecting accident severity
- Build machine learning models to predict accident severity
- Create an interactive dashboard for visualization
- Compare Decision Tree and Random Forest models

---

# 📊 Dataset

The dataset used in this project is the **Road Traffic Accidents dataset** obtained from Kaggle.

### Features
- Age_band_of_driver
- Sex_of_driver
- Educational_level
- Driving_experience
- Weather_conditions
- Light_conditions
- Type_of_collision
- Vehicle_movement
- Pedestrian_movement
- Cause_of_accident

### Target Variable
**Accident_severity**

---

# 🛠 Tools & Technologies

- KNIME Analytics Platform
- Machine Learning
- Data Visualization
- Dashboard Design

---

# ⚙️ Workflow

### 1️⃣ Data Loading
The dataset is loaded using the **CSV Reader node**.

### 2️⃣ Data Cleaning
Missing values are handled using the **Missing Value node**.

### 3️⃣ Feature Transformation
Categorical columns are converted into numerical format using **One to Many encoding**.

### 4️⃣ Data Splitting
The dataset is divided into:
- **70% Training Data**
- **30% Testing Data**

using the **Partitioning node**.

### 5️⃣ Model Training
Two machine learning models are used:

- Decision Tree
- Random Forest

### 6️⃣ Prediction
Models generate predictions using **Predictor nodes**.

### 7️⃣ Model Evaluation
The **Scorer node** is used to evaluate performance and generate:

- Accuracy
- Confusion Matrix

### 8️⃣ Dashboard Creation
Visualization nodes used:

- Bar Chart
- Pie Chart
- Table View

These nodes are combined inside a **Component** to create an interactive dashboard.

---

# 📈 Data Analysis

The project analyzes:

- Distribution of accident severity
- Impact of weather conditions
- Influence of light conditions
- Role of driver experience
- Comparison of predicted vs actual severity

---

# 📊 Dashboard

The dashboard displays:

- Accident severity distribution
- Weather condition analysis
- Light condition analysis
- Model prediction results

---

# 📂 Project Structure

```
Road-Accident-Analysis
│
├── dataset
│   └── cleaned.csv
│
├── workflow
│   └── knime_workflow.knwf
│
├── screenshots
│   └── dashboard.png
│
└── README.md
```

---

# 🚀 How to Run the Project

1. Install **KNIME Analytics Platform**
2. Download or clone this repository
3. Open KNIME
4. Import the workflow
5. Load the dataset (`cleaned.csv`)
6. Execute the workflow
7. Open the dashboard component

---

# 📌 Results

The machine learning models successfully predicted accident severity.

Key influencing factors include:
- Weather conditions
- Light conditions
- Driver experience
- Type of collision

Random Forest produced more stable predictions compared to Decision Tree.

---

# 📚 Future Improvements

- Use larger accident datasets
- Apply advanced machine learning algorithms
- Add geographic accident analysis
- Deploy dashboard as a web application

---

# 👨‍💻 Author

**Siddharth Tiwari**  
B.Tech Computer Science Engineering.
