# Quantum Pollard's Rho Algorithm for the Discrete Logarithm Problem

A Python implementation of a quantum-inspired version of **Pollard's Rho algorithm** for solving the **Discrete Logarithm Problem (DLP)** using **Qiskit**. The project demonstrates quantum circuit construction, simulation using IBM Aer, and execution on IBM Quantum backends.

---

## Overview

The Discrete Logarithm Problem (DLP) is a fundamental problem in number theory and modern cryptography. This project explores its solution through a quantum implementation inspired by Pollard's Rho algorithm.

The notebook includes:

- Quantum circuit construction using Qiskit
- IBM Quantum Runtime integration
- IBM Aer simulator execution
- Optional execution on IBM Quantum hardware
- Circuit visualization
- Experimental analysis and performance evaluation

---

## Features

- Quantum implementation of Pollard's Rho algorithm
- IBM Quantum Runtime support
- IBM Aer simulator support
- Quantum circuit visualization
- Experimental result generation
- Educational implementation with detailed code

---

## Technologies Used

- Python 3
- Qiskit
- Qiskit Aer
- IBM Quantum Runtime
- NumPy
- Matplotlib
- pylatexenc

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Silkygupta12/pollard.git
cd pollard
```

Install the required packages:

```bash
pip install qiskit
pip install qiskit-aer
pip install qiskit-ibm-runtime
pip install pylatexenc
pip install matplotlib
pip install numpy
```

---

## IBM Quantum Setup

Create an IBM Quantum account and generate an API key.

Instead of hardcoding the API key, use an environment variable:

```python
import os
from qiskit_ibm_runtime import QiskitRuntimeService

QiskitRuntimeService.save_account(
    channel="ibm_quantum_platform",
    token=os.getenv("QISKIT_IBM_TOKEN"),
    overwrite=True
)
```

**Never upload your API key to GitHub.**

---

## Running the Project

1. Open the notebook in Jupyter Notebook, VS Code, or Google Colab.
2. Install all dependencies.
3. Configure your IBM Quantum API key.
4. Run the notebook cells sequentially.
5. View the generated circuits and experimental results.

---

## Repository Structure

```
pollard/
│
├── quantum pollard rho.ipynb
├── README.md
└── LICENSE (optional)
```

---

## Learning Outcomes

This project demonstrates:

- Quantum computation fundamentals
- Quantum circuit design
- Pollard's Rho algorithm
- IBM Quantum Runtime usage
- Quantum simulation using IBM Aer
- Execution on real quantum hardware

---

## Future Improvements

- Support for larger DLP instances
- Circuit optimization
- Error mitigation techniques
- Performance benchmarking
- Improved visualization
- Modular code structure

---

## References

- Peter W. Shor, *Polynomial-Time Algorithms for Prime Factorization and Discrete Logarithms on a Quantum Computer*
- IBM Quantum Documentation
- Qiskit Documentation
- Pollard, J. M., *Monte Carlo Methods for Index Computation (mod p)*

---

## Author

**Silky Gupta**

B.Tech Student | Quantum Computing Enthusiast

GitHub: https://github.com/Silkygupta12

---

## License

This project is intended for educational and research purposes.
