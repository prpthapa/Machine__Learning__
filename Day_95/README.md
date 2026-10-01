# Day 95 — Naive Bayes Classifier & Conditional Probability

Today I learned about Conditional Probability, Bayes Theorem, and the Naive Bayes Classifier.

## 📚 Topics Learned

### 1. Conditional Probability

Conditional Probability tells us the probability of an event occurring when we already know that another event has occurred.

For example:

```text
What is the probability of A
when we already know that B has happened?
```

The formula is:

```text
P(A | B) = P(A ∩ B) / P(B)
```

Where:

```text
P(A | B) → Probability of A given B
P(A ∩ B) → Probability of A and B occurring together
P(B) → Probability of B
```

---

### 2. Bayes Theorem

Bayes Theorem helps us calculate the probability of a hypothesis or class based on available evidence.

The basic idea is:

```text
Prior Probability
        +
     Evidence
        ↓
Updated Probability
```

This idea is important for understanding how Naive Bayes works.

---

## 3. Naive Bayes Classifier

Naive Bayes is a classification algorithm based on Bayes Theorem.

It calculates the probability of each possible class based on the given features.

For example, suppose we want to classify an email as:

```text
Spam
Not Spam
```

The model looks at the available features and calculates the probability of each class.

The class with the highest probability is selected as the prediction.

```text
Probability of Spam       → 0.85
Probability of Not Spam  → 0.15

Prediction → Spam
```

---

## 4. Why is it called "Naive"?

The algorithm makes a simplifying assumption:

```text
Features are conditionally independent
given the class.
```

For example, if an email contains multiple words, Naive Bayes assumes that the presence of one word is independent of another word once the class is known.

This assumption is not always perfectly true, but it makes the algorithm simple and computationally efficient.

---

## 5. Naive Bayes Classification Process

The general process is:

```text
Input Features
      ↓
Calculate probabilities
      ↓
Apply Bayes Theorem
      ↓
Calculate probability for each class
      ↓
Compare class probabilities
      ↓
Choose the class with highest probability
```

---



Continuing to strengthen my understanding of probability-based machine learning algorithms step by step.
