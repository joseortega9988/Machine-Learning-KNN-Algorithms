# Machine-Learning-KNN-Algorithms

## Introduction
The notebook is part of a comprehensive Machine Learning coursework designed to enhance practical skills in implementing various machine learning methods using Python. It particularly emphasizes parameter selection, the evaluation of ML methods, and the application of cross-validation. The coursework does not rely on pre-built library functions for crucial aspects of machine learning but instead focuses on manual implementation for a deeper understanding.

### Dataset Used:
The project utilizes the Wine dataset, a collection comprising 178 samples that categorize three different types of Italian wine based on 13 distinct features. For the purposes of this study, only a select subset of these features is employed for in-depth analysis.

### Implementing k-Nearest Neighbors (kNN):
This section of the project is dedicated to the manual implementation of the k-Nearest Neighbors algorithm. Key activities include:

#### 1. Implementation of Distance Functions for kNN:
   - The project includes developing helper functions essential for the kNN algorithm, specifically focusing on distance calculations. Both Manhattan and Euclidean distance functions are implemented, highlighting an exploration of varied approaches to measuring distances between data points.

#### 2. Testing kNN Implementation:
   - An integral part of the project involves testing the custom kNN function. This includes the designation of features and target labels for training and test datasets, followed by the application of the `mykNN` function using these datasets and the developed distance functions. The outcomes using both Euclidean and Manhattan distances are analyzed and discussed.

### Classifier Evaluation:
The project also encompasses a thorough classifier evaluation segment. Key components include:

- Development of custom code for generating confusion matrices and computing standard metrics like accuracy.
- Creation of methods for presenting confusion matrix results in a clear, understandable format.
- Performing comparative analyses with the sklearn library’s results to assess the accuracy and efficiency of the custom implementations.
