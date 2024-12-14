## **Breast Cancer:**  
Breast cancer is cancer that forms in the cells of the breasts. It arises in the lining cells (epithelium) of the ducts (85%) or lobules (15%) in the glandular tissue of the breast. Initially, the cancerous growth is confined to the duct or lobule (“in situ”) where it generally causes no symptoms and has minimal potential for spread (metastasis). Most types of breast cancer are easy to diagnose by microscopic analysis of a sample - or biopsy - of the affected area of the breast. Also, there are types of breast cancer that require specialized lab exams.
**Task:** binary classification for breast cancer (Tabular Data).
## Overview
This project predicts whether a tumor is **malignant** or **benign** based on a set of clinical measurements.

 ![Auxiliary-Diagnosis-of-Breast-Cancer-_Architecture-diagram_ (1)](https://github.com/user-attachments/assets/38b274b1-022c-454c-916c-afcb938b6b8a)  
 
## Dataset
The dataset contains **32 features** (e.g., `radius_mean` ,	`texture_mean` , 	`perimeter_mean` , 	`area_mean`) and **1 target column** (`diagnosis`):
- `M`: Malignant (Cancerous)
- `B`: Benign (Non-Cancerous)

| Feature Name      | Description                  |
|-------------------|------------------------------|
| radius_mean       | Mean size of the tumor       |
| texture_mean      | Variation in texture         |
| ...               | ...                          |

- **Source**: https://github.com/TasneimAhmed/Breast-Cancer/blob/main/breast_cancer.csv 
- **Features**: 32 features, including `mean_radius`, `mean_texture`, and `mean_area`....
- **Target**: Diagnosis (`M` = Malignant, `B` = Benign).
- **Split**:  into train and test (80:20)
---
## Project Workflow
1. **Data Preprocessing**:
   - Handled missing values and scaled features.
2. **Modeling**:
   - Models used: Logistic Regression, SVM, Shallow Neural Network.
3. **Evaluation**:
   - Best Model: NN.
   - Accuracy: **98%**.
## Results
- **Precision**: 97%
- **Recall**: 97%
## Technologies Used
- Python (Pandas, Scikit-Learn, Matplotlib)
- Jupyter Notebook
## Prerequisites
###  Install libraries: 

pip install pandas scikit-learn matplotlib
## Run the Project
### Clone the repository:

git clone https://github.com/yourusername/Breast_Cancer.git




                                                    
       
                
