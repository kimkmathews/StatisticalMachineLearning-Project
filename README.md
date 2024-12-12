# Gender Classification in Movie Screenplays

## Abstract

This project investigates gender bias in Hollywood movies by analyzing screenplay data and employing machine learning models to predict the gender of the lead character.

## Data Description

The dataset contains information about roughly 1000 films, including:

* Number of words spoken by male and female actors
* Gender of the lead actor
* Box office revenue

## Models Employed

* **Logistic Regression (Baseline):** Achieved 87.5% accuracy after hyperparameter tuning.
* **Discriminant Analysis**
    * **Linear Discriminant Analysis (LDA):** Achieved 84% accuracy.
    * **Quadratic Discriminant Analysis (QDA):** Achieved the highest accuracy (91.34%).
* **K Nearest Neighbors (KNN):** Achieved 81% accuracy.
* **Tree-Based Methods**
    * **Classification Trees:** Achieved 80.12% accuracy.
    * **Random Forests:** Achieved 81.7% accuracy.
* **Gradient Boosting:** Achieved 89.2% accuracy.

## Key Findings

* Men dominate speaking roles in Hollywood movies, speaking considerably more words than female characters.
* While female characters' speaking roles have increased over time, a gender imbalance persists.
* There is a correlation between the lead character's gender and box office revenue, with films featuring male leads tending to generate higher profits.
* QDA outperformed other models in terms of accuracy, sensitivity, and specificity.

## Conclusion

This project demonstrates the feasibility of using machine learning to analyze gender bias in film. The findings suggest that Hollywood continues to favor male characters in leading roles, and this bias may be reflected in box office performance. Further research could explore a wider range of films and incorporate additional features to create even more comprehensive models.
