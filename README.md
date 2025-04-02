# **Breast Cancer Prediction using Logistic Regression**

## **Overview**  
This project implements a binary classification model using **Logistic Regression** to predict whether a breast tumor is **malignant** or **benign**. It utilizes the **Breast Cancer Wisconsin (Diagnostic) Dataset** for training and evaluation.  

## **About the Dataset**  
The project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.They describe characteristics of the cell nuclei present in the image.
### **Attribute Information:**  
1) **ID number**  
2) **Diagnosis** (*M = malignant, B = benign*)  
3-32) **Ten real-valued features computed for each cell nucleus:**  
   - **Radius** (mean of distances from center to points on the perimeter)  
   - **Texture** (standard deviation of gray-scale values)  
   - **Perimeter**  
   - **Area**  
   - **Smoothness** (local variation in radius lengths)  
   - **Compactness** (perimeter² / area - 1.0)  
   - **Concavity** (severity of concave portions of the contour)  
   - **Concave points** (number of concave portions of the contour)  
   - **Symmetry**  
   - **Fractal dimension** ("coastline approximation" - 1)  

- **All feature values are recorded with four significant digits.**  
- **Missing attribute values: None**  
- **Class distribution:**  
  - 357 benign  
  - 212 malignant  

## **Model and Approach**  
- **Algorithm**: Logistic Regression (a linear model for binary classification)    
- **Train-Test Split**: Typically **80%-20%**  
- **Performance Metrics**:  
  - Accuracy  
  - Precision    

## **Installation & Dependencies**  
Ensure you have Python and required libraries installed before running the code.  

### **Required Libraries**  
```bash
pip install numpy pandas scikit-learn 
```

## **Usage**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Breast_Cancer_Prediction.git
   cd Breast_Cancer_Prediction
   ```
2. Run the prediction script:  
   ```bash
   python Breast_Cancer_Prediction.py
   ```
3. The model will train on the dataset and display key performance metrics.  

## **License**  
This project is open-source and available under the **MIT License**.  
