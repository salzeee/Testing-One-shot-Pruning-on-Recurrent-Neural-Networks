# Testing One-shot Pruning on Recurrent Neural Networks

This repository presents an investigation into the application of the Lottery Ticket Hypothesis on Recurrent Neural Networks (RNNs). The Lottery Ticket Hypothesis suggests that within a randomly initialized dense neural network, there exist small subnetworks, known as winning tickets, that can be trained in isolation to achieve competitive performance. 

## Introduction

In this project, we aim to test the efficacy of the Lottery Ticket Hypothesis on RNNs and compare the results with its observed effects on Convolutional Neural Networks (CNNs). By applying one-shot pruning techniques to RNNs, we investigate whether a similar phenomenon occurs, where a sparse subnetwork of the original RNN can be trained to achieve comparable performance.

## Repository Structure

- **`datasets/`**: Only the .ipynb file is given. 

## Results and Discussion

The .ipynb file contains the obtained results from the experiments, including accuracy metrics, sparsity levels, and training logs. The findings will be discussed in detail in a separate report (link provided if available).

## Conclusion

This project investigates the application of one-shot pruning, based on the Lottery Ticket Hypothesis, to Recurrent Neural Networks. By testing the hypothesis on RNNs and comparing the results with its effects on CNNs, we aim to gain insights into the generalizability of the Lottery Ticket Hypothesis across different network architectures. The findings will contribute to our understanding of network sparsity and the potential for efficient training and deployment of RNN models.

If you have any questions or feedback, please feel free to reach out. Thank you for your interest in this project!
