# Quantum Machine Learning and Optimization Examples

Welcome to the code repository for **"Quantum Machine Learning Thinking and Exploration in Neural Network Models for Quantum Science and Quantum Computing"**. This repository provides hands-on examples from the book, with detailed code implementations of various quantum algorithms used in machine learning and optimization tasks.

## Overview

This repository serves as a companion to the book, offering ready-to-run implementations of key quantum algorithms. It is designed for researchers, students, and professionals who want to explore the intersection of quantum computing and machine learning.

## Project Structure

```plaintext
.
├── Chapter 1: Quantum Mechanics and Data-Driven Physics
├── Chapter 2: Kernelizing
├── Chapter 3: Qubit Maps
├── Chapter 5: Two-Qubit Transverse-Field Ising Model and Entanglement
├── Chapter 6: Variational Algorithms, Quantum Approximate Optimization Algorithm, and Neural Network Quantum States with Two Qubits
├── Chapter 7: Phase Space Representation
├── Chapter 8: States as a Neural Networks and Gates as Pullbacks
├── Chapter 9: Quantum Reservoir Computing
├── Chapter 11: Squeezing, Beam Splitters, and Detection
├── Chapter 12: Uncertainties and Entanglement
├── Chapter 13: Gaussian Boson Sampling
├── Chapter 14: Variational Circuits for Quantum Solitons 
├── Dockerfile
├── requeriments.txt
└── README.md

```
- **Dockerfile**: To set up a consistent development environment using Docker.
- **requeriments**: Requirements need to run the project.
- **README.md**: This document providing an overview of the project.

## Prerequisites

You can install the required Python libraries using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Running the Code

### Option 1: Local Environment

1. Clone the repository:

   ```bash
   git clone https://github.com/matheus-araujo/quantum-machine-learning.git
   cd quantum-machine-learning
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
   

### Option 2: Using Docker

Alternatively, you can run the examples using Docker for a consistent development environment.

1. Build the Docker image:

   ```bash
   docker build -t quantum-machine-learning .
   ```

2. Run the container:

   ```bash
   docker run -it --rm -v $(pwd):/app quantum-machine-learning
   ```

## Project Goals

- **Educational Resource**: To provide hands-on quantum computing examples in quantum computing, machine learning and optimization.
- **Experimentation Platform**: To enable users to explore and modify algorithms as they learn about quantum computing.
- **Community Contributions**: To allow contributions from developers and researchers interested in advancing quantum technologies.

## Contributing

Contributions are welcome! If you’d like to contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

This README file provides a concise project summary, how to get started, and how to contribute. Feel free to adjust the content to fit your project's details!
