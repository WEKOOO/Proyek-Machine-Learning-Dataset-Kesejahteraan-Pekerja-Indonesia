# **Final Machine Learning Project**

## **Overview**
This project implements **both clustering and classification models** as part of a structured Machine Learning workflow. The project follows standard ML development practices, including **data preprocessing, model training, evaluation, and optimization**.

## **Project Structure**
```
├── [Clustering] Submission Akhir BMLP_Weko_Abbror.ipynb  # Jupyter Notebook for clustering
├── [Klasifikasi] Submission Akhir BMLP_Weko_Abbror.ipynb # Jupyter Notebook for classification
├── Dataset_clustering.csv   # Dataset used for clustering model
├── Dataset_inisiasi.csv     # Initial dataset for processing
├── README.md                # Project documentation
```

## **Installation**
To run this project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## **Dataset**
- The project uses **Dataset_clustering.csv** for clustering and **Dataset_inisiasi.csv** as the initial dataset.
- Data preprocessing includes handling missing values, normalization, and feature selection.

## **Machine Learning Models**
### **1. Clustering Model**
- Implemented in `[Clustering] Submission Akhir BMLP_Weko_Abbror.ipynb`.
- Uses **K-Means, DBSCAN, and Agglomerative Clustering**.
- Evaluated using **Silhouette Score and Davies-Bouldin Index**.

### **2. Classification Model**
- Implemented in `[Klasifikasi] Submission Akhir BMLP_Weko_Abbror.ipynb`.
- Uses **Logistic Regression, Decision Tree, and Random Forest**.
- Evaluated using **accuracy, precision, recall, F1-score, and ROC-AUC**.

## **How to Run**
1. **Open the Jupyter Notebooks**
   - Run `[Clustering] Submission Akhir BMLP_Weko_Abbror.ipynb` for clustering.
   - Run `[Klasifikasi] Submission Akhir BMLP_Weko_Abbror.ipynb` for classification.

2. **Follow the steps inside the notebooks to execute the models.**

## **Results**
- Clustering results show clear data segmentation with **K-Means producing the best clusters**.
- Classification achieved **high accuracy and generalization performance** with Random Forest.

## **Next Steps**
- Further **hyperparameter tuning** for improved model performance.
- Experiment with **deep learning approaches** for better classification accuracy.
- Deployment of the model as a **web API or application**.

## **Contributors**
- Weko Abbror
