## Final Project - Political Toxicity Classifiers

For CIS 5/731. 

This project is meant to experimentally compare standard (non-LLM) classifiers for text data against an LLM classifier. Using Apache Spark, this project should be able to conduct structured streaming to take in large and new forms of social media text data and produce an accurate classfiication of toxic or not.

**Hypothesis:"" LLM classifiers are no more accurate than standard classifiers for political toxicity.

Deliverables:
- Trained (RandomForest, Linear Regression, KNN, and other) standard NLP classifiers on the [HOT](https://socialmediaarchive.org/record/19?ln=en&v=pdf) political toxicity dataset
- Trained LLM for classifying political toxicity
- Accuracy comparison and data visuals for all classifiers used
