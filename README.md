# 🌸 Developer Hub – Task 01

## **Exploring & Visualizing the Iris Dataset**

---

## 📌 **Task Objective**

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on the classic **Iris dataset**.
The goal is to understand:

* The structure of the dataset
* Distribution of each feature
* Relationships between features
* How the three Iris species differ based on their measurements

This analysis helps identify the most discriminative features and prepares the dataset for further Machine Learning tasks.

---

## 📊 **Dataset Used**

The task uses the well-known **Iris flower dataset**, consisting of:

* **150 samples**
* **4 numerical features:**

  * sepal_length
  * sepal_width
  * petal_length
  * petal_width
* **1 categorical target:**

  * species (Setosa, Versicolor, Virginica)

The dataset is clean with **no missing values**, making it suitable for immediate visualization and EDA.

---

## 🤖 **Models Applied**

No machine learning model was trained in this task.
However, multiple **visualization models/techniques** were applied to explore the data:

### **1. Scatter Plot**

Shows feature relationships and species clustering.

### **2. Histograms**

Displays the distribution of each numerical feature.

### **3. Box Plots**

Helps identify potential outliers in the dataset.

### **4. Pair Plot (Seaborn Pairplot)**

Visualizes multi-feature relationships and highlights which features best separate the three species.

These visual tools serve as a foundation for future ML modeling.

---

## 📈 **Key Results & Findings**

### **1. Species Clustering**

* **Iris-setosa** forms a very clear and distinct cluster in scatter plots.
* **Versicolor** and **Virginica** show partial overlap in some features.

### **2. Feature Distributions**

* Most features follow roughly normal distributions.
* **Petal Length and Petal Width** show clear separation between species, making them strong predictors for classification.

### **3. Outliers**

* Some mild outliers are visible in **sepal_width**, especially for the Setosa species.

### **4. Most Discriminating Features**

From pairplots, the two most important features appear to be:

* **Petal Length**
* **Petal Width**

These features offer the highest separation between species, confirming the dataset’s suitability for ML classification tasks.

---

## 🧾 **Code Included**

The task contains Python code for:

* Loading the dataset
* Displaying dataset info
* Generating scatter plots, histograms, boxplots, and pairplots

All visualizations were done using:

* **Pandas**
* **Seaborn**
* **Matplotlib**

---

## ✅ **Conclusion**

The Iris dataset proves to be an excellent starting point for data visualization and ML exploration.
The EDA clearly shows:

* Strong feature separability
* Minimal preprocessing needs
* High potential for accurate predictive modeling

This groundwork sets the stage for applying supervised learning models in future tasks.

---

**Author:** Areeba Khan
**Internship:** Developer Hub
**Task:** 01 – Exploring & Visualizing Iris Dataset
