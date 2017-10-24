# MINI_PROJECT_ECOLO_TEAM

DATA SELECTION :

- ML PROBLEM: choose ONLY problems of classification or regression (no recommendation, no reinforcement learning, etc.). Choose SIMPLE standard metrics (e.g. balanced accuracy or AUC for classification, r-square for regression).
- GOOD DATA is essential: spend enough time hunting for data, ask your instructors for feed-back and advice BEFORE your turn in the proposal. The data must be readily available and publicly available (no proprietary data). The problem must be interesting, but KEEP IT SIMPLE: Avoid data that are too noisy and/or have many missing values, have a large number of classes (>20) and have too few examples per class (less than 1000 in test data). Avoid data that are non homogeneous or non identically distributed. Avoid problems that are too easy or too hard. Visualize your data to check it is sounds.
- ENOUGH DATA: do not consider small datasets of less than 50 000 examples. You must have at least 10 000 test examples and preferably a large training set and a validation set of the same order of magnitude as the test set.
- PREPROCESSING: You will need to PREPROCESS the data to make your challenge easy enough for L2 students. All data will have to be preprocessed in a fixed length FEATURE REPRESENTATION. Take into account the effort of preprocessing when you select data.
- NOT TOO BIG DATA: we want enough samples, but the overall preprocessed compressed volume of data should not exceed 300 MB. Quantizing values to enough precision (but not to much) is recommended, as part of preprocessing.
- BASELINE: You will need to provide baseline methods (easy simple learning machines) for the L2 students AND you will need to try to beat the state-of-the-art on this problem (for your report). Choose a problem that you understand well and for which there are publications you can read. For classification problems, shoot for problems with between ~80 and 90% accuracy. Problems outside this bracket are probably too easy or too hard. For regression problem, shoot for problems with an R2 between 0.75 and 0.95. Check for “data leakage” that is for features that inform inadvertently about the target values: running a feature selection algorithm often reveals such features.
- TOPIC: Remain within the main topic of your team. If you find an interesting problem outside the topic of the team, ask the instructors whether it is OK to switch.



Anciens projets : https://sites.google.com/a/chalearn.org/saclay/
