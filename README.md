# Reproduction of NoProp

> NoProp takes inspiration from diffusion and flow matching methods, where each layer independently learns to denoise a noisy target. We believe this work takes a first step towards introducing a new family of gradient-free learning methods, that does not learn hierarchical representations -- at least not in the usual sense[^1].

It offered a new perspective on the application of denoising deep learning pattern and, by enabling each block to be trained independently and in a distributed manner, provides more possibilities for balancing training speed and memory usage.

To enhance code readability and modularity, this project uses dedicated Git branches for each major component:

- **main**: Overview of this repository.
- [**classify-mnist**](https://github.com/QidiLiu/NoProp_Reproduction/tree/classify-mnist): The most basic reproduction of NoProp.

[^1]: [Li, Q., Teh, Y. W., & Pascanu, R. (2025). NoProp: Training Neural Networks without Back-propagation or Forward-propagation. arXiv preprint arXiv:2503.24322.](https://arxiv.org/abs/2503.24322v1)
