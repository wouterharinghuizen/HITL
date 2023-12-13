# Leveraging Dropout-Based Acquisition Function for Active Learning in Machine Learning

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the code and research paper for "Leveraging Dropout-Based Acquisition Function for Active Learning in Machine Learning." This paper explores a novel dropout-based Acquisition Function (AF) for active learning and compares it with the traditional entropy-based AF. The research aims to provide insights into the effectiveness of these AFs in guiding the selection of informative data points for labeling.

## Abstract

Active learning is a machine learning paradigm that optimizes the learning process by selecting the most informative data points for labeling. In this paper, we introduce a dropout-based AF alongside the traditional entropy-based AF. Our comprehensive analysis and experiments on benchmark datasets evaluate the performance of these AFs in terms of model accuracy and labeling efficiency.

## Getting Started

To replicate the experiments and explore the code, follow the steps below:

1. Clone this repository to your local machine:

3. Open the notebook that walk you through the process

## Datasets

We conducted experiments on benchmark datasets, with a primary focus on the MNIST dataset for handwritten digit recognition.

## Hyperparameters

We maintained consistent hyperparameters for a fair comparison between AFs, including learning rates, batch sizes, and optimization algorithms.

## Experimental Results

Our experiments revealed interesting insights into labeling efficiency and the distribution of labels acquired during the active learning process. Detailed results can be found in the paper (if published link will show here)

## Practical Considerations

Implementing AFs in real-world scenarios requires careful evaluation and potential modifications. The paper discusses resource optimization and reduced human intervention as practical benefits of active learning with AFs.

## Comparative Analysis

The paper provides a comparative analysis of entropy-based and dropout-based Acquisition Functions, highlighting their strengths and limitations.

## Future Research

The unexpected results regarding dropout-based AFs call for further investigation into the factors contributing to their performance disparities in different studies. Future research could explore modifications and enhancements to improve their reliability and effectiveness.

## Conclusion

In conclusion, our research contributes valuable insights into the selection and performance of AFs for active learning in machine learning. While the dropout-based AF method did not perform as expected in our experiments, it opens doors for future research to enhance its reliability and effectiveness.
