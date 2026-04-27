# Pneumonia Classification — Model Evaluation Results

Results of three models across **5 independent runs** under two training configurations:

- No class weighting, default 0.5 threshold
- Class weighting enabled + 0.7 decision threshold


---

## Table of Contents

- [Without Class Weighting (0.5 threshold)](#without-class-weighting-05-threshold)
  - [Baseline CNN](#baseline-cnn)
  - [EfficientNet-B0](#efficientnet-b0)
  - [DenseNet-121](#densenet-121)
- [With Class Weighting + 0.7 Threshold](#with-class-weighting--07-threshold)
  - [Baseline CNN](#baseline-cnn-1)
  - [EfficientNet-B0](#efficientnet-b0-1)
  - [DenseNet-121](#densenet-121-1)
- [Summary](#summary)

---

## Without Class Weighting (0.5 threshold)

### Baseline CNN

<summary>Run 1</summary>

```
              precision    recall  f1-score   support

      Normal       0.93      0.40      0.56       234
   Pneumonia       0.73      0.98      0.84       390

    accuracy                           0.76       624
   macro avg       0.83      0.69      0.70       624
weighted avg       0.81      0.76      0.73       624
```


<summary>Run 2</summary>

```
              precision    recall  f1-score   support

      Normal       0.93      0.70      0.80       234
   Pneumonia       0.84      0.97      0.90       390

    accuracy                           0.87       624
   macro avg       0.89      0.83      0.85       624
weighted avg       0.88      0.87      0.86       624
```


<summary>Run 3</summary>

```
              precision    recall  f1-score   support

      Normal       0.97      0.55      0.70       234
   Pneumonia       0.79      0.99      0.88       390

    accuracy                           0.83       624
   macro avg       0.88      0.77      0.79       624
weighted avg       0.86      0.83      0.81       624
```


<summary>Run 4</summary>

```
              precision    recall  f1-score   support

      Normal       0.98      0.43      0.60       234
   Pneumonia       0.74      0.99      0.85       390

    accuracy                           0.78       624
   macro avg       0.86      0.71      0.72       624
weighted avg       0.83      0.78      0.76       624
```


<summary>Run 5</summary>

```
              precision    recall  f1-score   support

      Normal       0.95      0.59      0.73       234
   Pneumonia       0.80      0.98      0.88       390

    accuracy                           0.84       624
   macro avg       0.88      0.79      0.81       624
weighted avg       0.86      0.84      0.83       624
```


---

### EfficientNet-B0

<summary>Run 1</summary>

```
              precision    recall  f1-score   support

      Normal       0.97      0.50      0.66       234
   Pneumonia       0.77      0.99      0.86       390

    accuracy                           0.80       624
   macro avg       0.87      0.74      0.76       624
weighted avg       0.84      0.80      0.79       624
```


<summary>Run 2</summary>

```
              precision    recall  f1-score   support

      Normal       0.98      0.38      0.55       234
   Pneumonia       0.73      0.99      0.84       390

    accuracy                           0.76       624
   macro avg       0.85      0.69      0.69       624
weighted avg       0.82      0.76      0.73       624
```


<summary>Run 3</summary>

```
              precision    recall  f1-score   support

      Normal       0.96      0.51      0.66       234
   Pneumonia       0.77      0.99      0.87       390

    accuracy                           0.81       624
   macro avg       0.86      0.75      0.76       624
weighted avg       0.84      0.81      0.79       624
```


<summary>Run 4</summary>

```
              precision    recall  f1-score   support

      Normal       0.99      0.32      0.48       234
   Pneumonia       0.71      1.00      0.83       390

    accuracy                           0.74       624
   macro avg       0.85      0.66      0.65       624
weighted avg       0.81      0.74      0.70       624
```


<summary>Run 5</summary>

```
              precision    recall  f1-score   support

      Normal       0.97      0.57      0.72       234
   Pneumonia       0.79      0.99      0.88       390

    accuracy                           0.83       624
   macro avg       0.88      0.78      0.80       624
weighted avg       0.86      0.83      0.82       624
```


---

### DenseNet-121

<summary>Run 1</summary>

```
              precision    recall  f1-score   support

      Normal       0.96      0.75      0.84       234
   Pneumonia       0.87      0.98      0.92       390

    accuracy                           0.89       624
   macro avg       0.91      0.86      0.88       624
weighted avg       0.90      0.89      0.89       624
```


<summary>Run 2</summary>

```
              precision    recall  f1-score   support

      Normal       0.94      0.68      0.79       234
   Pneumonia       0.84      0.97      0.90       390

    accuracy                           0.87       624
   macro avg       0.89      0.83      0.85       624
weighted avg       0.88      0.87      0.86       624
```


<summary>Run 3</summary>

```
              precision    recall  f1-score   support

      Normal       0.95      0.76      0.84       234
   Pneumonia       0.87      0.97      0.92       390

    accuracy                           0.89       624
   macro avg       0.91      0.87      0.88       624
weighted avg       0.90      0.89      0.89       624
```


<summary>Run 4</summary>

```
              precision    recall  f1-score   support

      Normal       0.95      0.75      0.84       234
   Pneumonia       0.87      0.98      0.92       390

    accuracy                           0.89       624
   macro avg       0.91      0.86      0.88       624
weighted avg       0.90      0.89      0.89       624
```


<summary>Run 5</summary>

```
              precision    recall  f1-score   support

      Normal       0.93      0.75      0.83       234
   Pneumonia       0.86      0.96      0.91       390

    accuracy                           0.88       624
   macro avg       0.90      0.86      0.87       624
weighted avg       0.89      0.88      0.88       624
```


---

## With Class Weighting + 0.7 Threshold

### Baseline CNN

<summary>Run 1</summary>

```
              precision    recall  f1-score   support

      Normal       0.93      0.59      0.72       234
   Pneumonia       0.80      0.97      0.88       390

    accuracy                           0.83       624
   macro avg       0.86      0.78      0.80       624
weighted avg       0.84      0.83      0.82       624
```


<summary>Run 2</summary>

```
              precision    recall  f1-score   support

      Normal       0.84      0.84      0.84       234
   Pneumonia       0.90      0.90      0.90       390

    accuracy                           0.88       624
   macro avg       0.87      0.87      0.87       624
weighted avg       0.88      0.88      0.88       624
```


<summary>Run 3</summary>

```
              precision    recall  f1-score   support

      Normal       0.93      0.68      0.79       234
   Pneumonia       0.84      0.97      0.90       390

    accuracy                           0.86       624
   macro avg       0.88      0.83      0.84       624
weighted avg       0.87      0.86      0.86       624
```


<summary>Run 4</summary>

```
              precision    recall  f1-score   support

      Normal       0.93      0.71      0.81       234
   Pneumonia       0.85      0.97      0.90       390

    accuracy                           0.87       624
   macro avg       0.89      0.84      0.86       624
weighted avg       0.88      0.87      0.87       624
```


<summary>Run 5</summary>

```
              precision    recall  f1-score   support

      Normal       0.92      0.78      0.84       234
   Pneumonia       0.88      0.96      0.92       390

    accuracy                           0.89       624
   macro avg       0.90      0.87      0.88       624
weighted avg       0.89      0.89      0.89       624
```


---

### EfficientNet-B0

<summary>Run 1</summary>

```
              precision    recall  f1-score   support

      Normal       1.00      0.20      0.33       234
   Pneumonia       0.67      1.00      0.81       390

    accuracy                           0.70       624
   macro avg       0.84      0.60      0.57       624
weighted avg       0.80      0.70      0.63       624
```


<summary>Run 2</summary>

```
              precision    recall  f1-score   support

      Normal       0.96      0.65      0.78       234
   Pneumonia       0.83      0.98      0.90       390

    accuracy                           0.86       624
   macro avg       0.89      0.82      0.84       624
weighted avg       0.87      0.86      0.85       624
```


<summary>Run 3</summary>

```
              precision    recall  f1-score   support

      Normal       0.95      0.62      0.75       234
   Pneumonia       0.81      0.98      0.89       390

    accuracy                           0.84       624
   macro avg       0.88      0.80      0.82       624
weighted avg       0.86      0.84      0.84       624
```


<summary>Run 4</summary>

```
              precision    recall  f1-score   support

      Normal       0.95      0.45      0.61       234
   Pneumonia       0.75      0.99      0.85       390

    accuracy                           0.79       624
   macro avg       0.85      0.72      0.73       624
weighted avg       0.83      0.79      0.76       624
```


<summary>Run 5</summary>

```
              precision    recall  f1-score   support

      Normal       0.99      0.30      0.46       234
   Pneumonia       0.70      1.00      0.83       390

    accuracy                           0.74       624
   macro avg       0.85      0.65      0.64       624
weighted avg       0.81      0.74      0.69       624
```


---

### DenseNet-121

<summary>Run 1</summary>

```
              precision    recall  f1-score   support

      Normal       0.91      0.82      0.86       234
   Pneumonia       0.90      0.95      0.92       390

    accuracy                           0.90       624
   macro avg       0.90      0.88      0.89       624
weighted avg       0.90      0.90      0.90       624
```


<summary>Run 2</summary>

```
              precision    recall  f1-score   support

      Normal       0.92      0.79      0.85       234
   Pneumonia       0.88      0.96      0.92       390

    accuracy                           0.89       624
   macro avg       0.90      0.87      0.88       624
weighted avg       0.90      0.89      0.89       624
```


<summary>Run 3</summary>

```
              precision    recall  f1-score   support

      Normal       0.90      0.86      0.88       234
   Pneumonia       0.92      0.94      0.93       390

    accuracy                           0.91       624
   macro avg       0.91      0.90      0.91       624
weighted avg       0.91      0.91      0.91       624
```


<summary>Run 4</summary>

```
              precision    recall  f1-score   support

      Normal       0.94      0.79      0.86       234
   Pneumonia       0.89      0.97      0.93       390

    accuracy                           0.90       624
   macro avg       0.91      0.88      0.89       624
weighted avg       0.91      0.90      0.90       624
```


<summary>Run 5</summary>

```
              precision    recall  f1-score   support

      Normal       0.89      0.76      0.82       234
   Pneumonia       0.87      0.95      0.90       390

    accuracy                           0.88       624
   macro avg       0.88      0.85      0.86       624
weighted avg       0.88      0.88      0.87       624
```


---
