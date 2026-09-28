# Day 92 — Precision, Recall & F1 Score

Today I learned about Precision, Recall, and F1 Score, which are important metrics used to evaluate classification models.

## 📚 Topics Learned

### 1. Precision

Precision tells us how many of the positive predictions made by the model were actually positive.

It focuses on the correctness of positive predictions.

```text
Precision = TP / (TP + FP)
```

Where:

```text
TP → True Positive
FP → False Positive
```

A higher Precision means that fewer negative cases are incorrectly predicted as positive.

---

### 2. Recall

Recall tells us how many of the actual positive cases were correctly identified by the model.

It focuses on finding as many actual positive cases as possible.

```text
Recall = TP / (TP + FN)
```

Where:

```text
TP → True Positive
FN → False Negative
```

A higher Recall means that fewer actual positive cases are missed by the model.

---

### 3. F1 Score

F1 Score combines Precision and Recall into a single metric.

It uses the harmonic mean of Precision and Recall.

```text
F1 Score = 2 × (Precision × Recall) / (Precision + Recall)
```

F1 Score is useful when we want to consider both Precision and Recall together.

---

## 📊 Precision vs Recall

| Metric    | Main Question                                                            |
| --------- | ------------------------------------------------------------------------ |
| Precision | Of the cases predicted as positive, how many were actually positive?     |
| Recall    | Of the actual positive cases, how many did the model correctly identify? |
| F1 Score  | How well are Precision and Recall balanced?                              |

---

## 🔗 Connection with Confusion Matrix

Precision, Recall, and F1 Score are calculated using values from the Confusion Matrix.

```text
TP → True Positive
TN → True Negative
FP → False Positive
FN → False Negative
```

Precision mainly depends on:

```text
TP and FP
```

Recall mainly depends on:

```text
TP and FN
```

F1 Score combines:

```text
Precision + Recall
```

##
