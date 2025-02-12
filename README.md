## LAB 2
## Breast Cancer Diagnosis Using Machine Learning

### Overview
This project focuses on diagnosing breast cancer using machine learning models trained on the **Wisconsin Diagnostic Breast Cancer (WDBC) dataset**. The dataset is sourced from the **UCI Machine Learning Repository** via `ucimlrepo`.

The project implements:
1. **Logistic Regression Model** (Version 1) - A baseline model for classification.
2. **Random Forest Classifier** (Version 2) - A more advanced ensemble learning model.

### Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- **Features**: 30 numerical attributes extracted from cell nuclei
- **Target Labels**:
  - `1` → Malignant (Cancerous)
  - `0` → Benign (Non-Cancerous)

### Project Features
- **Exploratory Data Analysis (EDA)**:
  - Visualizations of class distribution
  - Feature correlation heatmap
- **Data Preprocessing**:
  - Train-test split (80% training, 20% testing)
  - Feature scaling using `StandardScaler`
- **Model Training & Evaluation**:
  - Version 1: **Logistic Regression**
  - Version 2: **Random Forest Classifier**
  - Performance evaluation using:
    - **Accuracy Score**
    - **Classification Report**
    - **Confusion Matrix**

### How to Run the Code
1. **Clone the repository**:
   ```sh
   git clone https://github.com/SMJR-GH/Lab-2.git
   cd <repo-name>
   ```
2. **Install required dependencies**:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn ucimlrepo
   ```
3. **Run the script**:
   ```sh
   python your_script.py
   ```

### Results
The model outputs:
- **Accuracy Score**: Percentage of correctly classified cases.
- **Confusion Matrix**: Breakdown of True Positives, True Negatives, False Positives, and False Negatives.
- **Classification Report**: Precision, recall, and F1-score.

### GitHub Repository
🔗 [Your GitHub Repository] https://github.com/SMJR-GH/Lab-2.git


