# support-vector-machine
The objective of this task is to understand and implement Support Vector Machine (SVM) for binary classification using linear and non-linear kernels.
#Dataset Used
Breast Cancer Wisconsin Dataset (from sklearn library)
This dataset contains features related to breast cancer diagnosis and the target variable indicates whether the tumor is malignant or benign.
#Steps Performed
1. Imported required libraries such as NumPy, Matplotlib and Scikit-learn.
2. Loaded the breast cancer dataset.
3. Selected two features for visualization of decision boundary.
4. Split the dataset into training and testing sets.
5. Applied StandardScaler for feature scaling.
6. Trained two SVM models:
   - Linear Kernel
   - RBF (Radial Basis Function) Kernel
7. Compared model accuracy.
8. Generated confusion matrix and classification report.
9. Visualized decision boundaries for better understanding.
#Results
- Both Linear and RBF models performed well.
- RBF kernel handled non-linear separation better.
- Accuracy was calculated to evaluate performance.
#Tools Used
- Python
- Scikit-learn
- NumPy
- Matplotlib
#Conclusion
Support Vector Machine is a powerful classification algorithm that works well for both linear and non-linear data using kernel trick. This task helped me understand how SVM builds decision boundaries and how to evaluate classification models.
