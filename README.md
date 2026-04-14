# Metrics-for-Measuring-the-Quality-of-Unstructured-Data

This is the repository for the thesis work _Metrics for Measuring the Quality of Unstructured Data_. The work presents a review of past literature to discuss the use of classifiers as data-driven quality-metrics. 

To evaluate this metrics implemented with classifiers, it proves relevant the probabilistic interpretation of ROC-AUC as the probability of a satisfactory-quality instance to get a higher score than a defective instance. This trained automatic-metrics should comply the property of calibration. 

Bechmarks and datasets indicating fitness for use are an importnat input to train these metrics. The use of the ROC-AUC Delong Test provides a robust statistical base for comparison and validation of competing models.

Note that in the cases of widely studied models, hyperparameter tuning can leverage evidence supported heuristic policies. For less documeted models - or for a more exhaustive search - tools as Optuna can provide a comprehensive approach.

The slides available here show a quick-overview. The document available here is equivalent in content to the one available in the PoliMi database. However, the version available in this GitHub repository has minor style improvements that enhance readability and comfort in visualization/formatting.

