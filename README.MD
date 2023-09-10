Home Loan Default Detection using Linear Regression, SHAP, and Real-Time Interactive Dashboard

This project aims to develop a predictive model for detecting home loan defaults. By utilizing linear regression and SHAP (SHapley Additive exPlanations) techniques, the project enhances the accuracy of predicting an individual's likelihood of defaulting on a home loan.

Key Features:
Linear regression model: The project leverages the power of linear regression to build a predictive model for home loan default detection.
SHAP analysis: SHAP is employed to explain the contributions of different features towards the loan default predictions, providing valuable insights into the decision-making process.
Real-time interactive dashboard: The project includes a user-friendly interactive dashboard developed using Streamlit. This allows users to input relevant borrower information and obtain instant predictions regarding loan default probabilities.
Contributors:
This project was collaboratively developed by a group, with significant contributions from Shibo: https://github.com/leokingzhao

Deployment on Google Cloud Platform (GCP):
The project is deployed on Google Cloud Platform to ensure scalability and accessibility. Hosting the application on GCP allows users to access the real-time interactive dashboard from anywhere, enabling efficient loan default predictions.

Repository Structure:
data/: Contains the dataset used for training and testing the predictive model.
models/: Includes the trained linear regression model and SHAP model.
notebooks/: Jupyter notebooks with data preprocessing, model training, and SHAP analysis.
app.py: The main application file for the Streamlit interactive dashboard.
requirements.txt: A list of Python dependencies required for running the project.
README.md: The current file, providing an overview of the project.

URL: http://34.66.218.64:8501/
