# Predict New Medicines with BELKA
# It's about one question: Can a model recognize something it has never seen before?

Kaggle Competition: Public LB Top 8%, Private LB Top 12%

##The Research Question

The competition evaluated not only predictive performance but also a model's ability to generalize beyond the distribution represented in the training data. The hidden evaluation introduced entirely new molecular building blocks, making this a study of robustness under distribution shift rather than benchmark optimization.


##Initial Hypothesis

Transformers should produce better predictions.
SMILES tokenization is all we need.
Maybe Transformers and CNN hybrid models.
Rigorous cross-validation for robustness.

##What I Explored

Different representations of molecular sequences.
The effect of fine-tuning on unseen chemical space.
Model simplicity versus specialization.
Training strategies that balance fitting and generalization.


## What Changed My Mind

My initial focus was improving leaderboard performance. 
However, the hidden evaluation demonstrated that success on familiar data does not necessarily translate to unseen chemistry. Through experimentation, I found that lightly fine-tuned transformer models often generalized better than aggressively optimized models, while surprisingly simple CNN baselines remained highly competitive.



## Reflection

A model's true capability is revealed by what it has never seen.

This competition changed how I evaluate machine learning models. 
Can models truly generalize to unseen data in real-world, complex biological scenarios?
This competition raises concerns about model reliability in such cases, underscoring the need for further research.

## Data
Data can be accessed on [Kaggle BELKA Dataset](https://www.kaggle.com/c/neurips-2024-predict-new-medicines/data).
