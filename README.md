Project Overview

This repository contains the implementation and documentation for my research project on developing an advanced Intrusion Detection System (IDS) using both machine learning and deep learning techniques. The goal of this project is to compare the effectiveness of various computational models in detecting network intrusions.

Objectives

	•	To implement and evaluate the performance of different models including Linear SVM, MLP, and CNN on the KDD Cup 1999 dataset.
	•	To analyze the strengths and weaknesses of machine learning vs. deep learning approaches in the context of IDS.
	•	To provide a comprehensive comparison of model performances based on accuracy, precision, recall, and F1-score.

Dataset

The dataset used is the KDD Cup 1999 dataset, which is a widely used data set for network-based intrusion detection systems. This dataset includes a wide variety of intrusions simulated in a military network environment.

Methods

	•	Data Preprocessing: Standardization of numerical features, encoding of categorical features, and handling of class imbalance.
	•	Model Implementation:
	•	Linear SVM (LSVM) for baseline performance.
	•	Multi-Layer Perceptron (MLP) to capture non-linear relationships.
	•	Convolutional Neural Network (CNN) to exploit spatial correlations in sequence data.
	•	Evaluation: Models were evaluated using metrics like accuracy, precision, recall, and F1-score. Additional insights were derived from confusion matrices and ROC curves.

Results

The models demonstrated the following key performances:

	•	LSVM showed good overall accuracy but struggled with class imbalance.
	•	MLP and CNN outperformed LSVM in terms of accuracy and were better at handling imbalanced data.
