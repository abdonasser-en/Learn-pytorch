# Learn-pytorch

This is a beginner course for those who want to rapidly learn PyTorch and progress from a beginner to an intermediate level. So, let's get started :muscle:


![Pytorch logo](images/pytorch.png)

A research deep learning framework developed by Meta, PyTorch is an open-source platform used by big companies such as Tesla and Microsoft. One of the most interesting that PyTorch has the ability to run code accelerated on a GPU. Additionally, PyTorch offers plenty of pre-built learning models hosted on their website( yyou can find TorchHub [here](https://pytorch.org/hub/)).

PyTorch provides a wide range of tools that cater to the machine learning life cycle, including data preprocessing, model development, and model deployment.


## Table of Contents


- [Tensors](#tensors)
- [Reproducibility](#reproducibility)
 
## Tensors

In machine learning, tensors are defined as multi-dimensional arrays of numbers. Tensors can represent scalars, vectors, matrices, and n-dimensional matrices. They provide a way to represent and store data, enabling fast mathematical operations specifically for neural network. For a more detailed understanding of tensors, please visit this [YouTube video](https://www.youtube.com/watch?v=L35fFDpwIM4) presented by Josh Starmer.

![Tensors](images/Tensors-rank.png)

* **Scalars**: Tensors of rank zero.
* **Vectors**: Tensors of rank one.
* **Matrices**: Tensors of rank two.
* **N-dimensional matrices**: Tensors of rank higher than 2. 

## Reproducibility

> "Reproducibility, closely related to replicability and repeatability, is a major principle underpinning the scientific method. For the findings of a study to be reproducible means that results obtained by an experiment or an observational study or in a statistical analysis of a data set should be achieved again with a high degree of reliability when the study is replicated". [wikipedia](https://en.wikipedia.org/wiki/Reproducibility)

In a simpler way, in  deep learnig , we know that our neural network intialize with random numbers to represent data patterns and then apply tensor operations to update and improve numbers. so here we could agree that that randomness is valueable and powerful, but the question is what we have to do if  we wan to do reproduible experiements that we can share with the public or firend ? 

