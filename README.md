# Quantum Kernel Training with Qiskit

This project implements a **Quantum Kernel Learning** algorithm using Qiskit. It includes data preprocessing, quantum circuit construction, and fidelity calculation using IBM Quantum hardware or simulators.

## **Features**
- Reads and processes training data from a CSV file.
- Constructs a quantum feature map and overlap circuits.
- Evaluates kernel matrix elements using Qiskit’s **UnitaryOverlap** circuit.
- Uses **IBM Quantum** hardware for quantum state sampling.
- Visualizes results with **Matplotlib** and **Plotly**.

## **Installation**
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
## Quantum Kernel Overlap Plot
- The encoding of classical data into quantum states.
- The entanglement pattern applied between qubits.
- The measurement operations that extract the final probabilities.
- ![Image Alt](https://github.com/Tayyab5733/Quantum-Kernel-Training/blob/f422e2f52a5ff9531edd93170d5dd8beca1d0541/first.png)
## Optimized Quantum Circuit Plot on IBM Quantum Backend
- The transpiled quantum circuit optimized for execution on real quantum hardware.
- Gate rearrangements and optimizations performed by Qiskit's preset pass manager.
- The elimination of idle qubits (`idle_wires=False`), making the circuit more efficient.
- The final structure of the circuit, showing how it will be executed on the IBM Quantum device.
- ![Image Alt](https://github.com/Tayyab5733/Quantum-Kernel-Training/blob/5b45f2aef148fcaebe8605f572de45af1a1c9c13/second.png)
## Quantum State Overlap Measurement
The plot visualizes:
- The probability distribution of measurement outcomes after executing the quantum circuit.
- The frequency of each possible quantum state based on `num_shots = 10,000`.
- The impact of quantum noise when executed on real hardware.
- ![Image Alt](https://github.com/Tayyab5733/Quantum-Kernel-Training/blob/5b45f2aef148fcaebe8605f572de45af1a1c9c13/third.png)
## Scatter Plot of Fidelity Between Training Samples
The plot visualizes:
- The relationship between different training samples based on their fidelity values.
- A color gradient (`Viridis` scale) to indicate the strength of fidelity between pairs.
- Data points where each `(x, y)` pair represents two training samples, with color intensity reflecting their fidelity.
- ![Image Alt](https://github.com/Tayyab5733/Quantum-Kernel-Training/blob/5b45f2aef148fcaebe8605f572de45af1a1c9c13/fourth.png)

 
 Wanna do this visual insight by yourself ? Get your own token form [IBM Quantum Learning](https://learning.quantum.ibm.com/)
