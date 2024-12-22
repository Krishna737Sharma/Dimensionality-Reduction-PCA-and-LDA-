# Dimensionality Reduction: PCA and LDA  

## Objective  
To implement Principal Component Analysis (PCA) and Linear Discriminant Analysis (LDA) from scratch, compare them with Scikit-learn implementations, and visualize the results.  

---

## Tasks  

### **Task 1: PCA from Scratch**  
- Implemented PCA from scratch by:  
  1. Standardizing the data.  
  2. Computing the covariance matrix.  
  3. Calculating eigenvalues and eigenvectors.  
  4. Sorting eigenvectors by descending eigenvalues.  
  5. Projecting data onto the top k principal components.  

### **Task 2: PCA Using Scikit-learn**  
- Used Scikit-learn's `PCA` class to compute principal components and transform the dataset.  

### **Task 3: Comparison and Visualization of PCA**  
- Compared the results of PCA from scratch and Scikit-learn.  
- Plotted:  
  - Data projected onto the first two principal components for both implementations.  
  - Explained variance ratio for both implementations.  

### **Task 4: LDA from Scratch**  
- Implemented LDA from scratch by:  
  1. Calculating the mean vectors for each class.  
  2. Computing the within-class scatter matrix and between-class scatter matrix.  
  3. Calculating eigenvalues and eigenvectors from the scatter matrices.  
  4. Sorting eigenvectors by descending eigenvalues and projecting the data.  

### **Task 5: LDA Using Scikit-learn**  
- Used Scikit-learn's `LinearDiscriminantAnalysis` class to compute discriminant components and transform the dataset.  

### **Task 6: Comparison and Visualization of LDA**  
- Compared the results of LDA from scratch and Scikit-learn.  
- Plotted:  
  - Data projected onto the first two discriminant components for both implementations.  
  - Explained variance ratio for both implementations.  

---

## Results  

### **PCA Comparison**  
- **Explained Variance Ratio (First 2 Components)**:  
  - From Scratch: `<value>`  
  - Scikit-learn: `<value>`  

- **Visualization**:  
  - Scatter plots of data projected onto the first two principal components.  

### **LDA Comparison**  
- **Explained Variance Ratio (First 2 Components)**:  
  - From Scratch: `<value>`  
  - Scikit-learn: `<value>`  

- **Visualization**:  
  - Scatter plots of data projected onto the first two discriminant components.  

---

## How to Run  

1. Install required libraries:  
   ```bash
   pip install numpy pandas matplotlib scikit-learn
