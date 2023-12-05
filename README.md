
# Toxic Comments Detection with BERT Models

This repository encompasses code and resources dedicated to evaluating the performance of BERT models in identifying toxic comments. The primary focus is on comments directed towards three distinct groups: transgender people, indigenous people, and migrated people. The goal is to develop a model capable of classifying comments as toxic or non-toxic based on their content.

## Objectives

- Utilize the distilbert-base-multilingual-cased model for toxic comments detection.
- Assess the model's effectiveness using key metrics such as Accuracy, Precision, Recall, and F1-score.
- Specifically, evaluate the model's performance in identifying toxic comments targeting transgender, indigenous, and migrated populations.



### Dataset Preparation:

- Collect and curate a dataset comprising comments related to transgender, indigenous, and migrated people.
- Annotate the dataset to distinguish toxic and non-toxic comments.

### Model Development:

- Implement and fine-tune the distilbert-base-multilingual-cased model for toxic comment classification.
- Train the model on the prepared dataset, considering the distinct groups of people.

### Performance Evaluation:

- Evaluate the model using fundamental metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Perform a subgroup analysis to assess the model's performance on comments directed towards transgender, indigenous, and migrated people.
