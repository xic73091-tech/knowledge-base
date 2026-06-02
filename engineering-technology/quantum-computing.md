---
domain: engineering-technology
subdomain: quantum-computing
title: "Quantum Computing"
description: "Computing technology based on quantum mechanical phenomena for processing information"
created: 2026-06-02
updated: 2026-06-02
tags: [quantum, computing, qubits, superposition, entanglement, algorithms, cryptography]
prerequisites: [natural-sciences/physics, natural-sciences/mathematics, engineering-technology/computer-science]
related: [natural-sciences/physics, natural-sciences/mathematics, engineering-technology/computer-science]
difficulty: advanced
completeness: comprehensive
---

# Quantum Computing

## Overview

Quantum computing is a type of computation that harnesses quantum mechanical phenomena such as superposition, entanglement, and interference to process information in fundamentally new ways. Unlike classical computers that use bits representing 0 or 1, quantum computers use quantum bits (qubits) that can exist in superposition of both states simultaneously. This enables quantum computers to solve certain problems exponentially faster than classical computers, with potential applications in cryptography, drug discovery, optimization, machine learning, and scientific simulation.

## Core Concepts

### Quantum Mechanics Fundamentals
- **Wave-Particle Duality**: Matter exhibits both wave and particle properties; de Broglie wavelength
- **Quantum Superposition**: Physical states existing simultaneously; linear combination
- **Quantum Entanglement**: Correlated quantum states; non-classical correlations; EPR paradox
- **Quantum Measurement**: Wave function collapse; observable operators; eigenvalues
- **Quantum Interference**: Probability amplitudes adding/subtracting; phase matters
- **Uncertainty Principle**: Heisenberg; fundamental limits to precision measurements
- **No-Cloning Theorem**: Impossible to copy arbitrary unknown quantum state

### Qubits & Physical Implementations
- **What is a Qubit**: Quantum bit; two-level quantum system; basis states |0⟩ and |1⟩
- **Bloch Sphere Representation**: Visualizing qubit states; angles; phases
- **Superconducting Qubits**: Transmon; flux; charge qubits; Josephson junctions
- **Trapped Ion Qubits**: Individual atoms; laser cooling; high fidelity
- **Photonic Qubits**: Light particles; polarization; path encoding; room temperature
- **Topological Qubits**: Anyons; braiding; error protection; Microsoft's approach
- **Spin Qubits**: Electron spin; silicon-based; semiconductor technology
- **Neutral Atoms**: Rydberg atoms; optical traps; scalability potential

### Quantum Gates & Circuits
- **Single-Qubit Gates**: Pauli gates (X,Y,Z); Hadamard; Phase; Rotation gates
- **Two-Qubit Gates**: CNOT; CZ; SWAP; entangling gates; controlled operations
- **Multi-Qubit Gates**: Toffoli (CCNOT); Fredkin; universal gate sets
- **Quantum Circuit Model**: Gates on wires; sequential and parallel operations
- **Universal Quantum Computing**: Any unitary operation can be decomposed
- **Gate Decomposition**: Breaking gates into elementary gate sequences
- **Gate Fidelity**: Error rates; decoherence; control precision

### Quantum Algorithms
- **Shor's Algorithm**: Integer factorization; exponential speedup; RSA implications
- **Grover's Algorithm**: Unstructured search; quadratic speedup; oracles
- **Quantum Fourier Transform (QFT)**: Fourier transform in quantum; period finding
- **Variational Quantum Eigensolver (VQE)**: Hybrid classical-quantum; chemistry
- **Quantum Approximate Optimization Algorithm (QAOA)**: Combinatorial optimization
- **Quantum Phase Estimation**: Eigenvalue estimation; precision; applications
- **Deutsch-Jozsa Algorithm**: One query vs exponential classical queries
- **Quantum Walks**: Sampling; search; algorithms based on quantum walks

### Quantum Complexity Theory
- **BQP (Bounded-error Quantum Polynomial Time)**: Problems solvable on quantum computer
- **Relationship to Classical Complexity**: BPP; NP; P; quantum advantages
- **Quantum Supremacy**: Demonstrating quantum advantage; random circuit sampling
- **Quantum Advantage**: Practical advantages; near-term vs fault-tolerant
- **Quantum-Classical Hybrid**: Best use of both; what quantum does well
- **Limitations**: Not all problems have quantum speedup; no speedup for NP-complete
- **Post-Quantum Complexity**: New complexity classes; certification

### Quantum Error Correction
- **Why Error Correction**: Decoherence; noise; gate errors; fragile quantum states
- **Bit-Flip & Phase-Flip Errors**: Types of quantum errors; correction codes
- **Shor Code**: First quantum error-correcting code; 9 qubits; correcting errors
- **Surface Code**: Topological; high threshold; 2D grid; most promising
- **Logical vs Physical Qubits**: Overhead; error thresholds; fault tolerance
- **Threshold Theorem**: Error rates below threshold enable arbitrary computation
- **Error Mitigation**: NISQ-era techniques; zero-noise extrapolation; probabilistic error cancellation

### Quantum Hardware & Systems
- **Dilution Refrigerators**: Ultra-cold temperatures; 15 mK; superconducting
- **Vacuum Systems**: Ultra-high vacuum; ion trapping; contamination control
- **Control Electronics**: Waveform generators; arbitrary waveform generators
- **Laser Systems**: Trapped ions; precise wavelengths; stabilization
- **Cryogenic Systems**: Different cooling stages; thermal management
- **Qubit Readout**: Dispersive readout; amplifiers; fidelity; speed
- **Scaling Challenges**: Wiring complexity; crosstalk; manufacturing; control

### Quantum Software & Programming
- **Quantum Programming Languages**: Qiskit; Cirq; QuTiP; PennyLane; Braket
- **Quantum SDKs**: Development kits; simulators; runtime interfaces
- **Quantum Simulators**: Classical simulation; limited qubit counts; debugging
- **High-Level Languages**: Rigetti; Xanadu; Silq (ETH Zurich)
- **Quantum Assembly**: OpenQASM; intermediate representations; compilation
- **Compiler Optimization**: Gate reduction; transpilation; optimization passes
- **Testing & Verification**: Assertion; debugging; noise models

### Quantum Cryptography
- **Quantum Key Distribution (QKD)**: BB84; E91; secure key exchange; no-cloning
- **BB84 Protocol**: Polarization states; eavesdropping detection; Bennett & Brassard
- **E91 Protocol**: Entanglement-based QKD; Ekert protocol
- **Quantum Random Number Generation**: True randomness; certification; QRNG
- **Post-Quantum Cryptography**: Lattice-based; code-based; hash signatures
- **NIST Post-Quantum Standards**: CRYSTALS; Dilithium; Kyber; FrodoKEM
- **Cryptographic Transition**: Timeline; challenges; "harvest now, decrypt later"

### Applications of Quantum Computing
- **Drug Discovery & Chemistry**: Molecular simulation; reaction prediction; protein folding
- **Materials Science**: New materials; batteries; catalysts; superconductor design
- **Optimization Problems**: Routing; scheduling; portfolio optimization; logistics
- **Machine Learning & AI**: Quantum ML algorithms; speedups; quantum neural networks
- **Financial Modeling**: Risk analysis; portfolio optimization; derivatives pricing
- **Climate Modeling**: Simulation; carbon capture materials; prediction
- **Cryptography & Security**: Breaking RSA; secure communication; blockchain
- **Search & Database**: Quantum search; Grover's algorithm; unstructured data

### Quantum Communication & Networking
- **Quantum Repeaters**: Extending range; entanglement distribution; memory
- **Quantum Teleportation**: State transfer; no physical transfer; entanglement
- **Quantum Internet**: Network of quantum devices; secure communication
- **Satellite Quantum Communication**: Micius satellite; long-distance QKD
- **Memory & Storage**: Quantum memories; photon storage; synchronization
- **Quantum Sensors**: Measurement precision; gravitational wave detection
- **Distributed Quantum Computing**: Networked quantum processors; collaboration

### Quantum Machine Learning
- **Quantum Support Vector Machines**: Kernel estimation; classification
- **Quantum Neural Networks**: Variational circuits; parameterized quantum circuits
- **Quantum Clustering**: k-means; quantum distance; speedup potential
- **Quantum Principal Component Analysis**: Exponential speedup claim; debate
- **Quantum Sampling**: Boson sampling; Gaussian boson sampling; supremacy
- **Hybrid Classical-Quantum**: VQE; quantum approximate optimization
- **Quantum Kernels**: Computing kernel matrices; feature space

### Current State & Industry
- **IBM Quantum**: Eagle; Osprey; roadmap; cloud access; Qiskit
- **Google Quantum AI**: Sycamore; supremacy claim; research direction
- **Microsoft Quantum**: Azure Quantum; topological qubits; Q#
- **Rigetti**: Aspen; cloud access; hybrid quantum-classical
- **IonQ**: Trapped ion; cloud partnerships; performance claims
- **Xanadu**: Photonic; Borealis; Strawberry Fields; cloud
- **D-Wave**: Quantum annealing; optimization focus; commercial applications
- **AWS Braket**: Multi-provider platform; simulation; hybrid

### Challenges & Limitations
- **Decoherence**: Qubit isolation; environmental interference; error sources
- **Scalability**: Many qubits; connectivity; control complexity
- **Error Rates**: Current error rates; fault-tolerant threshold (~1%)
- **Temperature Requirements**: Millikelvin temperatures; cooling costs
- **Manufacturing Consistency**: Qubit variability; yield; calibration
- **Classical Overhead**: Control systems; read-out; compilation; integration
- **Algorithm Development**: Finding more practical quantum advantages

### Quantum Information Theory
- **Quantum Information**: Qubits vs bits; information content; entropy
- **Von Neumann Entropy**: Quantum entropy measure; entanglement entropy
- **Quantum Channel Capacity**: Information transmission limits; noisy channels
- **Entanglement Theory**: Pure vs mixed states; distillation; monogamy
- **Quantum Data Compression**: Schumacher compression; quantum information theory
- **Decoherence & Entanglement**: Environment as witness; information loss
- **Quantum State Tomography**: Reconstructing quantum states; measurement overhead

### Measurement & Control
- **Quantum Measurement Theory**: POVMs; projective measurement; statistics
- **Weak Measurement**: Minimal disturbance; extracting information gradually
- **Measurement Feedback**: Real-time control; adaptive algorithms; correction
- **Control Theory**: Hamiltonian engineering; pulse shaping; optimization
- **Cryogenic Control Electronics**: Room temperature vs cold electronics
- **Readout Fidelity**: High-fidelity measurement; error sources; speed
- **Calibration**: Regular recalibration; drift compensation; automated

### Future Directions
- **Fault-Tolerant Quantum Computing**: Logical qubits; error correction overhead
- **Quantum Simulation**: Beyond classical; many-body physics; chemistry
- **Quantum Advantage**: Practical problems; industry applications; timeline
- **Quantum Internet**: Global network; secure communication; distributed QC
- **Quantum AI**: ML acceleration; new algorithms; transformative potential
- **Quantum Sensing**: Beyond computing; metrology; imaging; fundamental science
- **Photonic Quantum Computing**: Room temperature; scalability; different approach

### Ethics & Security Implications
- **Cryptographic Risk**: "Harvest now, decrypt later"; long-term data security
- **Dual-Use Technology**: Military applications; surveillance; responsible development
- **Quantum Divides**: Access inequality; nations; organizations; preparation
- **Environmental Impact**: Energy consumption of cooling; sustainability
- **Transparency**: Open research; responsible disclosure; governance
- **Economic Impacts**: Job displacement; new industries; disruption
- **International Competition**: National strategies; investment; geopolitical

### Mathematical Foundations
- **Linear Algebra**: Hilbert spaces; unitary matrices; tensor products
- **Group Theory**: Symmetries; representations; Lie groups
- **Probability Theory**: Born rule; measurement outcomes; statistics
- **Complex Numbers**: Phases; amplitudes; interference; Euler's formula
- **Matrix Operations**: Pauli matrices; tensor products; eigendecomposition
- **Optimization**: Variational methods; gradients; classical optimization
- **Fourier Analysis**: Quantum Fourier transform; frequency domains

## Key Theories

| Theory | Key Figure | Core Idea |
|--------|-----------|-----------|
| Shor's Algorithm | Peter Shor | Quantum algorithm exponentially faster than classical for integer factorization |
| Grover's Algorithm | Lov Grover | Quantum search provides quadratic speedup over classical unstructured search |
| Quantum Supremacy | Google (Arute et al.) | Demonstrated quantum device outperforming classical for specific task |
| Threshold Theorem | Various | Below error threshold, arbitrary quantum computation possible |
| No-Cloning Theorem | Wootters, Zurek, Dieks | Cannot copy unknown arbitrary quantum state |

## Important Figures

- **Richard Feynman**: Original quantum computing idea; simulating physics
- **David Deutsch**: Quantum Turing machine; quantum computation foundation
- **Peter Shor**: Factorization algorithm; cryptography implications; MIT
- **Lov Grover**: Search algorithm; database search speedup; Bell Labs
- **John Preskill**: Quantum complexity; fault tolerance; NISQ era terminology
- **Yoshua Bengio**: Quantum machine learning; quantum cognitive tools
- **Scott Aaronson**: Quantum complexity; quantum supremacy; popularizer
- **Michele Mosca**: Quantum computing; cryptography; impact assessment
- **Seth Lloyd**: Quantum algorithms; quantum machine learning; MIT
- **John Martinis**: Google's quantum supremacy; superconducting qubits

## Frontiers

- **Fault-Tolerant Quantum Computing**: Logical qubits; error correction; practical applications
- **Quantum Machine Learning**: Accelerating ML algorithms; quantum neural networks
- **Quantum Simulation**: Materials; drug discovery; beyond classical capability
- **Quantum Internet**: Secure communication; distributed quantum computing
- **Quantum Sensing**: Ultra-precise measurement; imaging; navigation
- **Photonic Quantum Computing**: Room temperature; different scalability path
- **Hybrid Classical-Quantum Systems**: Best of both; practical near-term applications
- **Quantum Software Stack**: Better tools; debugging; optimization; accessibility

## Applications

- **Cryptography**: Breaking RSA; post-quantum migration; secure communication
- **Drug Discovery**: Molecular simulation; protein interaction; drug design
- **Materials Science**: New materials; batteries; catalysts; design
- **Financial Services**: Portfolio optimization; risk analysis; pricing
- **Logistics & Optimization**: Routing; scheduling; supply chain
- **Machine Learning**: Training acceleration; new algorithms; quantum kernels
- **Climate Modeling**: Complex simulation; materials for clean energy
- **National Security**: Cryptanalysis; defense applications; intelligence

## Classic Works

- **"Quantum Computation and Quantum Information"** by Nielsen & Chuang — Definitive textbook
- **"Introduction to Quantum Mechanics"** by Griffiths — Quantum mechanics foundations
- **"Quantum Computing Since Democritus"** by Scott Aaronson — Accessible introduction
- **"Programming the Universe"** by Seth Lloyd — Quantum computing for general audience
- **"Quantum Computer Science"** by David Mermin — Computer science perspective
- **"Learn Quantum Computing with Python and Q#"** by Sarah Kaiser — Practical introduction
- **"Quantum: A Guide for the Perplexed"** by Jim Al-Khalili — Popular science

## See Also

- [Computer Science](computer-science.md) — Classical computing foundations
- [Physics](physics.md) — Quantum mechanics foundations
- [Mathematics](mathematics.md) — Linear algebra; mathematical foundations
- [Cryptography](cybersecurity.md) — Post-quantum cryptography
