# Supervised_Learning_Regression_Customer_Churn_Prediction
Context: Customer behavior  prediction to retain customers 

Each cell description:
Each cell description:
Cell 3: lib load
Cell 4: read data from csv file
Cell 5: helper function to find unique value in a feature
Cell 6: Apply label Encoder to convert into numerical value
Cell 7: Exploratory Data Analysis (EDA)
			a. Correlation matrix
			b. Correlation matrix visualization
			c. Pair plot analysis
			d. Histogram analysis
			e. Density analysis
			f. Scatter matrix analysis
			g. Pie chart of Churn

Cell 8: PCA analysis
Cell 9: Best parameter search for 4 models
Cell 10: KNN model
Cell 11: Random forests
Cell 12: Logistic Regression Model
Cell 13: Decision Tree Classifier Model
Cell 14: Single LSTM Model
Cell 15: LSTM Model Evaluation
Cell 16: ROC curves analysis
Cell 17: Precision recall curves analysis
Cell 18: Save Best model(LR) 
Cell 19: Saved Model Execution 

Dataset : Telco Customer Churn
Dataset Link: https://www.kaggle.com/blastchar/telco-customer-churn
Dataset includes 21 features: 
    customerID
    gender
    SeniorCitizen
    Partner
    Dependents
    tenure
    PhoneService
    MultipleLines
    InternetService
    OnlineSecurity
    OnlineBackup
    DeviceProtection
    TechSupport
    StreamingTV
    StreamingMovies
    Contract
    PaperlessBilling
    PaymentMethod
    MonthlyCharges
    TotalCharges
    Churn
We have considered "Churn" as a label
