# NLP Spam Identifier

## Hypothesis
The hypothesis of this project is that natural language processing (NLP) techniques can be effectively used to identify spam messages with high accuracy. By analyzing the text of messages, we aim to build a model that can distinguish between spam and non-spam (ham) messages.

## Data Acquisition
The data for this project was collected from a publicly available dataset of email messages. The dataset can be found at the following location:

```
url_spam.csv
```

This dataset contains a collection of SMS messages labeled as either spam or ham (non-spam). Each message is accompanied by a label indicating whether it is spam or not, which will be used to train and evaluate our models.

## Model Used
- Support Vector Machine (SVM)


## Hyperparameter Tuning
To optimize the performance of our model, we used Grid Search Cross-Validation to tune the hyperparameters. This method involves systematically searching through a predefined set of hyperparameters and evaluating the model's performance using cross-validation. The best combination of hyperparameters is then selected based on the cross-validation results.


## Model Evaluation

To evaluate the performance of our model, we used the following plots:

### Learning Curve
The learning curve helps us understand the model's performance over time as it is trained on more data. It plots the training and validation scores against the number of training samples. This allows us to diagnose whether the model is suffering from bias (underfitting) or variance (overfitting).

### Confusion Matrix
The confusion matrix provides a detailed breakdown of the model's predictions. It shows the number of true positives, true negatives, false positives, and false negatives. This helps us understand the types of errors the model is making and provides insights into its precision, recall, and overall accuracy.

By analyzing these plots, we can gain a deeper understanding of the model's performance and make informed decisions about potential improvements.


## Takeaways
- NLP techniques can be highly effective in identifying spam messages.
- Proper data preprocessing and feature extraction are crucial for building an accurate model.
- Hyperparameter tuning can significantly improve the performance of the model.
- The selected model achieved high accuracy in distinguishing between spam and ham messages, demonstrating the potential of NLP in spam detection.
