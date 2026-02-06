#  Crop Recommendation System (Multi-Class Classification)

This project builds a **Machine Learning-based Crop Recommendation System** that predicts the most suitable crop to grow based on soil and environmental parameters.

---

##  Problem Statement

Agricultural productivity depends heavily on selecting the right crop for given soil and climate conditions. This model helps farmers and agricultural planners make data-driven decisions by recommending one of **22 possible crops**.

---

##  Dataset

**Crop Recommendation Dataset** containing features:

* Nitrogen (N)
* Phosphorus (P)
* Potassium (K)
* Temperature
* Humidity
* pH level
* Rainfall
* Target: Crop type (22 classes)

---

##  Preprocessing Steps

* Checked and handled missing values (mean imputation where needed)
* Scaled numerical features using **StandardScaler**
* Removed outliers using the **IQR method**
* Encoded crop labels using **LabelEncoder**
* One-hot encoded labels using **to_categorical**
* Split data into **80% training** and **20% testing**

---

##  Model Architecture

**Neural Network (Baseline Model):**

* Input layer: 7 features
* Hidden Layer 1: 64 neurons (ReLU)
* Hidden Layer 2: 32 neurons (ReLU)
* Output Layer: 22 neurons (Softmax)

**Compilation:**

* Loss: Categorical Crossentropy
* Optimizer: Adam
* Metric: Accuracy

**Training:**

* Epochs: 100
* Batch size: 32

---

## Evaluation

* Model evaluated using:

  * Accuracy score
  * Confusion Matrix

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib / Seaborn





If you want, I can also write a more professional version for a final-year project or portfol
