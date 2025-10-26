## 1. Titanic Survival Prediction 🚢


## 2. Movie Rating Prediction with Python 🎬

### Project Goal
To build a **regression model** that accurately estimates a movie's numerical rating based on its features and metadata.

### Modeling Approach
* **Technique:** Utilized the **Random Forest Regressor** to predict the continuous rating score, focusing on capturing non-linear feature relationships.
* **Preprocessing:** Handled high-cardinality categorical features (like `Director` and `Actors`) through effective encoding techniques.
* **Key Features:** Incorporated essential movie metadata, including **Genres**, **Director**, and **Actors**.

### Performance Summary
The model's performance was evaluated using standard regression metrics.

| Metric | Score | Interpretation |
| :--- | :--- | :--- |
| **RMSE** (Root Mean Squared Error) | **1.207** | The average magnitude of the prediction error (in rating points). |
| $\text{R}^2$ Score | 0.216 | The percentage of variance in the ratings explained by the model. |

**Conclusion:** The Random Forest Regressor provides a prediction with an average error (RMSE) of approximately $1.2$ rating points.


## 3. Iris Flower Classification 🌸

### Project Goal
A multi-class classification task to correctly identify the species of an Iris flower ($\text{setosa}$, $\text{versicolor}$, or $\text{virginica}$) using its physical measurements.

### Data Inputs
The model relies on four key measurements: **sepal length**, **sepal width**, **petal length**, and **petal width**.

### Classification Approach
1.  **Preprocessing:** Minimal preprocessing was required due to the dataset's clean nature.
2.  **Model:** Utilized the **Random Forest Classifier** from scikit-learn. This robust ensemble model was chosen for its reliability and ability to handle simple classification tasks effectively.

### Performance Summary
The **Random Forest Classifier** performed well on the test data.

**Conclusion:** The Random Forest model achieved a $\mathbf{90\%}$ accuracy, successfully classifying the Iris species based on their dimensions.