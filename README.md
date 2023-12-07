# Project Title

Unlabeled Data Labeling with Acquisition Functions - Human in the loop for machine learning

## Introduction

This project aims to label the MNIST digits dataset using acquisition functions (AFs) to determine which unlabeled data the model should prioritize for labeling. By comparing different AFs, we can identify the most effective strategy for selecting data points to improve the model's performance.

To elaborate, the dataset is labeled, but in this project I will treat it as if its not labeled and let some function determine what the most interesting unlabeled datapoint is and train on the new acquired data. I compare this to regular training which an equal sized datgaset to see what AF works best.

## Getting Started

### Installation

1. Before you start, ensure have an environment (I've created a .yml file to install a conda environment):
  ```shell
  conda env create -f environment.yml
```

1. Clone the repository:

   ```shell
   git clone https://github.com/wouterharinghuizen/HITL.git
   
Navigate to the project directory:


Contact
For questions or collaboration, feel free to contact me at [wouterharinghuizen@hotmail.com].





