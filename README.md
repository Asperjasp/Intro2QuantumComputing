# Intro2QuantumComputing
Welcome to Introduction to Quantum Computing! This repository contains materials and resources for learning the fundamentals of quantum computing, based on authoritative texts and resources in the field.

## Overview
This course covers the basic concepts of quantum computing, including:
- Quantum bits (qubits) and quantum states
- Quantum gates and circuits
- Quantum algorithms
- Quantum entanglement and superposition
- Practical applications of quantum computing

## Prerequisites
- Basic understanding of linear algebra
- Familiarity with complex numbers
- Basic programming knowledge (Python recommended)
- Understanding of classical computing concepts

## Course Structure
- **Module 1**: Introduction to Quantum Mechanics
- **Module 2**: Quantum Computing Basics
- **Module 3**: Quantum Gates and Circuits
- **Module 4**: Basic Quantum Algorithms
- **Module 5**: Quantum Programming with Qiskit

## Getting Started
1. Clone this repository
2. Install required dependencies (see `requirements.txt`)
3. Follow the tutorials in order
4. Complete the exercises in each section

## Resources
- [Qiskit Documentation](https://qiskit.org/documentation/)
- [IBM Quantum Experience](https://quantum-computing.ibm.com/)
- [Quantum Computing Playground](http://www.quantumplayground.net/)
- [Linux Foundation Quantum computing course](https://training.linuxfoundation.org/training/fundamentals-of-quantum-computing-lfq101)
- [IBM Quantum technology](https://www.ibm.com/quantum/technology)

## Bibliography
### Core Textbooks
1. Nielsen, M. A., & Chuang, I. L. (2010). Quantum Computation and Quantum Information: 10th Anniversary Edition. Cambridge University Press.
2. Yanofsky, N. S., & Mannucci, M. A. (2013). Quantum Computing for Computer Scientists. Cambridge University Press.
3. Mermin, N. D. (2007). Quantum Computer Science: An Introduction. Cambridge University Press.

### Research Papers
1. Shor, P. W. (1997). Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer. SIAM Journal on Computing, 26(5), 1484-1509.
2. Grover, L. K. (1996). A Fast Quantum Mechanical Algorithm for Database Search. Proceedings of the 28th Annual ACM Symposium on Theory of Computing, 212-219.

### Online Resources
1. Preskill, J. (2018). Quantum Computing in the NISQ era and beyond. Quantum, 2, 79.
2. Quantum Computing Report - [https://quantumcomputingreport.com/](https://quantumcomputingreport.com/)
3. Qiskit Textbook - [https://qiskit.org/textbook/](https://qiskit.org/textbook/)
4. Qiskit Youtube Channel [ibm.com/quantum/qiskit](ibm.com/quantum/qiskit)

## Contributing
Feel free to contribute to this repository by:
- Reporting issues
- Suggesting improvements
- Submitting pull requests

## Important Note on Qiskit Version and Course Materials

This course is designed and tested using **Qiskit version 2.0.0 or later** (specifically, the `qiskit` metapackage).

**Why this matters:**
*   **Rapid Evolution:** Quantum computing is a rapidly advancing field, and software frameworks like Qiskit evolve quickly to incorporate new research, hardware capabilities, and improved programming interfaces.
*   **Version 1.0 and 2.0 Milestones:** Qiskit reached a significant `1.0.0` metapackage release in early 2024, which stabilized many APIs and introduced the `qiskit-ibm-provider` for interacting with IBM Quantum hardware. Qiskit `2.0.0` followed, introducing some breaking changes aimed at long-term improvements and consistency (as detailed in its official migration guides), though many fundamental operations for beginners remain similar.
*   **Course Compatibility:** The code examples, exercises, and explanations in this course are tailored to the syntax and behavior of Qiskit 2.0.0+. While many concepts are transferable, using significantly older versions (e.g., Qiskit 0.x) or even some Qiskit 1.x versions might lead to:
    *   Different function names or arguments.
    *   Unavailable features.
    *   Errors when running the provided code.

**Our Approach:**
*   We aim to use the modern, stable Qiskit 2.0.0+ features to provide you with current best practices.
*   A `requirements.txt` file is provided with this course. **It is highly recommended to set up a Python virtual environment and install the packages listed in `requirements.txt`** to ensure you have a compatible environment. This file specifies `qiskit>=2.0.0`.

**If you are using a different version of Qiskit:**
*   You might need to consult the official Qiskit documentation for your specific version to adapt the code.
*   For major version differences (e.g., trying to run this course's code with Qiskit 0.x), significant modifications would likely be required.

**Focus on Concepts:**
While we use Qiskit as our tool, the primary goal of this course is to teach you the **fundamental concepts of quantum computing**. These concepts (qubits, superposition, entanglement, gates, measurement) are universal. Learning them with Qiskit 2.0.0+ will provide you with a solid and up-to-date practical foundation.


