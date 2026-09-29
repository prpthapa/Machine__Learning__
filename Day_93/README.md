# Day 93 — ROC-AUC Curve

Today I learned about the ROC-AUC Curve and how it can be used to evaluate the performance of classification models.

## 📚 Topics Learned

### 1. ROC Curve

ROC stands for Receiver Operating Characteristic.

The ROC Curve shows the relationship between:

```text
True Positive Rate (TPR)
        vs
False Positive Rate (FPR)
```

It is created by changing the classification threshold and observing how the model's TPR and FPR change.

---

### 2. True Positive Rate (TPR)

True Positive Rate tells us how many of the actual positive cases were correctly identified by the model.

It is also known as Recall.

```text
TPR = TP / (TP + FN)
```

Where:

```text
TP → True Positive
FN → False Negative
```

---

### 3. False Positive Rate (FPR)

False Positive Rate tells us how many of the actual negative cases were incorrectly predicted as positive.

```text
FPR = FP / (FP + TN)
```

Where:

```text
FP → False Positive
TN → True Negative
```

---

## 📈 ROC Curve

The ROC Curve plots:

```text
Y-axis → True Positive Rate (TPR)

X-axis → False Positive Rate (FPR)
```

As the classification threshold changes, the TPR and FPR also change.

This gives us different points that form the ROC Curve.

---

## 🎯 Classification Threshold

A classification model often produces a probability rather than directly giving a class.

For example:

```text
Predicted Probability = 0.80
```

If the threshold is:

```text
0.50
```

The prediction would be:

```text
0.80 ≥ 0.50
→ Positive
```

Changing the threshold changes which observations are classified as positive or negative.

Therefore, the threshold affects both:

```text
TPR
FPR
```

The ROC Curve shows this behavior across different thresholds.

---

## 📊 AUC

AUC stands for Area Under the Curve.

It represents the area under the ROC Curve and provides a single value summarizing the model's ability to distinguish between positive and negative classes.

```text
AUC → Area Under the ROC Curve
```

A model with better class-separation ability generally produces an ROC curve with more area toward the upper-left region of the graph.

---

## 🔗 Connection with Previous Metrics

ROC-AUC connects with the classification metrics I learned previously.

```text
Confusion Matrix
       ↓
TP, TN, FP, FN
       ↓
TPR and FPR
       ↓
ROC Curve
       ↓
AUC
```

Recall is also the same as True Positive Rate:

```text
Recall = TPR
```

---



Continuing to understand classification model evaluation step by step.
