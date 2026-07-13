# Deep Learning

This repo contains a checklist of deep learning components implemented from first principles. These notebooks help you understand the actual components and how they come together to form state-of-the-art models. Detailed analysis with a hint of mechanistic interpretability is provided along with the code.

> For a better experience with notebooks, it is recommended to view the repository at
> https://nbviewer.org/github/nveshaan/deep_learning/tree/main/

## Architectures

**Core**
- [x] Neural Network
- [ ] Weights Initialization
- [ ] Activations
- [ ] Normalization
- [ ] Loss Functions
- [ ] Optimizers
- [ ] Residual Connections
- [ ] Regularization

**Inductive Bias**
- [ ] CNN: Convolutional Neural Network
- [ ] RNN: Recurrent Neural Network
- [ ] GRU: Gated Recurrent Unit
- [ ] LSTM: Long Short-Term Memory
- [ ] SSM: State Space Model
- [ ] GNN: Graph Neural Network

**Attention**
- [ ] Attention Mechanisms
- [ ] Positional Encodings
- [ ] Transformer

**Modulation**
- [ ] Normalization
    - [ ] CBN: Conditional Batch Norm
    - [ ] FiLM: Feature-wise Linear Modulation
    - [ ] adaLN: Adaptive Layer Normalization
    - [ ] AdaIN: Adaptive Instance Normalization
- [ ] Hypernetworks
- [ ] Gating Mechanisms

## Model Paradigms

**Discriminative** 

*Implemented in architectures*

**Generative**
- [ ] GPT: Generative Pre-trained Transformer
- [ ] VAE: Variational Autoencoder
- [ ] GAN: Generative Adversarial Network
- [ ] Diffusion
- [ ] Flow Matching

**Joint Embedding**
- [ ] Deep Metric Learning
- [ ] Self-Distillation
- [ ] Canonical Correlation Analysis

## Training

**Strategies**
- [ ] Knowledge Distillation
- [ ] Domain Adaptation
- [ ] Transfer Learning

**Hacks**
- [ ] Reparameterization Trick
- [ ] Gumbel-Softmax
- [ ] Log-Derivative Trick
- [ ] Straight-Through Estimator (STE)
- [ ] Gradient Reversal Layer (GRL)
- [ ] Stop-Gradient (sg)
- [ ] Momentum Updates

<!--
core - math of nn, equivariance, andrej karpathy, colah
inductive - goodfellow, geometry, mit, rnn blog
attention - andrej's stanford video and blog
generative - andrej's mingpt, mit, flowmatching, cs 182, deep unsupervised learning, murphy
joint - ssl -->
