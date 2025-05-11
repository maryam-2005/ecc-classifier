# ECC Classification using Machine Learning

This project focuses on classifying error-correcting codes (ECC) using supervised machine learning techniques. Various models like Decision Trees, Random Forests, AdaBoost, SVM, and XGBoost were explored to identify the most accurate and efficient classification method.

---

## Features

- **Dataset Generation**: The dataset is synthetically generated using a custom script, which simulates different types of error-correcting codes.
- **Exploratory Data Analysis (EDA)**: Performed using Seaborn and Matplotlib to understand the dataset.
- **Classifier Models**: Various machine learning models are trained and evaluated:
  - Decision Tree  
  - Random Forest  
  - AdaBoost  
  - Support Vector Machine (SVM)  
  - XGBoost
- **Model evaluation**:
  - Confusion matrix
  - Classification report
  - Accuracy score

---

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Setup Instructions

1. **Clone the repository:**

       git clone https://github.com/maryam-2005/ecc-classifier.git
       cd ecc-classifier

2. **Install the required dependencies:**

       pip install -r requirements.txt

3. **Run the notebook:**

       There are three main Jupyter Notebooks:

    - **Dataset Generation (`DatasetGenerate.ipynb`)**: This notebook creates a synthetic dataset for training and testing the models.
    - **Model Training and Evaluation (`RF_DT_adaboost_xgboost.ipynb`)**: This notebook trains the machine learning models of Random Forest, Decision Tree, Adaboost and XGBoost on the generated dataset and evaluates their performance.
    - **Model Training and Evaluation (`SVM.ipynb`)**: TThis notebook trains the machine learning model SVM on the generated dataset and evaluates performance.

    You can open and run the notebooks in order to generate the dataset and train/evaluate the models.

---

## Results

- Achieved a highest accuracy of **91.87%** using the **XGBoost Classifier**
- Performance evaluated using confusion matrix and classification report

---

## Models Compared

- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
- Support Vector Machine (SVM)

For complete metrics and plots, check the [Model Results & Visuals](model_outputs.md) file.

---

## Folder Structure

    ecc-classifier/
    ├── DatasetGenerate.ipynb
    ├── RF_DT_adaboost_xgboost.ipynb
    ├── SVM.ipynb
    ├── images/
    │   ├── ECC Type (Encoded).png
    │   ├── plot2.png
    │   └── plot3.png
    ├── requirements.txt
    ├── README.md
    └── data/ (optional synthetic dataset location)
---

## License

This project is not currently licensed.  
Please contact the author for permission before using or redistributing the code.

---

## Author

Maryam Ameen 
AI/ML Project – ECC Classification
