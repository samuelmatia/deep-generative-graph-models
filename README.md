# 🧠 Deep Generative Graph Models

<p align="center">
  <img src="https://img.shields.io/badge/Status-Ongoing-orange?style=flat-square" alt="Ongoing">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Graph%20Generation-6A5ACD?style=flat-square" alt="Graph Generation">
  <img src="https://img.shields.io/badge/license-MIT-2ea44f?style=flat-square" alt="MIT License">
</p>


A collection of simplified implementations of the main deep generative graph architectures. Each model is implemented in a separate repository.

The goal is to understand the core ideas behind each architecture through simple, readable, and reproducible code.

## Models

### 1. Autoregressive Models

Generate graphs sequentially, one node or edge at a time.

* **GraphRNN**: Uses recurrent neural networks to generate graphs sequentially.

  * <a href="https://arxiv.org/abs/1802.08773"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="https://github.com/samuelmatia/graph-rnn"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

* **GRAN**: Uses recurrent attention to generate graphs in blocks.

  * <a href="https://arxiv.org/abs/1910.00760"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_GRAN_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

### 2. Variational Graph Autoencoders

Learn a probabilistic latent representation of graphs and generate new graphs from it.

* **VGAE**: Uses a GNN encoder and a probabilistic decoder to model graph structure.

  * <a href="https://arxiv.org/abs/1611.07308"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_VGAE_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

* **GraphVAE**: Generates entire graphs from latent representations using a probabilistic decoder.

  * <a href="https://arxiv.org/abs/1802.03480"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_GRAPHVAE_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

### 3. Normalizing Flows

Use invertible transformations to learn complex graph distributions with tractable likelihoods.

* **GraphNVP**: Uses normalizing flows to generate molecular graphs.

  * <a href="https://arxiv.org/abs/1905.11600"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_GRAPHNVP_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

* **MoFlow**: Uses invertible flows to generate molecular graphs and model their node and edge features.

  * <a href="https://arxiv.org/abs/2006.10137"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_MOFLOW_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

### 4. Diffusion Models

Generate graphs by progressively denoising noisy graph representations.

* **GDSS**: Uses score-based diffusion to generate graphs.

  * <a href="https://arxiv.org/abs/2202.02514"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_GDSS_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

* **DiGress**: Uses discrete diffusion to generate graphs with categorical node and edge attributes.

  * <a href="https://arxiv.org/abs/2209.14734"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_DIGRESS_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

### 5. Generative Adversarial Networks

Use a generator and a discriminator trained adversarially to produce realistic graphs.

* **NetGAN**: Generates graphs through random walks using adversarial training.

  * <a href="https://arxiv.org/abs/1803.00816"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_NETGAN_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

* **MolGAN**: Uses adversarial training and reinforcement learning to generate molecular graphs.

  * <a href="https://arxiv.org/abs/1805.11973"><img src="https://img.shields.io/badge/Paper-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_MOLGAN_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

### 6. Transformer-based Models

Use self-attention to model dependencies between graph components.

* **Graph Transformer**: Uses Transformer architectures for graph generation.

  * <a href="https://arxiv.org/abs/2106.05234"><img src="https://img.shields.io/badge/Reference-PDF-002147?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Paper"></a>
  * <a href="REPLACE_WITH_GRAPH_TRANSFORMER_REPOSITORY_URL"><img src="https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository"></a>

## Comparison

| Architecture      | Main idea                       | Generation           |
| ----------------- | ------------------------------- | -------------------- |
| Autoregressive    | Sequential probability modeling | Step by step         |
| VAE               | Probabilistic latent space      | Latent decoding      |
| Normalizing Flows | Invertible transformations      | Direct sampling      |
| Diffusion         | Iterative denoising             | Multiple steps       |
| GAN               | Adversarial learning            | Generator sampling   |
| Transformer       | Self-attention                  | Depends on the model |

## Evaluation

* **Degree distribution:** Compares node degree distributions.
* **Clustering coefficient:** Measures local connectivity.
* **MMD:** Compares graph statistics between real and generated graphs.
* **Validity:** Measures the proportion of valid generated graphs.
* **Uniqueness:** Measures the proportion of distinct generated graphs.
* **Novelty:** Measures the proportion of generated graphs not present in the training set.

The evaluation metrics depend on the dataset and the type of graph being generated.

## Goals

* Understand the main deep generative graph architectures.
* Provide simple and readable implementations.
* Reproduce the core ideas of the original papers.
* Compare different approaches using common evaluation metrics.
* Facilitate experimentation and further research.

## Contributing

Contributions are welcome, including new implementations, documentation, experiments, and evaluation methods.

## License

See the individual repositories for their respective licenses.
