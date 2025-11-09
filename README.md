# 🏈 NFL Drive Success Analysis

### 📘 Overview
Predictive analysis of NFL offensive drive outcomes from 2015–2024 using play-by-play data.  
This project explores which offensive factors — like yards gained, rushing success, and efficiency — best predict whether a drive ends in points.

### 🎯 Objective
Identify the key offensive metrics that drive scoring success and quantify their impact using logistic regression.

### 📂 Dataset
- Source: [`nfl_data_py`](https://pypi.org/project/nfl-data-py/) (built on nflfastR)
- Seasons: 2015–2024
- Aggregated to **drive-level** metrics:
  - Plays, yards, average EPA  
  - Rush success rate, pass rate, penalty rate  
  - Binary target: `success` (drive ended in points)

### ⚙️ Methods
- Data Cleaning & Aggregation (Python, pandas)
- Exploratory Data Analysis (Seaborn, Matplotlib)
- Logistic Regression (scikit-learn)
- Evaluation: AUC = **0.93**, Accuracy = **0.89**

### 📊 Key Insights
- Drives with **higher rush success rate** and **average EPA** strongly correlate with scoring.  
- **Penalties** slightly reduce scoring odds but have limited aggregate correlation.  
- **Balanced offenses** outperform pass-heavy ones in sustained drives.

### 📈 Visuals
Include images like:
- Correlation heatmap  
- ROC Curve  
- Feature importance (bar chart)  
- Confusion matrix  

### 🚀 Next Steps
- Add contextual features like field position and game state  
- Experiment with non-linear models (Random Forest, XGBoost)  
- Build a Streamlit dashboard for interactive exploration  

### 👤 Author
**Srihith Duggi**
B.S in Mathematics and Informatics, University of Texas at Austin
M.S. in Artificial Intelligence, University of Texas at Austin  
📍 Austin, TX  
🔗 [LinkedIn](https://www.linkedin.com/in/srihithduggi/) | [GitHub](https://github.com/SrihithDuggi)
