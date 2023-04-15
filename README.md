# Face Recognition using K Nearest Neighbours and PCA

## Introduction:
Following are the results of face image classification using the k-nearest neighbours (KNN) algorithm with my own implementation in Python. The code for the experiment is provided in a Jupyter notebook. The experiment involves testing different k values ranging from 1 to 10 for calculating the average accuracy.

## Methodology:
1. Data: The CMU Pose, Illumination, and Expression (PIE) database
(http://ieeexplore.ieee.org/abstract/document/1004130/) consists of 41,368 images of 68 subjects.
Each person is under 13 different poses, 43 different illumination conditions, and with 4 different
expressions.
2. Preprocessing: The face images are preprocessed to extract relevant features using Principal Component Analysis (PCA) technique.
3. Implementation: The KNN algorithm is implemented using Python, and different k values ranging from 1 to 10 are tested.
4. Evaluation: The accuracy of the KNN algorithm is calculated for each k value using 5 splits cross-validation.

## Results:
The experiment results show the average accuracy of the KNN algorithm for face image classification ,further exact details are provided in the report 

## Conclusion:
In conclusion, the experiment demonstrates the implementation of the KNN algorithm for face image classification using PCA for feature extraction.Using PCA significantly improves the computational time and also accuracy of the model when using mahalanobis distance as the distance measure.Further the provided code in the Jupyter notebook can serve as a reference for future work in face recognition experiments.

