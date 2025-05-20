# 📱 Mobile Price Range Classification using Random Forest

This project uses a **Random Forest Classifier** to predict the **price range category** of mobile phones based on various features. The model is built and evaluated using **Python**, **scikit-learn**, and visualization libraries like **matplotlib** and **seaborn**.

---

## 🧾 Dataset Overview

The dataset used is `mobile_price_classification.csv`, containing numerical features of mobile phones such as battery capacity, RAM, processor speed, etc., along with the target column `price_range`.

### 🔑 Target Variable
- `price_range`: Categorical variable indicating the price category (0 = Low, 1 = Medium, 2 = High, 3 = Very High)

---

## 🎯 Objective

To build a classification model that predicts the **price range** of a mobile device using its hardware specifications.

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- scikit-learn (for preprocessing, model training, evaluation)
- seaborn, matplotlib (for visualization)

---

## ⚙️ Workflow

1. **Load Data**  
   Load the dataset using `pandas`.

2. **Data Preparation**  
   - Separate features (`X`) and target (`y`)
   - Split into training and testing sets (80/20)
   - Standardize features using `StandardScaler`

3. **Model Training**  
   - Train a **Random Forest Classifier** with 100 trees (`n_estimators=100`)

4. **Model Evaluation**  
   - Calculate **accuracy score**
   - Generate **confusion matrix** and **classification report**
   - Visualize results using heatmaps

---

## 📈 Visualizations

- ✅ **Confusion Matrix**: Shows how well the model predicts each price range class
![{9B763CEE-67FE-4D41-9E14-5A6620743767}](https://github.com/user-attachments/assets/4be3b995-6fc4-4dfd-a043-6790a3e1296c)

- ✅ **Classification Report Heatmap**: Visualizes precision, recall, and F1-score for each class
![{FDAA9099-145D-4444-9A35-2684C053649E}](https://github.com/user-attachments/assets/4f66cecc-0681-435d-9898-164303c097ba)

---

## ✅ Results

- **Accuracy Score** is printed in the console after training.
- Evaluation metrics are visualized for interpretability.

---
