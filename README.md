# Obesity_Prediction
"This project involves building a multiclass classification model to predict obesity levels using features from a dataset, and deploying the trained model as an API with a Streamlit app for interactive user input and real-time predictions."

<img src="https://github.com/rpjinu/Obesity_Prediction/blob/main/project_img.png">

# Obesity Classification with Machine Learning 🧑‍⚕️🍏 

This project involves building a **multiclass classification model** to predict different **obesity levels** (Obesity_Type_I, Obesity_Type_III, Obesity_Type_II, etc.) based on various health and lifestyle features. The model is deployed as a **Streamlit web application** for easy interaction and real-time predictions. 🌐💻

## Features of the Project 🚀

- **Multiclass Classification**: Predicting multiple obesity levels.
- **Models Used**: XGBoost, Random Forest, and SVM.
- **Deployment**: Streamlit app that allows users to input data and get real-time predictions.
- **Accuracy Evaluation**: Comparing models based on their accuracy scores to determine the best-performing model. 📊

## Key Steps in the Project 🛠️

### 1. **Data Preprocessing** 🧹
   - Handling missing values and categorical features.
   - Splitting the dataset into training and test sets.

### 2. **Model Training** 🧠
   - Implemented and trained models: **XGBoost**, **Random Forest**, and **SVM**.
   - Evaluated models based on **accuracy** using cross-validation.

### 3. **Streamlit Web App** 📱
   - A user-friendly web application built with **Streamlit** to allow input of health features and predict obesity levels in real-time.
   - Displays model predictions and evaluation metrics.

## Installation 🛠️

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/obesity-classification.git
    cd obesity-classification
    ```

2. **Install required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

## Dataset 📊

The dataset includes features like age, weight, cholesterol level, physical activity, and more. The target column is the **Obesity** level, which consists of various classes:

- **Obesity_Type_I** 🏋️‍♂️
- **Obesity_Type_III** 🏋️‍♀️
- **Obesity_Type_II** 🍔
- **Overweight_Level_II** 🥗
- **Normal_Weight** 🏃‍♂️
- **Overweight_Level_I** 🥑
- **Insufficient_Weight** 🍏

## Model Evaluation 📈

- **XGBoost**: Best for handling structured data and capturing non-linear relationships.
- **Random Forest**: Robust and easy to interpret, but slightly less accurate than XGBoost.
- **SVM**: Suitable for smaller datasets but less efficient for large-scale data.

## Usage 👨‍💻

1. Enter your health data into the **Streamlit app**.
2. Get predictions on the obesity level based on the provided features.
3. View model performance and accuracy metrics directly from the app.

## Conclusion 🎯

This project provides an easy way to predict obesity levels using machine learning, and it showcases how to deploy a model with **Streamlit** for user interaction. It's an ideal tool for healthcare providers or individuals who want to predict obesity based on lifestyle data. 

---

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

