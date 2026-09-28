# 🧠 Deep Generative Graph Models

A collection of simplified implementations of the main deep generative graph architectures. Each model is implemented in a separate repository.

The goal is to understand the core ideas behind each architecture through simple, readable, and reproducible code.

## Models

### 1. Autoregressive Models

Generate graphs sequentially, one node or edge at a time.

* **GraphRNN**: Uses recurrent neural networks to generate graphs sequentially.

  * 📄 [Paper](https://arxiv.org/abs/1802.08773)
  * 💻 [Code](REPLACE_WITH_GRAPHRNN_REPOSITORY_URL)

* **GRAN**: Uses recurrent attention to generate graphs in blocks.

  * 📄 [Paper](https://arxiv.org/abs/1910.00760)
  * 💻 [Code](REPLACE_WITH_GRAN_REPOSITORY_URL)

### 2. Variational Graph Autoencoders

Learn a probabilistic latent representation of graphs and generate new graphs from it.

* **VGAE**: Uses a GNN encoder and a probabilistic decoder to model graph structure.

  * 📄 [Paper](https://arxiv.org/abs/1611.07308)
  * 💻 [Code](REPLACE_WITH_VGAE_REPOSITORY_URL)

* **GraphVAE**: Generates entire graphs from latent representations using a probabilistic decoder.

  * 📄 [Paper](https://arxiv.org/abs/1802.03480)
  * 💻 [Code](REPLACE_WITH_GRAPHVAE_REPOSITORY_URL)

### 3. Normalizing Flows

Use invertible transformations to learn complex graph distributions with tractable likelihoods.

* **GraphNVP**: Uses normalizing flows to generate molecular graphs.

  * 📄 [Paper](https://arxiv.org/abs/1905.11600)
  * 💻 [Code](REPLACE_WITH_GRAPHNVP_REPOSITORY_URL)

* **MoFlow**: Uses invertible flows to generate molecular graphs and model their node and edge features.

  * 📄 [Paper](https://arxiv.org/abs/2006.10137)
  * 💻 [Code](REPLACE_WITH_MOFLOW_REPOSITORY_URL)

### 4. Diffusion Models

Generate graphs by progressively denoising noisy graph representations.

* **GDSS**: Uses score-based diffusion to generate graphs.

  * 📄 [Paper](https://arxiv.org/abs/2202.02514)
  * 💻 [Code](REPLACE_WITH_GDSS_REPOSITORY_URL)

* **DiGress**: Uses discrete diffusion to generate graphs with categorical node and edge attributes.

  * 📄 [Paper](https://arxiv.org/abs/2209.14734)
  * 💻 [Code](REPLACE_WITH_DIGRESS_REPOSITORY_URL)

### 5. Generative Adversarial Networks

Use a generator and a discriminator trained adversarially to produce realistic graphs.

* **NetGAN**: Generates graphs through random walks using adversarial training.

  * 📄 [Paper](https://arxiv.org/abs/1803.00816)
  * 💻 [Code](REPLACE_WITH_NETGAN_REPOSITORY_URL)

* **MolGAN**: Uses adversarial training and reinforcement learning to generate molecular graphs.

  * 📄 [Paper](https://arxiv.org/abs/1805.11973)
  * 💻 [Code](REPLACE_WITH_MOLGAN_REPOSITORY_URL)

### 6. Transformer-based Models

Use self-attention to model dependencies between graph components.

* **Graph Transformer**: Uses Transformer architectures for graph generation.

  * 📄 [Reference paper](https://arxiv.org/abs/2106.05234)
  * 💻 [Code](REPLACE_WITH_GRAPH_TRANSFORMER_REPOSITORY_URL)

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

The implementations can be evaluated using the following metrics:

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
