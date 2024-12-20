# Diabetes Prediction with ANN
This project leverages an Artificial Neural Network (ANN) to predict diabetes diagnoses using a dataset provided by [National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK)](https://www.niddk.nih.gov/)
. The model demonstrates how machine learning can effectively support early detection and management of diabetes, a chronic condition with significant health implications.

**Project Overview**
The primary objective of this project is to develop a robust ANN that predicts whether a patient has diabetes based on diagnostic measurements. The dataset comprises nine features, including physiological measurements and medical history, and is specific to females of Pima Indian heritage aged at least 21 years. Through systematic model development, optimization, and evaluation, this project delivers an accurate and interpretable prediction model.

**Methodology**
  1.	Data Preprocessing:
      o	Addressed missing values for features such as SkinThickness and Insulin by replacing zeros with the respective column means.
      o	Performed exploratory data analysis (EDA) to understand feature distributions, correlations, and outliers.
  2.	Model Development:
      o	Constructed an initial ANN using TensorFlow and Keras with one hidden layer.
      o	Applied hyperparameter tuning and added batch normalization and dropout layers to improve performance and prevent overfitting.
      o	Integrated advanced techniques such as early stopping and learning rate adjustments to enhance model generalization.
  3.	Model Evaluation:
      o	Used cross-validation for robust performance assessment.
      o	Final model achieved a test accuracy of 77.27%, demonstrating balanced predictions with precision and recall improvements.
    	
**Results**
  1.	Final Model Performance:
      o	Accuracy: 77.27%
      o	True Negative Rate: 85%
      o	True Positive Rate: 34%
      o	False Positive Rate: 14%
      o	False Negative Rate: 21%
  2.	Significant predictors of diabetes include glucose levels, BMI, and age, as identified through correlation analysis.
  
**Key Features of the Project**
  1.	Data Cleaning and Preprocessing: Ensured dataset integrity by addressing missing values and balancing features.
  2.	Advanced Model Optimization: Used techniques like batch normalization and dropout for improved model robustness.
  3.	Comprehensive Evaluation: Balanced evaluation metrics across diabetic and non-diabetic predictions.
  
**Dependencies**
Ensure you have the following libraries installed to run the project:
  1.	Python 3.7 or later
  2.	TensorFlow
  3.	Keras
  4.	Pandas
  5.	NumPy
  6.	Matplotlib
  7.	Scikit-learn
  
**Dataset**
The dataset used in this project can be accessed from [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database). Please download the data and place it in the appropriate directory before running the code.

**Ideas for Further Research**
  1.	Feature Engineering: Introduce new features or interactions to improve predictive accuracy.
  2.	Ensemble Models: Explore ensemble methods such as stacking or boosting to enhance performance.
  3.	Longitudinal Data: Incorporate temporal data to track disease progression over time.
  
**Concrete Recommendations for Implementation**
  1.	Deploy the ANN model as a decision-support tool for healthcare professionals.
  2.	Develop a user-friendly interface to input patient data and display predictions seamlessly.
  3.	Regularly update the model with new data to maintain relevance and accuracy.

**Conclusion**
This project demonstrates the potential of machine learning in healthcare by successfully applying ANN to predict diabetes diagnoses. It highlights the importance of systematic data preprocessing, model development, and optimization in achieving reliable predictions.

