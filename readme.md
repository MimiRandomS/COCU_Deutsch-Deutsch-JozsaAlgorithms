# Deutsch & Deutsch-Jozsa Algorithms

**Geronimo Martinez Nuñez** · COCU — Computación Cuántica · Maestría

---

Quantum circuit design and simulation of the **Deutsch** and **Deutsch-Jozsa** algorithms for a 3-qubit system, including oracle construction, unitary matrix derivation, Python simulation, and execution on **IBM Quantum Composer**.

## Notebook

> **[`AlgorithmsIntro.ipynb`](./AlgorithmsIntro.ipynb)**

Click the notebook to explore the full implementation.

## What's Inside

| Algorithm | Function | Result |
|---|---|---|
| Deutsch | Balanced NOT `f(x) = ¬x` | `\|1⟩` → balanced |
| Deutsch-Jozsa | Constant `f(x) = 1` | `\|000⟩` → constant |
| Deutsch-Jozsa | Balanced `f(x) = x₂` | `\|001⟩` → balanced |
| Deutsch-Jozsa | Balanced `f(x) = x₀` | `\|100⟩` → balanced |

## Structure

```
📁 notebooks/
├── AlgorithmsIntro.ipynb   ← main notebook
└── imgs/                   ← circuit diagrams & IBM results
```

## Requirements

```bash
pip install qiskit matplotlib notebook qiskit-aer pylatexenc
```