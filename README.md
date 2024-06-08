# Health Plan Audits

Project conducted in the Data Mining and Machine Learning course, aimed at building a tool capable of combining all the variables of a request and, based on the historical behavior of auditors, automating the analysis of the request.

## Problem

The provider asks the operator if the beneficiary is eligible to undergo the procedure. The service should only continue if the answer is positive. All requests are analyzed by the operator's computerized system. After automatic analysis, the system determines whether it can already give the final answer (yes or no) or if it depends on the analysis of an auditor (operator's employee). The auditors analyze all artifacts of the request (justification, attachments, beneficiary history, etc.) and respond whether the procedure is authorized or not.

## Tools

The project used the Knowledge Discovery in Databases (KDD) procedure, combined with Machine Learning tools to finalize the proposed model.

## Methods Used

Various libraries and machine learning methods were used, including:

- **Pandas** for data manipulation.
- **NumPy** for mathematical operations.
- **Seaborn** and **Matplotlib** for visualizations.
- **SciPy** for statistics.
- **Scikit-learn** for modeling, including:
  - **Train-test split**
  - **Label encoding**
  - **Support Vector Machine (SVM)**
  - **K-Nearest Neighbors (KNN)**
  - **GridSearchCV** and **RandomizedSearchCV** for hyperparameter tuning
  - **Gaussian Naive Bayes**
  - **Decision Tree Classifier**
  - **Random Forest Regressor and Classifier**
  - **AdaBoost Classifier**
  - **Gradient Boosting Classifier**
  - **Extra Trees Classifier**
  - **Multi-layer Perceptron (MLP) Classifier**
  - **Confusion matrix, ROC AUC score, F1 score, classification report**
- **Graphviz** for decision tree visualization.
- **Imbalanced-learn** for handling imbalanced data, using:
  - **Random OverSampler**
  - **Random UnderSampler**

## Files

- **NotebookFinal.ipynb**: Notebook containing the entire process of analysis, data mining, and machine learning model building.

## Kaggle Competition

Join the competition on Kaggle to test and improve your model: [kaggle](https://www.kaggle.com/competitions/auditoria-bia-ufg)

## How to Use

1. Clone the repository:
    ```sh
    git clone <repository URL>
    ```

2. Navigate to the project directory:
    ```sh
    cd <repository name>
    ```

3. Open the notebook:
    ```sh
    jupyter notebook NotebookFinal.ipynb
    ```

4. Run the notebook cells to reproduce the results and see the model building process.

## Contribution

Contributions are welcome! Feel free to open issues and pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
