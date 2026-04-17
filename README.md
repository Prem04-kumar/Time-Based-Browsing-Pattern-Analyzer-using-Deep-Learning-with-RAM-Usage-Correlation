# ⏱️ Time-Based Browsing Pattern Analyzer  
### Deep Learning + RAM Usage Correlation for User Behavior Analytics  

---

## 📌 Overview  

This project analyzes personal browsing history along with system RAM usage to uncover meaningful behavioral patterns.  

It is built as a **data science + machine learning pipeline**, starting from raw browser data and ending with insights, anomaly detection, and visualizations.  

The notebook demonstrates a **step-by-step analytical workflow**, making it ideal for both learning and real-world applications.  

---

## 🔍 What This Project Does  

- ⏰ Extracts time-based browsing patterns (hour/day trends)  
- 🌐 Identifies frequently visited domains  
- 📊 Creates browsing sessions from raw logs  
- 🤖 Applies unsupervised learning (clustering)  
- ⚠️ Detects anomalies using Autoencoder  
- 💾 Analyzes RAM usage vs browsing behavior  
- 📈 Generates visual insights and patterns  

---

## 🎯 Objectives  

- Understand user browsing habits over time  
- Group similar browsing sessions using ML  
- Detect unusual or abnormal behavior  
- Correlate system resource usage (RAM) with browsing activity  
- Provide data-driven behavioral insights  

---

## 🧠 Notebook Workflow  

### 1️⃣ Data Loading  
- Load browsing history dataset  
- Load RAM usage logs  

### 2️⃣ Data Preprocessing  
- Clean URLs  
- Extract domain names  
- Handle missing values  
- Format timestamps  

### 3️⃣ Feature Engineering  
**⏰ Time-Based Features**
- Hour of browsing  
- Day of week  
- Activity frequency  

### 4️⃣ Sessionization  
- Convert raw browsing logs into user sessions  
- Group activity based on time gaps  

### 5️⃣ Exploratory Data Analysis (EDA)  
- Browsing frequency analysis  
- Domain usage trends  
- Time-based activity distribution  

### 6️⃣ Machine Learning (Clustering)  
- Apply **KMeans**  
- Identify user behavior patterns  

### 7️⃣ Deep Learning (Anomaly Detection)  
**🤖 Autoencoder Model**
- Learns normal browsing patterns  
- Detects anomalous sessions  

### 8️⃣ RAM Usage Correlation  
- Merge browsing + RAM datasets  
- Analyze:
  - High RAM usage periods  
  - Correlation with browsing activity  

### 9️⃣ Visualization & Insights  
- Time-based charts  
- Cluster plots  
- RAM usage trends  
- Behavioral insights  

---

## 📊 Key Outputs  

- 📁 Cleaned browsing dataset  
- 📁 Session-based dataset  
- 📊 Clustered browsing sessions  
- ⚠️ Anomaly detection results  
- 📈 Visual analytics  

---

## 🛠️ Tech Stack  

| Category            | Tools                          |
|--------------------|--------------------------------|
| Programming        | Python                         |
| Data Processing    | Pandas, NumPy                  |
| Visualization      | Matplotlib, Seaborn            |
| Machine Learning   | Scikit-learn                   |
| Deep Learning      | TensorFlow / Keras             |
| Notebook           | Jupyter                        |
| System Monitoring  | psutil                         |

---

## 🚀 How to Run  

### 1️⃣ Install Dependencies  
```bash
pip install -r requirements.txt


## 👨‍💻 Author
A. Prem Kumar
