# **Data Science Internship at Prodigy Infotech**

## **Task 3 Submission:**

Welcome to my submission for Task 3 of the Data Science Internship at Prodigy Infotech. In this task, I worked on the Bank Marketing Dataset, applying data cleaning, exploratory data analysis (EDA), feature transformation, and building a machine learning model to predict whether a client subscribes to a term deposit.

## Dataset Description
____________

The Bank Marketing Additional Dataset contains information about direct marketing campaigns (phone calls) from a Portuguese banking institution. It includes demographic details, contact information, economic indicators, and the target variable indicating whether the client subscribed to a term deposit.

### Key Columns:

* **y(deposit):** Target variable (yes = subscribed, no = not subscribed)

* **age:** Client’s age

* **job, marital, education:** Client demographics

* **default, housing, loan:** Financial indicators

* **contact, month, day_of_week:** Campaign contact details

* **duration, campaign, pdays, previous:** Campaign performance metrics

* **emp.var.rate, euribor3m, cons.price.idx, cons.conf.idx, nr.employed:** Economic context variables

## Tools and Libraries Used

* Jupyter Notebook

* Pandas for data manipulation

* NumPy for numerical operations

* Matplotlib & Seaborn for data visualization

* Scikit-learn for preprocessing and machine learning


## Exploratory Data Analysis (EDA) Process

### **Data Cleaning:**

* Checked and removed duplicate rows and missing values.

* Handled "unknown" categories in categorical columns.

* Treated outliers in numerical columns using the IQR method.

* Reduced skewness in highly skewed numerical columns using log transformation.


### **Data Visualization:**

* Count plots showed distribution of clients' responses across job types, marital status, and other demographics.

* Histograms and boxplots explored the spread of numerical features.

* Correlation heatmaps visualized relationships between economic indicators and campaign features.

### **Machine Learning Model**

* Built a Decision Tree Classifier to predict client subscription (y).

### **Evaluated model performance using:**

* Accuracy score

* Confusion matrix

* Classification report

* Plotted the decision tree for better interpretability.

### **Key Insights**

* Duration of the last call is a strong predictor of success.

* Clients with higher education, younger age, and no default history showed higher subscription rates.

Economic indicators like emp.var.rate and euribor3m showed some influence on client decisions.

Contacted clients in certain months (e.g., March, December) had better response rates.

✅ Conclusion
This project provided valuable insights 🌟 into customer behavior during marketing campaigns. The model successfully predicted term deposit subscriptions, offering a foundation for optimizing future marketing strategies.

🙏 Thank you for reviewing my submission!

