# EEG-Classification
Classification of EEG data (The Data consists of 14 Healthy and 14 Schizophrenia Patients)

EEG Classification for Schizophrenia

Introduction

Electroencephalography (EEG) is a non-invasive technique for measuring the electrical activity of the brain.
This technology is commonly used for diagnosing various neurological conditions, including schizophrenia.
The aim of EEG classification for schizophrenia is to develop machine learning algorithms that can accurately
identify patients with this disorder based on their EEG signals.

Data Collection

EEG signals are collected from patients with schizophrenia and healthy individuals.
The EEG signals are typically recorded while the subjects are resting with their eyes closed or performing simple tasks,
such as counting or imagining movements.
The collected EEG data is then divided into training and testing sets for use in the machine learning algorithms.

Feature Extraction

Before the EEG signals can be used for classification,they must be processed to extract relevant features.
This involves transforming the raw EEG signals into numerical representations that capture the underlying patterns in the data.
Commonly used feature extraction methods include power spectral density (PSD) analysis, time-frequency analysis, and independent component analysis (ICA).

Classification Algorithms

Once the features have been extracted from the EEG signals,
various machine learning algorithms can be applied for classification.
Commonly used algorithms include support vector machines (SVM), decision trees, random forests, and deep neural networks (DNN).
The performance of these algorithms is typically evaluated using metrics such as accuracy, precision, recall, and F1 score.


In this project we will be working on classification of EEG data for Healthy and Patients with Schizophrenia.
The Dataset we will be using in this paper is : http://dx.doi.org/10.18150/repod.0107441

In the dataverse_files you will find the eeg data for 14 healthy and 14 patients with schizophrenia. The .edf files with "h" are Healthy and with "s" are the patients suffering with schizophrenia.

The dataset comprised 14 patients with paranoid schizophrenia and 14 healthy controls. Data were acquired with the sampling frequency of 250 Hz using the standard 10-20 EEG montage with 19 EEG channels: Fp1, Fp2, F7, F3, Fz, F4, F8, T3, C3, Cz, C4, T4, T5, P3, Pz, P4, T6, O1, O2. The reference electrode was placed between electrodes Fz and Cz.

Learn the steps to analyze Electroencephalography (EEG) data, including its processing, feature extraction, and classification using sklearn classifiers. Utilizing Machine Learning and EEG, the goal is to categorize the presence of schizophrenia.



