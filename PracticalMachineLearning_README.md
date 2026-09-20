# Practical Machine Learning: Prediction Assignment

**Author:** Sanidhya Singhal

This project predicts barbell-lift technique from wearable-sensor measurements. The analysis removes collection metadata and sparse fields, compares tree-based classifiers, tunes a random forest with five-fold cross-validation, estimates out-of-sample error on a held-out validation set, and predicts the 20 course quiz cases.

## Submission files

- [`practical_machine_learning.Rmd`](practical_machine_learning.Rmd): reproducible R Markdown analysis
- [`practical_machine_learning.html`](practical_machine_learning.html): compiled report
- [`quiz_predictions.csv`](quiz_predictions.csv): predictions for the 20 quiz cases

The R Markdown downloads the two public course CSV files automatically when they are not already available locally. Required R packages are `caret`, `randomForest`, and `rmarkdown`.

Validation accuracy was 99.61%, corresponding to an estimated out-of-sample error of 0.39%.
