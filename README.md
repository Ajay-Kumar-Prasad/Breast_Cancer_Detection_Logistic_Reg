# 🧠 Breast Cancer Detection using Logistic Regression

This project utilizes **Logistic Regression** to predict whether a tumor is benign or malignant based on features extracted from the Breast Cancer Wisconsin dataset. The model is trained, evaluated, and saved for future predictions.

---

## 📁 Project Structure

- `cancerdetection.ipynb`: Jupyter Notebook containing data preprocessing, model training, evaluation, and saving steps.
- `data1.csv`: Dataset used for training and testing the model.
- `log_classifier.pkl`: Serialized Logistic Regression model.
- `scaler.pkl`: Serialized StandardScaler used for feature scaling.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project documentation.
- `.gitignore`: Specifies files to ignore in the repository.
- `LICENSE`: MIT License.

---

## 📊 Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Attributes**:
  - 30 numeric features (mean, standard error, and worst for radius, texture, perimeter, area, etc.)
  - `diagnosis` column: `M` = malignant, `B` = benign

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Ajay-Kumar-Prasad/Breast_Cancer_Detection_Logistic_Reg.git
cd Breast_Cancer_Detection_Logistic_Reg
