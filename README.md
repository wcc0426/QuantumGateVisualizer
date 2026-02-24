# Quantum Gate Visualizer

A Python Jupyter Notebook that demonstrates the effect of quantum gates on a single qubit using IBM's Qiskit library. The program applies 8 different quantum gates to a user-specified initial qubit state and visualizes each gate's effect on the Bloch sphere in real time.

## Purpose

This project serves as a **technical portfolio piece** showcasing my abilities in:
- **Quantum Computing**: Understanding and applying quantum gates, qubits, and statevectors
- **Python Development**: Writing clean, modular code using industry-standard quantum libraries
- **Data Visualization**: Generating Bloch sphere visualizations to represent quantum states
- **Mathematics**: Working with complex numbers, linear algebra, and quantum state representations

## Features

- User-specified initial qubit state (|0⟩ or |1⟩)
- Applies 8 quantum gates: X, Y, Z, H, Phase (π/4), Rx (π/2), Ry (π/2), Rz (π/2)
- Calculates and displays full statevector (a, b) for each gate
- Computes Bloch sphere coordinates (X, Y, Z) for each quantum state
- Generates a 3D Bloch sphere visualization for every gate applied

## Technologies Used

- **Python 3** - Core language
- **Qiskit** - IBM's quantum computing framework
- **Matplotlib** - Visualization
- **NumPy** - Mathematical operations
- **Jupyter Notebook** - Interactive development environment
- **Git** - Version control

## Getting Started

### Prerequisites
- Python 3 installed on your system
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository
```bash
git clone https://github.com/wcc0426/QuantumGateVisualizer.git
cd QuantumGateVisualizer
```

2. Install dependencies
```bash
pip install qiskit qiskit-aer matplotlib numpy jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook chisholmFinalProj.ipynb
```

4. Run all cells and enter your initial qubit state when prompted (0 or 1)

## How It Works

The notebook creates a single-qubit quantum circuit for each gate, prepares the initial state, applies the gate, and extracts the resulting statevector. The Bloch sphere coordinates are calculated from the complex amplitudes:

- **X** = 2 · Re(a* · b)
- **Y** = 2 · Im(a* · b)  
- **Z** = |a|² - |b|²

Each gate is then visualized on a 3D Bloch sphere showing how the qubit state was transformed.

## Quantum Gates Covered

| Gate | Description |
|------|-------------|
| X | Quantum NOT gate — flips \|0⟩ to \|1⟩ |
| Y | Pauli-Y rotation |
| Z | Phase flip gate |
| H | Hadamard gate — creates superposition |
| Phase (π/4) | Rotates phase by π/4 |
| Rx (π/2) | Rotation around X-axis by π/2 |
| Ry (π/2) | Rotation around Y-axis by π/2 |
| Rz (π/2) | Rotation around Z-axis by π/2 |

## Skills Demonstrated

- **Quantum Computing**: Practical application of quantum gates and qubit state manipulation
- **Python Scripting**: Modular function design and library integration
- **Mathematical Thinking**: Working with complex amplitudes and 3D coordinate transformations
- **Data Visualization**: Generating meaningful visual representations of quantum states
- **Version Control**: Git workflow and repository management

## Contact

William Chisholm
- LinkedIn: https://www.linkedin.com/in/william-chisholm-msu/
- Email: liamchisholm0426@gmail.com

## License

This project is open source and available under the [MIT License](LICENSE).

---

*This project was created as a demonstration of software engineering skills for potential employers.*
