# ML-Project: Insurance Cost Prediction
This project predicts medical insurance charges using personal and demographic features such as age, sex, BMI, smoking habits, and more. Built using Python and scikit-learn, it includes a full machine learning workflow—from preprocessing to model training and evaluation—organized for modularity and scalability.

Project Overview:
This project demonstrates how to:
•	Load and preprocess structured data.
•	Use Regression models to build a predictive model.
•	Evaluate model performance using standard metrics.
•	Save and reuse the trained model.
•	Explore data through a Jupyter notebook.

Key Features:
•	Clean and modular code structure for ease of maintenance.
•	Preprocessing with one-hot encoding for categorical variables.
•	Linear regression, Random Forest Regressor and Gradient Boosting Regressor using scikit-learn.
•	Model evaluation using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE) and R² Score.
•	Saved model artifacts with joblib.
•	Jupyter notebook for interactive exploration.


Data and Features:

Dataset: insurance(1).csv 
Features used:
1.	age: Age of the individual
2.	sex: Gender (categorical)
3.	bmi: Body Mass Index
4.	children: Number of children
5.	smoker: Smoking status (categorical)
6.	region: Residential area (categorical)
7.	charges: Target variable (insurance cost)

 Tech Stack
 
•	Python (Pandas, NumPy, Sklearn, Seaborn, Matplotlib)
•	Jupyter Notebook
•	Tkinter (for web interface)

Preprocessing Steps

•	Load CSV using pandas
•	One-hot encode categorical variables (sex, smoker, region)

Visualizations

•	Distplot for all numerical features.
•	 Countplot for all categorical features.
•	Correlation heatmap to visualize feature interrelationships.
•	Bar plots for comparison of performance metrics of different models.



Project Structure

ML-Project/ 
├── data/ # Contains datasets 
├── insurance(1).csv # Original dataset  
   └── .gitignore # To ignore large files from version control 
├── docs/ 
   └── project documentation.pdf # Optional documentation 
├── models/
   └── model.joblib # Trained model (auto-generated) 
├── notebooks/ 
   └── Insurance cost prediction .ipynb # Jupyter Notebook for exploration 
├── src/ 
├── data_preprocessing.py # Script for preprocessing 
├── LICENSE # MIT license for open-source distribution 
|-── requirements.txt # Required Python packages
├── README.md # Project overview and instructions 

 How to Run
 
1.	Clone the repo:
git clone https://github.com/yourusername/ML-Project.git
cd ML-Project
2.	Install dependencies:
•	pip install -r requirements.txt
3.	Launch Jupyter Notebook and run Insurance cost prediction.ipynb
   
Authors
•	Mitali Sharma
•	Naincy Rahuja
