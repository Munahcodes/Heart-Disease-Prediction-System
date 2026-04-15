# Heart Disease Prediction

This project explores how machine learning can be used to predict the likelihood of heart disease based on patient health data. It’s built around the idea of using common clinical features to make a simple but meaningful risk prediction.

The dataset used includes attributes such as age, sex, chest pain type, blood pressure, cholesterol levels, heart rate, and ECG results. I started by cleaning and exploring the data to better understand how these variables relate to heart disease outcomes. This helped guide the preprocessing and feature selection steps.

For the modeling phase, I tested multiple algorithms including Logistic Regression, Random Forest, and K-Nearest Neighbors (KNN). The models were evaluated using accuracy, precision, recall, and F1-score to ensure the predictions were not just correct overall, but also reliable across different classes.

The structure of the project is kept straightforward so it’s easy to navigate and build upon. It reflects a typical machine learning workflow from data preparation to model evaluation, and it can be expanded with more advanced techniques or deployed into a user-facing application.

To run the project:

pip install -r requirements.txt  
python app.py  

Like the breast cancer model, this project is intended for educational purposes and should not be used as a substitute for professional medical advice or diagnosis.
