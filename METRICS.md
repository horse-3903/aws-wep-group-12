# Model Evaluation Metrics

Below are the explanations of the key metrics used:

## **Accuracy**
- **Definition**: The ratio of correctly predicted instances to the total instances.
- **Formula**:  
  $$
  \text{Accuracy} = \frac{\text{True Positives} + \text{True Negatives}}{\text{Total Instances}}
  $$
- **Interpretation**: It gives the overall effectiveness of the model. However, it can be misleading if the dataset is imbalanced.

## **Precision**
- **Definition**: The ratio of correctly predicted positive instances to the total predicted positives.
- **Formula**:  
  $$
  \text{Precision} = \frac{\text{True Positives}}{\text{True Positives} + \text{False Positives}}
  $$
- **Interpretation**: It indicates how many of the instances predicted as positive are actually positive. High precision means low false positive rate.

## **Recall**
- **Definition**: The ratio of correctly predicted positive instances to all instances that are actually positive.
- **Formula**:  
  $$
  \text{Recall} = \frac{\text{True Positives}}{\text{True Positives} + \text{False Negatives}}
  $$
- **Interpretation**: It shows how many of the actual positive instances were correctly identified by the model. High recall means low false negative rate.

## **F1 Score**
- **Definition**: The harmonic mean of precision and recall.
- **Formula**:  
  $$
  \text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}}
  $$
- **Interpretation**: It provides a balance between precision and recall. It is useful when the class distribution is imbalanced.

## **Confusion Matrix**
- **Definition**: A table used to describe the performance of a classification model. It shows the actual versus predicted classifications.
- **Components**:
    - **True Positives (TP)**: Correctly predicted positive instances.
    - **True Negatives (TN)**: Correctly predicted negative instances.
    - **False Positives (FP)**: Incorrectly predicted positive instances.
    - **False Negatives (FN)**: Incorrectly predicted negative instances.
- **Interpretation**: It provides a detailed breakdown of correct and incorrect classifications, which helps in understanding the types of errors the model is making.

## **Classification Report**
- **Definition**: A detailed report showing the precision, recall, F1 score, and support for each class.
- **Components**:
    - **Precision**: As defined above.
    - **Recall**: As defined above.
    - **F1 Score**: As defined above.
    - **Support**: The number of actual occurrences of each class in the dataset.
- **Interpretation**: It provides a comprehensive view of the model's performance across all classes.