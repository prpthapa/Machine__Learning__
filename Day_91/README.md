# Day 91 — Accuracy, Confusion Matrix & Classification Metrics

Today I learned about classification metrics and how to evaluate the performance of a classification model.

## 📚 Topics Learned

### 1. Accuracy

Accuracy measures how many predictions a classification model got correct out of all the predictions.

The basic idea is:

```text
Accuracy = Correct Predictions / Total Predictions
```

It gives an overall idea of how well the model is performing.

---

### 2. Confusion Matrix

A Confusion Matrix provides a detailed breakdown of the predictions made by a classification model.

It contains four important values:

| Actual / Predicted | Positive            | Negative            |
| ------------------ | ------------------- | ------------------- |
| Positive           | True Positive (TP)  | False Negative (FN) |
| Negative           | False Positive (FP) | True Negative (TN)  |

### True Positive (TP)

The model predicted Positive, and the actual value was also Positive.

### True Negative (TN)

The model predicted Negative, and the actual value was also Negative.

### False Positive (FP)

The model predicted Positive, but the actual value was Negative.

### False Negative (FN)

The model predicted Negative, but the actual value was Positive.

---

## ⚠️ Type 1 Error

Type 1 Error occurs when the model predicts Positive when the actual class is Negative.

It is also called a False Positive (FP).

```text
Actual:    Negative
Predicted: Positive

→ Type 1 Error
→ False Positive
```

---

## ⚠️ Type 2 Error

Type 2 Error occurs when the model predicts Negative when the actual class is Positive.

It is also called a False Negative (FN).

```text
Actual:    Positive
Predicted: Negative

→ Type 2 Error
→ False Negative
```

---

## 📊 Classification Metrics

I learned that accuracy alone may not always be enough to understand the performance of a classification model.

The Confusion Matrix helps us understand exactly where the model is making correct and incorrect predictions.

The four basic outcomes are:

```text
TP → Correct Positive Prediction
TN → Correct Negative Prediction
FP → Incorrect Positive Prediction
FN → Incorrect Negative Prediction
```

These values form the foundation for other classification metrics such as Precision, Recall, and F1-Score.

---

## 🧠 Key Takeaways

* Accuracy measures the overall correctness of predictions.
* A Confusion Matrix gives a detailed breakdown of predictions.
* TP and TN represent correct predictions.
* FP and FN represent incorrect predictions.
* Type 1 Error = False Positive.
* Type 2 Error = False Negative.
* Different classification metrics provide different perspectives on model performance.


