# Machine Learning Project: California Housing Price Prediction

## Project Description

This project was developed to solidify core **Machine Learning** principles, diving into advanced techniques for predicting house prices in California. Leveraging the renowned **California Housing dataset**, it encompasses a comprehensive workflow including **feature engineering**, sophisticated **exploratory data analysis (EDA)** with advanced plotting, robust **data preprocessing using pipelines**, and **model building**. We explored various algorithms, fine-tuned hyperparameters with **Grid Search** and **Random Search**, and ensured model reliability through **cross-validation** and analysis of **confidence intervals**. This project was inspired by and developed while diligently following the concepts from the book "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron.

---

## Tools and Libraries Used

-   **Python**
-   **Pandas**
-   **NumPy**
-   **Matplotlib**
-   **Scikit-learn**

---

## Key Project Steps

### 1. Data Acquisition and Preparation

-   Dataset download directly from an online repository.
-   Preprocessing with **pipelines** and custom transformers.

### 2. Exploratory Data Analysis (EDA)

-   Histograms and scatter plots.
-   Correlation maps to identify relationships between variables.

### 3. Modeling

-   Algorithms applied: **Linear Regression**, **Decision Tree**, among others.
-   Hyperparameter tuning with **Grid Search** and **Random Search**.
-   Cross-validation to ensure robust results.

### 4. Evaluation

-   Metrics used: **Mean Squared Error (MSE)**, **R²**.
-   Use of cross-validation technique to prevent data leakage.
-   Confidence intervals to analyze the variability of predictions.

---

## Results

The models were evaluated with robust metrics, and comparative graphs between actual and predicted values were generated for better visualization of the results.

---

## Main Visualizations

-   Histograms showing variable distribution.
-   Scatter plots to identify patterns.
-   Visual comparison between predictions and actual values.

---

## How to Run the Project

1.  Clone this repository:

    ```bash
    git clone [https://github.com/phaa/california-housing.git](https://github.com/phaa/california-housing.git)
    ```

2.  Create an Anaconda environment:

    ```bash
    conda create -n housing-env python=3.9
    ```

3.  Activate the environment:

    ```bash
    conda activate housing-env
    ```

4.  Install the dependencies:

    ```bash
    conda install --file requirements.txt
    ```

5.  Execute Jupyter Lab:

    ```bash
    jupyter lab
    ```

6.  Open the `Housing.ipynb` file and run the cells.

---

## Notes

This project serves as a practical application of fundamental Machine Learning concepts, following best practices for data analysis and model development.
---

## Developer

[Pedro Azevedo](https://www.linkedin.com/in/pedro-henrique-amorim-de-azevedo/)
