# 🤖 Machine Learning Algorithms

> **Implementation of Fundamental Machine Learning Algorithms from Scratch**

This repository contains Python implementations of core **Machine Learning** algorithms, demonstrated through practical problem-solving in a Jupyter Notebook. It focuses on understanding the mathematical foundations behind classification and regression models.

---

## 🛠 Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white) |
| **Libraries** | ![NumPy](https://img.shields.io/badge/NumPy-Math-013243?style=flat&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-Scientific_Computing-8CAAE6?style=flat&logo=scipy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-Data-150458?style=flat&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=flat&logo=matplotlib&logoColor=white) |
| **Environment** | ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white) |

---

## 🧠 Algorithms Implemented

The repository includes custom implementations (not just library calls) of the following:

-   **Linear Discriminant Analysis (LDA)**:
    -   `ldaLearn(X, y)`: Learn parameters (means, covariance) for LDA.
    -   `ldaTest(means, covmat, Xtest, ytest)`: Predict and test accuracy using LDA.
-   **Quadratic Discriminant Analysis (QDA)**:
    -   `qdaLearn(X, y)`: Learn parameters for QDA (distinct covariances).
    -   `qdaTest(means, covmats, Xtest, ytest)`: Predict and test accuracy using QDA.
-   **Linear Regression (OLE)**:
    -   `learnOLERegression(X, y)`: Optimize weights for Ordinary Least Squares.
-   **Ridge Regression**:
    -   `learnRidgeRegression(X, y, lambd)`: Regularized regression with parameter $\lambda$.
-   **Gradient Descent Optimization**:
    -   Custom objective functions optimized using `scipy.optimize.minimize`.

---

## 📂 Key Files

-   `Copy_of_Welcome_To_Colab.ipynb`: The main notebook containing all algorithm implementations, testing logic, and visualization code.

---

## 🚀 Usage

1.  **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/Machine-Learning-Algorithms.git
    cd Machine-Learning-Algorithms
    ```

2.  **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```

3.  **Open the Notebook**
    Open `Copy_of_Welcome_To_Colab.ipynb` to run the cells and visualize the results (Decision Boundaries, MSE plots, etc.).

---

*Focusing on the mathematics of learning.*
