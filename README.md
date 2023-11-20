# targeted-PGD

This project implements a targeted PGD & FGSM attack on the LeNet5 model.

## Introduction
The targeted PGD attack is a method used to generate adversarial examples that are specifically designed to be misclassified by the LeNet5 model. This attack aims to find the minimum perturbation required to change the predicted class of an input image to a target class.

## Usage
To use this project, follow these steps:

1. Clone the repository:
  ```bash
  git clone https://github.com/d2n0s4ur/targeted-PGD.git
  ```

2. Install the required dependencies:
  ```bash
  pip install -r requirements.txt
  ```

3. Run the attack script with jupyter notebook:
  ```bash
  jupyter notebook code/run.ipynb
  ```

## Results
The results of the targeted PGD attack on the LeNet5 model are shown below:

![Adversarial Example](images/adversarial_example.png)
