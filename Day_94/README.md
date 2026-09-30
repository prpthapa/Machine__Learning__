# Day 94 — Softmax Regression & Multinomial Regression

Today I learned about Softmax Regression and Multinomial Regression for solving multiclass classification problems.

## 📚 Topics Learned

### 1. From Binary to Multiclass Classification

Previously, I learned about Logistic Regression for binary classification.

For example:

```text
0 → Not Spam
1 → Spam
```

But many real-world problems have more than two classes.

For example:

```text
0 → Cat
1 → Dog
2 → Bird
```

This is called multiclass classification.

---

## 2. Softmax Regression

Softmax Regression is an extension of Logistic Regression that can be used for multiclass classification.

Instead of producing a probability for only one class, Softmax produces a probability for each possible class.

For example:

```text
Cat  → 0.10
Dog  → 0.75
Bird → 0.15
```

The probabilities add up to:

```text
0.10 + 0.75 + 0.15 = 1.00
```

The class with the highest probability becomes the model's prediction.

```text
Highest Probability
        ↓
   Predicted Class
```

---

## 3. Softmax Function

The Softmax function converts the raw scores produced by the model into probabilities.

For a class i:

```text
Softmax(zᵢ) = eᶻⁱ / Σⱼ eᶻʲ
```

The output probabilities are between 0 and 1, and the probabilities across all classes sum to 1.

---

## 4. Multinomial Regression

Multinomial Regression refers to regression/classification models that handle multiple possible categories.

In the context of classification, Softmax Regression is commonly used for multiclass problems.

Instead of deciding between only two classes:

```text
Class 0 vs Class 1
```

the model can choose between multiple classes:

```text
Class 0
Class 1
Class 2
Class 3
...
```

---

## 5. Example

Suppose we want to classify an image into three categories:

```text
Cat
Dog
Bird
```

The model produces scores and Softmax converts them into probabilities:

```text
Cat  → 0.20
Dog  → 0.65
Bird → 0.15
```

Since Dog has the highest probability:

```text
Prediction → Dog
```

---

## 🔗 Logistic Regression vs Softmax Regression

| Logistic Regression                     | Softmax Regression                  |
| --------------------------------------- | ----------------------------------- |
| Mainly used for binary classification   | Used for multiclass classification  |
| Two possible classes                    | More than two possible classes      |
| Produces probability for binary outcome | Produces probability for each class |
| Uses Sigmoid                            | Uses Softmax                        |

---


=

Continuing to build my understanding of classification algorithms step by step.
