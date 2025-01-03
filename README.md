Quantum Computation in Python

Overview

This repository contains Python implementations of foundational quantum computation concepts and algorithms. The project is inspired by the principles outlined in A Quantum Computation Workbook. It includes tools for visualizing quantum states and simulating key algorithms.

Features

Quantum State Representation: Functions to create and manipulate qubits.

Basic Gates: Implementation of fundamental quantum gates such as Hadamard and Pauli-X.

Multi-Qubit Systems: Tensor product and controlled gates like CNOT.

Quantum Algorithms: Implementations of Deutsch-Jozsa, Grover, Simon, and Quantum Teleportation.

Visualization: Interactive visualizations of quantum states using the Bloch Sphere.

Visualizations

We use the Bloch Sphere to represent single-qubit states, providing an intuitive understanding of quantum mechanics. Below is an example visualization:



Requirements

Python 3.8+

NumPy

Matplotlib

Installation

pip install -r requirements.txt

Usage

Run the Python scripts to explore quantum states and algorithms. For example, to visualize the Bloch Sphere:

python bloch_sphere_visualization.py

Example Algorithms

Deutsch-Jozsa Algorithm: Determines if a function is constant or balanced.

Grover's Algorithm: Searches an unsorted database exponentially faster than classical methods.

Simon's Algorithm: Identifies the period of a function.

Quantum Teleportation: Demonstrates transferring quantum states across entangled qubits.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

License

This project is licensed under the MIT License.

Acknowledgments

Special thanks to the authors of A Quantum Computation Workbook for providing the inspiration and foundation for this project.
