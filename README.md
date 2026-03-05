# Diabetes-Prediction-using-Logistic-Regression

## 1. Import Required Libraries

The program begins by importing the necessary Python libraries.

* NumPy is used for numerical operations.
* Pandas is used for loading and handling the dataset.
* Matplotlib is used for visualization and plotting graphs.
* Scikit-learn provides machine learning tools used for model training and evaluation.

These libraries help in data processing, model creation, and performance evaluation.

---

## 2. Loading the Dataset

The dataset **diabetes.csv** is loaded using pandas.

The dataset contains medical information about patients such as:

* Pregnancies
* Glucose level
* Blood pressure
* Skin thickness
* Insulin level
* Body Mass Index (BMI)
* Diabetes Pedigree Function
* Age

The dataset also contains a target column called **Outcome** which represents whether a person has diabetes or not.

**Outcome values:**

* 0 → No Diabetes
* 1 → Diabetes

---

## 3. Selecting Features and Target

The dataset is divided into two parts.

**Features (X)** – Input variables used to make predictions.

* Pregnancies
* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI
* DiabetesPedigreeFunction
* Age

**Target (y)** – Output variable to be predicted.

* Outcome

---

## 4. Splitting the Dataset

The dataset is divided using the **Train-Test Split** method.

* **Training Data (80%)** → Used to train the model
* **Testing Data (20%)** → Used to test the model

This helps evaluate the model on unseen data.

---

## 5. Feature Scaling

Feature scaling is performed using **StandardScaler**.

Feature scaling standardizes the dataset so that all feature values are in a similar range.

After scaling:

* Mean = 0
* Standard deviation = 1

This improves the performance of the machine learning algorithm.

---

## 6. Training the Model

The machine learning algorithm used i
