# Day 96 — Bayes Theorem in Probability

Today I focused on understanding Bayes Theorem and how it is used to update probabilities when new information or evidence becomes available.

## 📚 Topics Learned

### 1. Bayes Theorem

Bayes Theorem helps us calculate the probability of an event when we have some new evidence or information.

The formula is:

```text
P(A | B) = P(B | A) × P(A) / P(B)
```

Where:

```text
P(A | B) → Posterior Probability
P(B | A) → Likelihood
P(A)     → Prior Probability
P(B)     → Evidence
```

---

## 2. Understanding the Terms

### Prior Probability

Prior probability is what we believe about an event before considering the new evidence.

```text
Prior → What we knew before
```

For example, if we know that 10% of emails are spam, then:

```text
P(Spam) = 0.10
```

This is the prior probability.

---

### Likelihood

Likelihood tells us how probable the observed evidence is when the event is true.

For example:

```text
P(Word "offer" | Spam)
```

This asks:

```text
How likely is the word "offer"
to appear when an email is spam?
```

---

### Evidence

Evidence represents the overall probability of observing the given information.

```text
P(B)
```

It considers how likely the evidence is across all possible cases.

---

### Posterior Probability

Posterior probability is the updated probability after considering the new evidence.

```text
Prior + New Evidence
        ↓
    Posterior
```

For example:

```text
Before seeing evidence:
P(Spam) = 0.10

After seeing evidence:
P(Spam | "offer") = updated probability
```

---

## 3. Simple Example

Suppose:

```text
P(Spam) = 0.10
```

This means 10% of emails are spam.

Now suppose we observe the word "offer".

We want to find:

```text
P(Spam | "offer")
```

Bayes Theorem allows us to update our belief about whether the email is spam after observing the word "offer".

```text
Initial belief
     ↓
Observe evidence
     ↓
Apply Bayes Theorem
     ↓
Updated probability
```

This is the basic idea behind Bayesian reasoning.

---

## 4. Bayes Theorem and Machine Learning

Bayes Theorem is especially important in probability-based machine learning algorithms such as Naive Bayes.

The general idea is:

```text
Features / Evidence
        ↓
Bayes Theorem
        ↓
Probability of each class
        ↓
Choose the most probable class
```



