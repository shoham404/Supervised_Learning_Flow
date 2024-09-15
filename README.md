# 🎯 Breast Cancer Predictive Modeling
## 📌 Project Overview
This project aims to develop a predictive model to classify breast cancer as either benign or malignant. Using a structured machine learning approach, the project applies various preprocessing techniques, feature engineering, and evaluates the performance of different classifiers, specifically Support Vector Machines (SVM) and Naive Bayes. The dataset used in this project comprises clinical features of breast cancer cases, allowing for robust training and testing of the models.

## 📊 Dataset
The dataset includes features such as mean radius, texture, perimeter, area, and smoothness, which are crucial for distinguishing between benign and malignant cancer types. Data is split into a training set for model development and a testing set for model evaluation.

## 🔍 Methodology
### 🧪 Preprocessing
The data undergoes several preprocessing steps, including normalization and scaling, to ensure that the machine learning algorithms function optimally. We employ **StandardScaler** and **MinMaxScaler** to standardize the dataset features.

### ⚒️ Model Building and Evaluation
We explore two main classifiers:

* **Naive Bayes:** A simple probabilistic classifier based on applying Bayes' theorem with strong independence assumptions between the features.
  
* **Support Vector Machine (SVM):** A powerful classifier that works well in high-dimensional spaces and is effective in cases where the number of dimensions exceeds the number of samples.
  
Hyperparameters for these models are fine-tuned using **GridSearchCV**, which systematically works through multiple combinations of parameter tunes, cross-validating as it goes to determine which tune gives the best performance.

### 📈 Metrics
Model performance is evaluated using the F1-score, precision, recall, and accuracy metrics. These metrics provide insights into the model's ability to classify the cancer types accurately.

## 📝 Results
The models demonstrate promising results, with the SVM classifier achieving particularly high scores in precision and recall, suggesting its effectiveness in distinguishing between the cancer types. A detailed classification report is provided to review the model's performance comprehensively.

## 🚀 How to Use This Repository

* Clone the repository to your local machine and download the two CSV files.
* Ensure you have Python installed, along with libraries such as **pandas**, **numpy**, **matplotlib**, **seaborn**, **scikit-learn**.
* Run the Jupyter Notebook to view the analysis and model building process.
