# QuantumErrorCorrection
Uses Qiskit to create a function that takes two inputs: a pair of booleans $x$, and an error probability $p$, and outputs a quantum circuit that prepares the logical state $\ket{x_L}$ for the $5$ qubit error correction code, runs it through a random Pauli error channel with error rate $p$, measures syndromes, applies recovery operations, and then measures the data qubits to assure that the recovery operations were correctly applied.

