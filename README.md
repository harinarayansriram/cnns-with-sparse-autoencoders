## Goals
The goal of this research is to better understand the workings of Convolutional Neural Networks (CNNs), especially with regards to adversarial inputs, using Sparse Autoencoders (SAEs), a popular tool in Mechanistic Interpretability. SAEs are generally applied for the study of LLMs and there is very little literature on interpreting CNNs, so we aim to find and interpret features in models for small datasets (e.g. MNIST handwritten digits) and then upscale to larger CNNs for datasets such as tiny-imagenet.

## Progress
We have successfully trained an SAE on a CNN for the MNIST dataset and have found some potential features that pertain to adversarial pertubations. We are working on interpreting these features and perhaps performing feature steering. After this is complete, we will be working on acquiring the computational resources to upscale to train SAEs for CNNs on larger datasets.

## Paper
We hope to get our results on the arXiv but for now, we have the [following draft](https://docs.google.com/document/d/1TpyeaokZGJ0v6DpLVq6X0TLQBTnzmT8ptIDgWLMaN-E/edit?usp=sharing).