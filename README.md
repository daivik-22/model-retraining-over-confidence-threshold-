# Project: Continuous Learning with Confidence-Based Retraining

- This project is a full implementation of a ML pipeline that retrains itself using its most confident predictions.
- The idea is simple: if the model is sure it's right (prob > 0.78), it uses that data to learn and get better.

- Key Insight: I observed that while probabilities do get higher, this approach carries a risk of false confidence—where the model becomes more certain of its predictions,
even when they're wrong, if those errors are repeatedly reinforced.

- Check out the code, and credit is appreciated if you find it useful!
