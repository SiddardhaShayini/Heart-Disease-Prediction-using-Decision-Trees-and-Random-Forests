# Heart Disease Prediction using Decision Trees and Random Forests

## Project Overview

This project focuses on building and evaluating machine learning models to predict the presence of heart disease based on various patient attributes. We explore two fundamental tree-based algorithms: **Decision Trees** and **Random Forests**. The goal is to demonstrate their implementation, understand their working principles, analyze their performance, and visualize their decision-making processes.

## Dataset

The dataset used in this project is a subset of the Heart Disease dataset, containing 14 relevant features. The `target` field indicates the presence of heart disease:

  - `0`: No disease
  - `1`: Disease

### Features:

  * `age`: Age in years
  * `sex`: Sex (1 = male; 0 = female)
  * `cp`: Chest pain type (4 values)
  * `trestbps`: Resting blood pressure (mm Hg)
  * `chol`: Serum cholestoral (mg/dl)
  * `fbs`: Fasting blood sugar \> 120 mg/dl (1 = true; 0 = false)
  * `restecg`: Resting electrocardiographic results (values 0, 1, 2)
  * `thalach`: Maximum heart rate achieved
  * `exang`: Exercise induced angina (1 = yes; 0 = no)
  * `oldpeak`: ST depression induced by exercise relative to rest
  * `slope`: The slope of the peak exercise ST segment
  * `ca`: Number of major vessels (0-3) colored by flourosopy
  * `thal`: Thalassemia (0 = normal; 1 = fixed defect; 2 = reversable defect)
  * `target`: Presence of heart disease (0 = no disease, 1 = disease)

## Project Goals

  * Understand and implement Decision Tree Classifiers.
  * Visualize Decision Trees for interpretability.
  * Analyze the concept of overfitting and methods to control tree complexity (`max_depth`).
  * Implement and evaluate Random Forest Classifiers.
  * Compare the performance of Decision Trees and Random Forests.
  * Interpret feature importances to understand key predictors.
  * Utilize cross-validation for robust model evaluation.
  * Perform comprehensive exploratory data analysis (EDA) and visualizations.

## Technologies Used

  * **Python 3.x**
  * **Scikit-learn**: For machine learning models (Decision Trees, Random Forests, model selection).
  * **Pandas**: For data manipulation and analysis.
  * **Numpy**: For numerical operations.
  * **Matplotlib**: For basic plotting and visualizations.
  * **Seaborn**: For enhanced statistical data visualizations.
  * **Graphviz**: For visualizing decision tree structures.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/SiddardhaShayini/Heart-Disease-Prediction-using-Decision-Trees-and-Random-Forests.git
    cd Heart-Disease-Prediction-using-Decision-Trees-and-Random-Forests
    ```   

2.  **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the required packages:**

    ```bash
    pip install pandas scikit-learn matplotlib seaborn graphviz
    ```

    You might also need to install the Graphviz executable on your system for `graphviz` to render images.

      - **Windows**: Download from [graphviz.org/download](https://graphviz.org/download/) and add to PATH.
      - **macOS (using Homebrew)**: `brew install graphviz`
      - **Linux (Debian/Ubuntu)**: `sudo apt-get install graphviz`

## How to Run

1.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2.  Navigate to and open `heart_disease_prediction.ipynb`.
3.  Run all cells sequentially to execute the data loading, model training, evaluation, and visualization steps.


## Key Findings & Visualizations

The notebook includes comprehensive analyses and visualizations such as:

  * **Decision Tree Visualization**: A visual representation of how the tree makes splits.
  * **Overfitting Analysis**: A plot showing training vs. testing accuracy at different tree depths.
  * **Feature Importances**: A bar chart highlighting the most influential features in the Random Forest model.
  * **Confusion Matrices**: Visual representation of model performance for both Decision Tree and Random Forest.
  * **ROC Curve and AUC**: Evaluation of classifier performance across different threshold settings.
  * **Exploratory Data Analysis (EDA) Plots**:
      * Distributions of numerical features (histograms, KDEs).
      * Counts of categorical features.
      * Box plots showing numerical feature distributions by target class.
      * Stacked bar plots showing categorical feature distributions by target class.
      * Correlation heatmap of numerical features.
      * Pair plots for selected numerical features.
      * Specific scatter plots and histograms for `trestbps` vs `chol`, `age` vs `sex`, `sex` distribution, and `age` distribution.


-----

## ✍️ Author

- Siddardha Shayini

-----
