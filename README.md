# Sweet-Dreams-A-Comparative-Study-of-Sleep-Quality-Classifiers

The "Sweet Dreams: A Comparative Study of Sleep Quality Classifiers" Github repository contains code and data related to a project focused on evaluating the performance of six different classifiers for sleep stage scoring.

Sleep quality is a crucial factor in maintaining good health and well-being. Polysomnographic (PSG) recordings are widely used to measure sleep quality by capturing different types of physiological data including electroencephalogram (EEG), electrooculogram (EOG), electromyogram (EMG), and electrocardiogram (ECG). The PSG recording divides into non-overlapping time windows (segments) based on the American academy of sleep medicine (AASM) manual recommendation and each segment is classified into one of the five sleep stages.

The project used sleep data from the SC Sleep-EDF Database [Expanded], which is available through Physionet for training and evaluation purposes. The dataset consists of 15 features extracted from the brain signals of 8 subjects, along with sleep category labels for wakefulness, light sleep + REM, and deep sleep.

The objective of the project was to compare the performance of six different classifiers: Naïve Bayes, Decision Tree, Random Forest, Linear discriminate analysis, Quadratic discriminate analysis, and Multilayer Perceptron using 10-fold cross-validation. The classifiers were trained using different numbers of features, starting from one and increasing to 15.

The performance of each classifier was evaluated by comparing the accuracy versus the number of features using a curve. The best number of features and corresponding accuracy for each method were recorded in a table. The test performance was also evaluated using the best number of features for each sleep category, and metrics such as confusion matrix, accuracy, sensitivity, specificity, F1-score, false positive rate, and false negative rate were calculated.

The results were presented in a PowerPoint presentation, which includes tables and figures for a better understanding of the study. The repository contains code for data preprocessing, feature selection, and classifier implementation in Python. It also includes the sleep dataset used in the project.

![maxresdefault](https://user-images.githubusercontent.com/52755021/225415389-bb601eaa-7192-4af4-a4e6-7fb8c2a4c0f9.jpg)




