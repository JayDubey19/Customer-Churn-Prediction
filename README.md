# **📊 Customer Churn Prediction**

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)  


## **📝 Overview**

Customer churn prediction is a machine learning project aimed at identifying customers likely to leave a service or subscription. By analyzing historical data, the model predicts churn probability, enabling businesses to implement retention strategies and improve customer satisfaction.

This repository provides a complete pipeline for data preprocessing, model building, evaluation, and insights visualization.

---

## **✨ Features**

- 🔍 **Exploratory Data Analysis (EDA):** Gain insights from data using visualizations and statistical summaries.
- ⚙️ **Data Preprocessing:** Handle missing values, encode categorical features, and normalize data.
- 🤖 **Modeling:** Train and evaluate various machine learning models for churn prediction.
- 📈 **Evaluation Metrics:** Assess model performance using accuracy, precision, recall, and F1-score.
- 🚀 **Deployment-ready Code:** The trained model is serialized and ready for deployment.

---

## **🔧 Technologies Used**

- **Programming Language:** 🐍 Python  
- **Libraries:**  
  - `pandas`, `numpy` - Data manipulation  
  - `matplotlib`, `seaborn` - Data visualization  
  - `scikit-learn` - Machine learning algorithms  
  - `joblib` - Model serialization  

---

## **📦 Installation**

1. Clone the repository:  
```bash
git clone https://github.com/JayDubey19/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
```
2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```

## **📂 Dataset**

The project uses a publicly available dataset for churn prediction. You can download the dataset from [Kaggle](https://www.kaggle.com/) or use your own. Ensure the dataset follows the structure below:

| CustomerID | Feature1 | Feature2 | ... | Churn |  
|------------|----------|----------|-----|-------|  

> **⚠️ Note:** Place your dataset in the `data/` directory and update the file path in the code.

## **🚀 Usage**

### 🔧 **Data Preprocessing**: 
Run the preprocessing script to clean and prepare the data:  
```bash
python preprocess.py
```
### 🤖 **Model Training**:
Train the churn prediction model:
```bash
python train_model.py
```
### 📊 **Model Evaluation**:
Evaluate the trained model using test data:
```bash
python evaluate.py
```
### 📂 **Prediction**:
Use the trained model to make predictions on new data:
```bash
python predict.py --input-file new_data.csv
```
## **🌐 Streamlit App Demo**

You can explore the interactive **Customer Churn Prediction** app built with Streamlit. The app allows you to upload data and get real-time predictions on customer churn.

### **Running the Streamlit App Locally**  
To run the app on your local machine:

1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/JayDubey19/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
The app will open in your browser at http://localhost:8501.
#### Streamlit App: Customer will churn
![Image 1](images/confusion_matrix.png)
#### Streamlit App: Customer will not churn
![Image 2](images/confusion_matrix.png)


## **📊 Results**

- **Best Model:** 🌟 Regression  
- **Accuracy:** 95%  
- **Precision:** 92%  
- **Recall:** 90%  
- **F1-Score:** 91%

## **Visualizations of the Model's Output:**

#### Model Evaluation: Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

#### Feature Importance
![Feature Importance](images/feature_importance.png)

## **🤝 Contributing**

Contributions are welcome! 🎉 If you have suggestions for improvements or find a bug, feel free to fork the repository and submit a pull request.

### How to Contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request to the main repository.

Your contributions help make this project better, and all contributions are greatly appreciated! 🙌


> **Note:** These images are generated during model evaluation and visualization stages.




