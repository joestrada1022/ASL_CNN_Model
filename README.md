# American Sign Language (ASL) Classification Model
**Comparison between Artificial and Convolutional Neural Networks**

This project aims to enhance communication accessibility for deaf and hard-of-hearing individuals who use American Sign Language (ASL) as their primary mode of communication. Our goal is to develop a model that can detect ASL letters from A to Z (excluding J and Z) using a live camera feed. To achieve this, we utilize two machine learning models: Convolutional Neural Networks (CNN) and Artificial Neural Networks (ANN).

## Dataset
Our dataset, sourced from Kaggle, consists of 34,000 images representing ASL hand gestures.
https://www.kaggle.com/datasets/datamunge/sign-language-mnist

## Model Comparison
We implemented and compared both the CNN and ANN models to determine their effectiveness in real-time ASL letter recognition. Through hands-on demonstrations, we found that the CNN model outperformed the ANN model in terms of accuracy and reliability.

## Challenges
However, our models encountered challenges with letters that have similar hand gestures, resulting in misclassifications. Addressing gesture similarities is crucial for improving model performance.

## Future Work
Future work will focus on incorporating the dynamic letters J and Z, as well as expanding the model to recognize whole words. This will enhance its practical applications for real-world use.
