# Elevate-Labs-task-7
# SVM Classification Task

# Objective
The goal of this project is to implement **Support Vector Machines (SVM)** for **binary classification** using both **linear** and **RBF (Radial Basis Function)** kernels. This task is part of the AI & ML internship module.

# Dataset
The dataset used was provided in CSV format (uploaded as part of the task).
It was preprocessed, scaled, and visualized using **PCA** to reduce it to 2 dimensions for boundary visualization.

#Tools and Libraries Used
Python
Scikit-learn
NumPy
Matplotlib
Pandas

#Steps Performed
1. **Data Preprocessing**
   Loaded the CSV data.
   Scaled features using StandardScaler.
   Applied PCA to reduce to 2D for visualization.
2.**Model Training**
   Trained SVM models using:
   **Linear kernel**
   **RBF kernel**
3. **Hyperparameter Tuning**
   Used GridSearchCV to tune C and gamma for RBF.
4. **Model Evaluation**
   Used classification reports and confusion matrices.
5. **Visualization**
   Plotted decision boundaries for both kernels using 2D PCA data.

## Results
- SVM with linear and RBF kernels performed well.
- RBF kernel showed better performance on non-linearly separable data after tuning.

## Decision Boundary Plots
These were generated using the PCA-transformed dataset for 2D visualization of the SVM decision surface.

##Concepts Covered
- Support vectors and margins
- Kernel trick
- Hyperparameter tuning (`C`, `gamma`)
- Cross-validation
- Visualization of classifier boundaries
