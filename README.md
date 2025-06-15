## NBA Rookie Retention Prediciton

### 1. Goal  
To predict whether an NBA rookie will remain in the league after five years based on their first-season performance metrics.

### 2. Dataset  
Source: Provided [nba.csv](https://github.com/yehyifan/NBA_Rookie_Retention_Prediction/blob/main/nba.csv) dataset

- Number of Instances: Multiple rows representing individual rookies  
- Key Columns:  
  - `games_played`, `minutes_played`, `points_scored`, `rebounds`, `assists`, etc.  
  - `5yrs`: Binary target variable indicating whether a player stayed in the NBA after five years

### 3. Tools and Algorithms  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`  
- Machine Learning:  
  - Logistic Regression  
  - Feature Selection Techniques  
  - Threshold Tuning  
  - Confusion Matrix & Precision-Recall Evaluation

### 4. Procedure  
- Data Preprocessing  
- Exploratory Data Analysis  
- Feature Selection using RFE and SelectKBest  
- Model Training and Evaluation  
- Visualization of Feature Importance and Model Metrics

### 5. Results  
Please explore the full [notebook](https://colab.research.google.com/drive/1og8n16JiEnYU5Fj0SgaxQA208Um7Sh4k) for complete code and detailed results.
