# ML-Final-project

## INTRODUCTION

The diet of modern life is irregular, the work pressure is high, genetically modified foods, and cancer is commonplace in our lives. Breast cancer is the most frequently encountered cancer type in women and the second most terminal one after lung cancer. Due to the clinical experience of the doctors based on the doctor's work experience, relatively young doctors are not experienced enough to find early symptoms. It is very helpful if employed the artificial intelligent technique to assist doctors in diagnosing patients.

In this project, we used four methods to diagnose patients who had breast cancer. In order to train the model, we use the data from UC Irvine “Breast Cancer Wisconsin” data set. In this dataset, there are 569 entries, with 357 benign cases and 212 malignant cases. Each column contains 33 features, but there are some useless features. After comparison study, we found that Deep Learning could achieve better result without feature selection. 

Though these models cannot diagnose cancer conclusively, it could help physicians in deciding whether a biopsy is required by providing information about whether the patient has breast cancer or not. Using our models can help doctors prepare for diagnosis to provide effective information and improve the cure rate of early patients. Studies have shown that using machine learning methods to help doctors diagnose can give a more accurate result.

## METHODOLOGIES
### 1 Support Vector Machine
The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space (N — the number of features) that distinctly classifies the data points.

A Support Vector Machine (SVM) is a discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples. In two dimentional space this hyperplane is a line dividing a plane in two parts where in each class lay in either side.

### 2.Random Forest
The random forest is a model made up of many decision trees. Rather than just simply averaging the prediction of trees (which we could call a “forest”), this model uses two key concepts that gives it the name random: Random sampling of training data points when building trees

### 3. KNN
K-Nearest Neighbors, or KNN for short, is one of the simplest machine learning algorithms and is used in a wide array of institutions. KNN is a non-parametric, lazy learning algorithm. When we say a technique is non-parametric, it means that it does not make any assumptions about the underlying data. In other words, it makes its selection based off of the proximity to other data points regardless of what feature the numerical values represent. Being a lazy learning algorithm implies that there is little to no training phase. Therefore, we can immediately classify new data points as they present themselves.

### 4. Deep Learning 
Deep learning is an increasingly popular subset of machine learning. Deep learning models are built using neural networks. A neural network takes in inputs, which are then processed in hidden layers using weights that are adjusted during training. Then the model spits out a prediction. The weights are adjusted to find patterns in order to make better predictions. The user does not need to specify what patterns to look for — the neural network learns on its own.



