# Classification-of-Arrhythmia-ECG-DATA
# The dataset used in this project is available on the UCI machine learning Repository. (https://archive.ics.uci.edu/dataset/5/arrhythmia)
- Analyzed a dataset comprising 452 instances across 16 classes, with 245 cases representing individuals without arrhythmias ("normal").
- Explored 12 distinct arrhythmia types, emphasizing the significance of "coronary artery disease" and "Rjgbt bundle branch block."
- Leveraged a dataset encompassing 279 features, including patient age, sex, weight, height, and other relevant information.
- Acknowledged the challenge of a relatively high feature-to-example ratio, highlighting the need for sophisticated predictive modelling.
- Developed a predictive model to assess the presence of arrhythmia in individuals, aiming to classify cases into one of the 12 specific arrhythmia groups.

# Conclusion

By applying Principal Component Analysis (PCA) to the resampled data, we observed notable enhancements in model performance. PCA proved effective in simplifying data complexity by emphasizing variables with significant variance. The generated non-collinear components played a crucial role in mitigating collinearity issues within the large dataset. This resulted in improved overall execution time and model quality, particularly advantageous when dealing with an extensive array of variables.

Notably, the most successful model, achieving a remarkable recall score, was the **Random Forest Classifier with PCA**, attaining an outstanding accuracy of **99.5%**. This underscores the potency of leveraging PCA in conjunction with the Random Forest model for robust and accurate predictions.
