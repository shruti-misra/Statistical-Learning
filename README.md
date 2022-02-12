# EE 511 Statistical Learning

This class Covers classification and estimation of vector observations, including both parametric and nonparametric approaches. Includes classification with likelihood functions and general discriminant functions, density estimation, supervised and unsupervised learning, and feature reduction. Specific methods covered include Naive Bayes, decision trees, support vector machines and neural networks.

The repo contains code developed during class assignment and the class project (done in conjuction with a partner)

## Assigments

Each assignment as a theoretical and a programming part. The repo contains code for the programming section

- Assignment 1: Developed a k-nearest neighbor classifier and a Gaussian classifier 
- Assignment 2: Focused on learning how to preprocess data, do a least squares linear regression model and regularization
- Assignment 3: Developed an SVM model to predict which post belongs to which of the 20 newsgroups in the dataset
- Assignment 4: Trained a basic neural network and an autoencoder for reconstructing images from the Galaxy Zoo project
- Assignment 5: Developed a Recurrent Neural Network (RNN) model to identify te language of a Tweet 

## Project 

My partner and I implemented and analyzed various machine learning techniques to classify audio tracks into 10 different musical genres. We used a modified subset of the Million Song Dataset (MSD) which provides already extracted feature vectors for 1 million songs. We first established baseline models for the classification task such as Random Classification, Gaussian Mixture Models and Support Vector Machines. Next, we implemented neural network models such as Convolutional Neural Networks (CNNs)
and Convolutional Recurrent Neural Networks (CRNNs). Both the neural network models surpassed the accuracy of the baseline models and CRNNs perform
better than CNNs. To understand the impact of different features on performance, we implement GMMs and CRNNs with just timbral and pitch features. Thus, we
proposed two neural network architectures that surpass the baseline models and are comparable to models found in existing literature. ∂