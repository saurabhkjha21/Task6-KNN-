#  K-Nearest Neighbors (KNN) Classification – Iris Dataset

##  Task 6: KNN Classification  
This project implements the **K-Nearest Neighbors (KNN)** algorithm using **scikit-learn** on the classic **Iris flower dataset**. It demonstrates model training, evaluation, cross-validation, and visualization including decision boundaries.

---

##  Dataset Used
**File:** `iris.csv`  
This is the original Iris dataset with the following columns:
- `Id`
- `SepallengthCm`
- `SepalWidthCm`
- `PetalLengthCm`
- `PetalWidthCm`
- `Species`

---

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Steps Performed

### 1. Load & Preprocess Data
- Dropped the `Id` column.
- Renamed columns for readability.
- Encoded `Species` (Setosa, Versicolor, Virginica) into numeric labels.

### 2. Feature Scaling
- Normalized features using `StandardScaler`.

### 3. Train/Test Split
- 80% training, 20% testing using `train_test_split`.

### 4. KNN Training
- Trained KNN models for K values from 1 to 20.
- Plotted accuracy vs K.

### 5. Model Evaluation
- Chose the best K based on test accuracy.
- Evaluated using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### 6. Cross-Validation
- 5-fold cross-validation to ensure performance.

### 7. Visualization
- Accuracy vs K plot.
- Confusion matrix heatmap.
- 2D decision boundary using petal length & width (optional).

---

## 📈 Results
- Best accuracy achieved at the optimal value of K.
- KNN was effective with simple preprocessing and scaling.

---
##  Author

**Saurabh Kumar Jha**  
[GitHub Profile](https://github.com/saurabhkjha21)
[Linkedin Profile](www.linkedin.com/in/saurabhkjha21)

