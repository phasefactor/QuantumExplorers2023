# Notes for [Quantum Explorers 2023](https://challenges.quantum.ibm.com/quantum-explorers-23)
The QE23 challenge is divided into seven badges.
- [Captain](#captain)
- [Time Traveler](#time-traveler)
- [Space Combatant](#space-combatant)
- [Expert Navigator](#expert-navigator)


## Captain
Introduction to Qiskit and Quantum Computing.

### Activities
- [Quantum Computing Demo Notebook](./Captain/QE_Introductory_Demo_2023.ipynb)


### Quiz Topics
- Basis states
- Quantum states and randomness
- Rotation
- Basic Qiskit syntax (QuantumCircuit, etc)
- Reading quantum circuit diagrams
- Reading/Construction of Qsphere
- manual construction of controlled gates
- Entanglement and measurement correlation
- Bell States
- GHZ States and their construction
- teleportation algorithm
- Grover's algorithm
  - implemetaion for the two qubit case
  - understanding effects of iterations on accuracy
- measurement in X and Y bases (instead of Z)
- annoyingly must read Quantum Kittens chapter 3 for context


## Time Traveler

### Quiz Topics
- Describe quantum error mitigation
  - know the types: ZNE (zero noise extrapolation), M3, PEC, T-Rex (Twirled Readout Error Extinction)
- describe quantum error correction
- know the difference between quantum error mitigation and correction
- know sources of quantum error
- tradeoffs of increasing resilience level
- problems with applying classical error correction to quantum information
- definition of T1 and T2 values for quantum computers
- explain syndrome measurement
- running Qiskit primitives with and without resilience levels




## Space Combatant

### Quiz Topics
- Significant amount of normal Machine Learning vocabulary/concepts:
  - types of ML (supervised vs unsupervised vs re-inforcement learning)
  - general steps taken in each kind of ML
  - what is a generative model and what do you use it for
  - existing algorithms (k-Nearest Neighbors, etc)
  - linear separability, activation functions, feature maps, confusion matrices, residuals
- RAM vs Quantum RAM
- data encoding techniques
- known the types of feature maps and neural network models provided in Qiskit's ML module
- types of simple circuits: parameterized, unparameterized, etc
- expressibility vs entanglement capability (from textbook)
- parity post processing for Quantum Classifier (from Amira's lecture)
- know the implementation of a quantum Vector Support Classifier
 


## Expert Navigator

### Quiz Topics
- give the process/steps for defining an optimization problem
- what are objective, cost, and optimization functions
- define combinatorial optimization problems and max-cut optimization problems
- exact vs approximate algorithms, simulated annealing, P vs NP (hard, complete, etc)
- list features provided by Qiskit Optimization module
- know Qiskit Sampler primitive's properties
- conversion of max cut to quadratic optimization
- explain the QAOA algorithm, what is a mixing circuit?
- know about quadratic optimization.  steps for solving, relation to Ising Hamiltonians
- use of Sampler to create Variational Quantum Eigensolver
- hybrid algorithms and the split of workload between classical and quantum compute
- knoq about QUBO (optional video)



## Supreme Observer

This badge does not have a quiz, but does contain several coding exercises.

### Things to Know
- Cartesian Product [(lesson)](https://learning.quantum.ibm.com/course/basics-of-quantum-information/multiple-systems#classical-information)
