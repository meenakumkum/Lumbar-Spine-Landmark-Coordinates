
# 🦴 A Comparative Study of Regression, Sequential, and Hybrid Deep Learning Models for Lumbar Spine Landmark Coordinates

---

## 📌 Problem Statement

Accurate prediction of **lumbar spine landmark coordinates** is very important for medical diagnosis and spinal analysis.
Doing this **manually** takes a lot of time and results may vary from person to person (observer variability).

So, there is a strong need for an **automatic system** that can predict these coordinates **accurately, consistently, and efficiently** using **machine learning and deep learning techniques**.

---

## 📖 Project Overview

This project presents a **comparative study** of:

* **Traditional regression models**
* **Sequential deep learning models**
* **Hybrid deep learning models**

All models are applied on **numerical coordinate data** (not raw images) of the lumbar spine.

The main goal is to:

* Compare model performance
* Identify the most accurate model
* Understand the benefit of **hybrid architectures**

In total, **11 models** are implemented and evaluated.

---

## 📂 Dataset Description

* The dataset contains **numerical coordinates** of lumbar spine landmarks
* Each sample represents **key landmark positions** of lower lumbar vertebrae
* No image processing is involved

👉 This makes the study **purely data-driven and model-focused**

---

## 🔑 Key Components

---

### 1️⃣ Data Preprocessing

Data preprocessing ensures the dataset is clean and ready for modeling.

Steps involved:

* Handling missing values
* Normalizing numerical features
* Splitting data into **training and testing sets**
* Separating input features and target coordinates

👉 This step improves **model stability and performance**

---

### 2️⃣ Exploratory Data Analysis (EDA)

EDA is used to understand the dataset before training models.

Performed tasks:

* Statistical analysis (mean, variance, distribution)
* Understanding feature patterns
* Checking relationships between inputs and outputs

👉 EDA helps in **better model selection and design**

---

### 3️⃣ Machine Learning Models

The following **traditional ML models** are implemented:

* Linear Regression
* Logistic Regression
* Decision Tree
* Random Forest

👉 These models act as **baseline models** and are computationally efficient.

---

### 4️⃣ Sequential Deep Learning Models

To capture **sequential and contextual relationships**, the following models are used:

* Simple RNN
* LSTM (Long Short-Term Memory)
* GRU (Gated Recurrent Unit)
* Transformer
* Attention-based RNN

👉 These models are better at learning **complex patterns** in coordinate data.

---

### 5️⃣ Hybrid Deep Learning Models

To further improve performance, **hybrid models** are designed by combining strengths of multiple architectures.

#### 🔹 Hybrid Model 1: Transformer + GRU

* Transformer captures **global dependencies** using self-attention
* GRU handles **temporal and sequential patterns** efficiently
* This combination improves both **long-range and local learning**

#### 🔹 Hybrid Model 2: Attention + LSTM

* Attention mechanism focuses on **important features**
* LSTM captures **long-term dependencies**
* This hybrid model improves **accuracy and interpretability**

👉 Hybrid models show better performance compared to standalone models.

---

## 📊 Model Evaluation

All models are evaluated using standard regression metrics:

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

👉 Lower values indicate **better prediction accuracy**

---

## 🚀 Project Impact

* Enables **automatic lumbar spine landmark prediction**
* Reduces **manual effort and human error**
* Improves **accuracy and consistency**
* Useful for:

  * Medical research
  * Clinical decision support systems
  * Spine disorder analysis

---

## 🛠️ Technologies Used

* Python
* Google Colab / Jupyter Notebook
* NumPy
* Pandas
* Matplotlib & Seaborn
* Scikit-learn
* TensorFlow
* Keras

---

## ✅ Conclusion

From this study, the following conclusions are drawn:

* Traditional regression models are good **baseline models**
* Sequential deep learning models outperform classical ML models
* Hybrid models (Transformer + GRU and Attention + LSTM) provide **best accuracy**
* Hybrid architectures effectively capture:

  * Global dependencies
  * Sequential patterns
  * Important feature relationships

Overall, **hybrid deep learning models** are the most suitable choice for **lumbar spine landmark coordinate prediction using numerical data**.

