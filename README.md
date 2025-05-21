# heart-disease-prediction-decision-tree
This project is a step-by-step guide to predicting the presence of heart disease using a model trained using a real-world dataset and built with Python and Scikit-learn. From data loading to model evaluation in clear and practical terms. 

This name reflects the main purpose of the notebook — using a decision tree to predict heart disease, while being clean and descriptive.

# ❤️ Heart Disease Prediction Using Decision Tree (Beginner Project)

This project is a step-by-step, beginner-friendly guide to predicting the presence of heart disease using a **Decision Tree Classifier**. The model is trained using a real-world dataset and built with Python and Scikit-learn.

Whether you're new to data science or looking to understand how machine learning models work in practice, this notebook walks you through each step — from data loading to model evaluation — in clear and practical terms.

---

## 🔧 Tech Stack Used

| Tool / Library   | Purpose                            |
|------------------|-------------------------------------|
| Python           | Programming language                |
| Pandas           | Data loading and manipulation       |
| NumPy            | Numerical operations                |
| Matplotlib & Seaborn | Data visualization              |
| Scikit-learn     | Machine learning & model building   |
| Jupyter Notebook | Interactive step-by-step workflow   |

---

## 📊 About the Dataset

- The dataset contains medical records of patients.
- Each row represents one patient, and each column is a medical feature (e.g., age, cholesterol level, resting blood pressure).
- The target variable indicates whether the patient is likely to have heart disease (1) or not (0).

---

## 🚶🏽‍♂️ Project Workflow

### **Load the Data**
We use `pandas` to load the dataset from a CSV file. The first step is to inspect the data to understand its structure.
data = pd.read_csv("heart.csv")

>> Explore the Data
data.info()  #tells us about the data types and non-null counts.

data.isnull().sum() #checks for any missing values (important before model training).

This step helps ensure that our data is clean and ready for analysis.

### **Visualize the Data**
We use Seaborn and Matplotlib to explore trends:

Plotting the relationship between features (like age, cholesterol, etc.)

Understanding which variables might affect heart disease risk

Visuals help in choosing the most meaningful features for our model.

## **Prepare the Data**
We split the dataset into:

Features (X) – the input columns (e.g., age, blood pressure)

Target (y) – the output (presence of heart disease)

We also split the data into training and testing sets using train_test_split from Scikit-learn.

##  **Build the Model**
We use a Decision Tree Classifier, which is easy to interpret and suitable for beginners.

## Why a Decision Tree?

It works well with both numerical and categorical data.

It shows how decisions are made (like a flowchart).

It's quick to train and gives understandable results.

## **Evaluate the Model**
We test the model on unseen data and check:

Accuracy

Confusion Matrix

Precision, Recall, and F1-score

This tells us how well the model performs in making real-world predictions.


✅ **Key Takeaways**
You learned how to load and clean a dataset using Pandas.

You saw how visualizations help explore and understand data.

You built a basic, powerful machine learning model (Decision Tree).

You evaluated your model with real performance metrics.


🧠 **Next Steps (Optional Enhancements)**
Try other models like Random Forest or Logistic Regression.

Use GridSearchCV to tune hyperparameters.

Add cross-validation for more robust evaluation.


## 💬 *Final Notes*
This project is ideal for beginners who want to start hands-on with machine learning using health-related data. It balances simplicity with depth and shows you how real data can lead to valuable insights using accessible tools.

Feel free to fork, clone, or build on this project!
