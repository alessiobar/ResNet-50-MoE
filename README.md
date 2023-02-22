# ResNet-50-MoE 

This repository contains the code for the second homework of the *Neural Networks for Data Science Applications* course (10589627), Sapienza University.

**TL;DR** The task consisted of choosing a dataset (freely), building a neural network of choice, and adding a 'Mixture-of-Experts' layer. Everything using *TensorFlow*.

## Data

The dataset chosen for this homework is the Flowers dataset, it can be found on the catalog of TensorFlow Datasets, specifically on the section of image classification (at https://www.tensorflow.org/datasets/catalog/tf_flowers).

## Neural Network Model

The model chosen is a *ResNet-50*, it's implemented from scratch and it is trained for just a few epochs (i.e., 50) to avoid exceeding *Colab* usage limits.

## MoE Layer 

"This is by far the most interesting part: the approach took inspiration from both 'Deep Neural Networks with Mixture of Experts Layers for Complex Event Recognition from Images' (Li et al., 2018) for the use of a MoE layer within a ResNet model, and, most importantly, 'Outrageously Large Neural Networks: The Sparsely-Gated Mixture-Of-Experts Layer' (Shazeer et al., 2017) for the actual implementation."

## Results 
Everything is explained in the notebook `asdasdasdasasdas.pdf`

## (Few) References
- Shazeer, N., Mirhoseini, A., Maziarz, K., Davis, A., Le, Q., Hinton, G., & Dean, J. (2017). *Outrageously large neural networks: The sparsely-gated mixture-of-experts layer*. arXiv preprint arXiv:1701.06538.
- Li, M., & Kamata, S. I. (2018, June). *Deep neural networks with mixture of experts layers for complex event recognition from images*. In 2018 Joint 7th International Conference on Informatics, Electronics & Vision (ICIEV) and 2018 2nd International Conference on Imaging, Vision & Pattern Recognition (icIVPR) (pp. 410-415). IEEE.
