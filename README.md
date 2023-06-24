# AlphaNAS: Efficient Architecture Discovery for Large Language Models

This repository contains the theoretical framework for AlphaNAS, a method for efficiently discovering high-performing and computationally economical architectures for Large Language Models (LLMs). The framework combines Monte Carlo Tree Search (MCTS) with a surrogate model to explore the vast search space of LLM architectures and make informed decisions based on architecture performance and computational cost estimates.

## Introduction

The AlphaNAS framework addresses the challenge of discovering efficient architectures for large language models, such as those used in natural language processing tasks. By leveraging MCTS and a surrogate model, AlphaNAS enables efficient exploration of the architecture search space. The surrogate model learns from the performance and computational cost of previously explored architectures, providing accurate estimates for guiding the search process.

Please note that this repository focuses on the theoretical aspects of AlphaNAS, and empirical evaluation hasn't been done yet.

## Key Features

- Efficient architecture exploration using Monte Carlo Tree Search (MCTS)
- Surrogate model for accurate estimation of architecture performance and computational cost
- Iterative refinement of the surrogate model with newly explored architectures
- Theoretical framework for efficient architecture discovery in large language models

## Contributing

Contributions to the AlphaNAS framework are welcome. This is currently a theoretical framework, but we would love to start working on an implementation soon. If you are interested in contributing, please contact the project maintainer: [viraat@inferent.io](mailto:viraat@inferent.io)

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions or inquiries, please contact the project maintainer: [viraat@inferent.io](mailto:viraat@inferent.io)

## Citation

If you have used AlphaNAS for LLMs, citations would be appreciated.

`TODO: add citation`
