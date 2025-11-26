# HR Analytics – Job Change Prediction of Data Scientists  
Predicting the likelihood of job change using machine learning and analytics.

## 📌 Overview
This project analyzes the **HR Analytics: Job Change of Data Scientists** dataset from Kaggle to build predictive models that help Human Resources teams identify candidates who are likely to switch jobs.  

Through data cleaning, exploratory data analysis (EDA), and machine learning experimentation, the project uncovers insights into the factors influencing job transitions within the data science talent pool.

**Dataset Source:**  
Kaggle — HR Analytics: Job Change of Data Scientists  
(https://www.kaggle.com/datasets/arashnic/hr-analytics-job-change-of-data-scientists/)

---

## 📂 Dataset Description
The dataset contains candidate demographics, experience details, education background, and job-change intent.

| Column | Description |
|--------|-------------|
| `enrollee_id` | Unique candidate ID |
| `city` | City code |
| `city_development_index` | Index representing development level of the city |
| `gender` | Candidate gender |
| `relevent_experience` | Whether the candidate has relevant experience |
| `enrolled_university` | Enrollment type |
| `education_level` | Highest education level |
| `major_discipline` | Academic major |
| `experience` | Total years of experience |
| `company_size` | Size of previous employer |
| `company_type` | Type of previous employer |
| `last_new_job` | Years since last job change |
| `training_hours` | Hours of training completed |
| `target` | **1 = looking for a job change**, **0 = not looking** |

---

## 🎯 Project Objectives
- Clean, preprocess, and transform structured HR data  
- Conduct in-depth EDA to understand hiring and job-change patterns  
- Train and evaluate multiple machine learning models  
- Identify key features influencing job-change decisions  
- Provide actionable insights for HR decision-making  

---

## 🧹 Data Preprocessing
The project includes:
- Handling missing values  
- Converting categorical variables using label/one-hot encoding  
- Normalizing numeric features  
- Cleaning inconsistent entries (experience ranges, job gaps, etc.)  
- Outlier detection and removal  
- Train-test splitting  

---

## 📊 Exploratory Data Analysis (EDA)
Insights and visualizations include:
- Education level distribution  
- Gender imbalance analysis  
- Training hours vs job-change probability  
- Experience and job-change correlation  
- City development index comparison  
- Company size/type impact on job-change tendency  

Charts include bar plots, histograms, KDE plots, heatmaps, boxplots, and pairplots.

---

## 🤖 Machine Learning Models
Models implemented:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- LightGBM (optional)  
- Artificial Neural Network (optional)

Model evaluation metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

A comparison table is provided to identify top-performing models.

---

## 🏆 Key Findings
- Lower **city development index** is associated with higher job-change likelihood.  
- Candidates with **more training hours** tend to seek new opportunities.  
- Lack of **relevant experience** increases job-switch intention.  
- **Company size** and **last_new_job** show strong predictive power.  
- Ensemble models (Random Forest, XGBoost) generally outperform simpler models.

---

## 🛠️ Tech Stack
- Python 3.10+  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-Learn  
- XGBoost / LightGBM  

---

## 🚀 How to Run the Project
```bash
# Clone the repository
git clone https://github.com/your-username/hr-analytics-job-change.git

# Enter the project directory
cd hr-analytics-job-change

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook