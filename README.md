# Neural Network (gets updated)

#### Sparse Categorical Cross-Entropy
It's a loss function used for classification tasks where the target labels are integers rather than one-hot encoded vectors. It's particularly useful for multi-class classification problems.
##### When to Use It:
- Sparse Labels: When your target labels are integers (e.g., 0, 1, 2, ...), use sparse categorical cross-entropy.
- One-Hot Encoded Labels: If your labels are one-hot encoded vectors, you should use categorical cross-entropy instead.
- Using sparse categorical cross-entropy is computationally efficient because it directly uses the integer labels instead of converting them to one-hot vectors, thus saving memory and computation time.