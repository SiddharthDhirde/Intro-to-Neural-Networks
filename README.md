# Intro-to-Neural-Networks with Micrograd

Welcome to Intro to Neural Networks with Micrograd! This project provides a comprehensive guide to understanding and implementing neural networks from scratch using Micrograd, a lightweight automatic differentiation library developed by Andrej Karpathy.

## Overview

This project is designed to walk you through the process of building a simple neural network step by step using Micrograd. We start with the basics, explaining derivatives, partial differentiation, and building a foundational data structure for neural networks called the Value class. From there, we progress to creating a Neuron class, Layer class, and finally, a Multi-Layer Perceptron (MLP) class.

Each step of the implementation is explained in detail within Jupyter notebooks, accompanied by Markdown cells providing explanations of the topics covered and the corresponding code. By following along in the notebooks, you'll gain a deep understanding of how neural networks work and how they can be implemented using Micrograd.

## Micrograd

Micrograd is a tiny autograd engine developed by Andrej Karpathy. It implements reverse-mode autodiff over a dynamically built Directed Acyclic Graph (DAG), allowing for efficient computation of gradients. Despite its small size (about 100 lines of code), Micrograd is powerful enough to build entire deep neural networks. You can find the original Micrograd project [here](https://github.com/karpathy/micrograd).

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `Making of Micrograd/` directory and open the Jupyter notebooks.
3. Follow the instructions provided in the notebooks to implement the neural network step by step.
4. Experiment with different configurations and datasets to deepen your understanding and explore new concepts.

## Requirements

Ensure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- NumPy

## Contributing

Contributions to this project are welcome! If you find any issues, have suggestions for improvements, or want to add new features, please follow these guidelines:

1. **Issues**: Before starting work on a new feature or bug fix, please check the [issue tracker](https://github.com/SiddharthDhirde/Intro-to-Neural-Networks/issues) to see if the topic has already been discussed. If not, feel free to open a new issue to discuss your proposal or report a bug.

2. **Pull Requests**: If you'd like to contribute code to the project, please fork the repository and submit a pull request with your changes. Make sure to include a detailed description of the changes and any relevant context. We'll review your pull request as soon as possible and provide feedback if needed.

3. **Coding Standards**: Please follow the coding style and conventions used in the existing codebase. This ensures consistency and makes it easier for others to understand and maintain the code.

4. **Testing**: If you're adding new functionality, please include tests to ensure that your code works correctly and doesn't introduce regressions. Run the existing tests before submitting your pull request to make sure you haven't broken anything.

5. **Documentation**: If you're adding new features or making significant changes, please update the documentation to reflect the changes. Clear and concise documentation helps other users understand how to use the new features and contributes to the overall usability of the project.

Thank you for considering contributing to this project! Together, we can make it even better.


## Acknowledgments

This project is inspired by Micrograd, a lightweight automatic differentiation library developed by Andrej Karpathy. We extend our sincere gratitude to Andrej Karpathy for his contributions to the field of deep learning and for making tools like Micrograd accessible to the community.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your educational and personal projects.
