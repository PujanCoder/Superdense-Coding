# Quantum Superdense Coding 🚀

This project demonstrates **Quantum Superdense Coding** using Qiskit, a protocol in quantum communication that allows **sending 2 classical bits using only 1 qubit**, leveraging quantum entanglement.

---

## 🔹 Overview

Superdense Coding is a foundational quantum communication protocol:

1. **Entanglement**: Alice and Bob share a Bell pair (entangled qubits).  
2. **Encoding**: Alice encodes **2 classical bits** (00, 01, 10, 11) on her qubit using quantum gates.  
3. **Transmission**: Alice sends her qubit to Bob.  
4. **Decoding**: Bob applies a decoding circuit (CNOT + Hadamard) and measures both qubits to retrieve the original 2 bits.

This demonstrates the power of quantum entanglement to **transmit more information than classical limits allow**.

---

## 🔹 Features

- Create a Bell pair between two qubits
- Encode 2 classical bits using Alice's qubit
- Decode the message using Bob's qubit
- Visualize results with probability distribution plots
- Fully simulated using Qiskit AerSimulator

---

## 🔹 Prerequisites

- Python >= 3.8  
- [Qiskit](https://qiskit.org/) installed
```bash
pip install qiskit
