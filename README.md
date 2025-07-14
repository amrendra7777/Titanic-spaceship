# 🚀 Spaceship Titanic - Machine Learning Classification

This is a solution for the  
[Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic)  
Kaggle competition. We predict whether passengers were transported  
to another dimension using classical ML techniques.

---

## 🧠 Overview

- **Target:** `Transported` (True / False)  
- **Key features:**  
  - `HomePlanet`  
  - `CryoSleep`  
  - `Cabin`  
  - `Destination`  
  - …and more  
- **Pipeline:**  
  1. EDA & imputation  
  2. One-hot encoding of categoricals  
  3. (Optional) scaling  
  4. Model training & tuning (RF, AdaBoost)  
  5. Evaluation (accuracy, confusion matrix, Kaggle score)

---

## 📁 Project Structure

    ├── titanic-env/         # Python virtual environment (excluded via .gitignore)
    ├── .gitignore           # Specifies files and folders to ignore in version control
    ├── model.ipynb          # Main Jupyter notebook for model training and evaluation
    ├── README.md            # Project overview and setup instructions
    ├── requirements.txt     # Python dependencies for reproducibility
    ├── train.csv            # Training dataset from Kaggle
    └── test.csv             # Test dataset from Kaggle


---

## ⚙️ Setup Instructions

```bash
# 1. Clone this repo
git clone https://github.com/YOUR-USERNAME/spaceship-titanic-ml.git
cd spaceship-titanic-ml

# 2. Create & activate a virtual environment
python3 -m venv titanic-env
source titanic-env/bin/activate   # On Windows: titanic-env\Scripts\activate

# 3. Install required packages
pip install -r requirements.txt

# 4. Start Jupyter Notebook
jupyter notebook
