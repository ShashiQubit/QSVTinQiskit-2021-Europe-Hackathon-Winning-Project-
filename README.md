# QSVT in Qiskit
Quantum algorithms re-imagined as the iteration of a 'simple' circuit through Quantum Singular Value Transformation

# Demonstrating the Grand Unification of Quantum Algorithms and Making Them More NISQ-friendly
Quantum Singular Value Transformation is a promising new framework that allows one to apply a polynomial transformation to the singular values of a block-encoded unitary transformation, first coherently introduced by Gilyen et. al in a 2018 paper. Later, about 4 months ago, Prof. Isaac Chuang has given an overview of Gilyen's ideas, and how QSVT serves as a unification schemes for many quantum algorithms as something more fundamental. Even more recently, last week, Seth Lloyd and colleagues published a preprint on 'Hamiltonian Singular Value Transformation and Inverse Block Encoding' for NISQ-era devices.

One of the most important challenges in the broad field of Quantum Information is finding useful, NISQ-era applications that offer some valuable speed-up to their classical counterparts, which can be employed in academic research and industry today. The QSVT effort is an emerging and potentially-impactful development towards these NISQ-applicability as it allows one to fundamentally re-cast any complex circuitry as the iteration of a single, simple circuit structure that,as parameters, require merely the block-encoded Unitary and the relevant polynomial transformation of interest.

In this project, the aim is to apply QSVT hands-on in Qiskit and develop a useful libarary dedicated to general QSVT framework where different algorithms can be expressed as the different side of a many-sided dice, with the corresponding encoding and polynomial transformation. 

# Algorithms That Are Confirmed to be QSVT-expressable

Hamiltonian Simulation and Quantum Walks

Grover's Search

Shor's Algorithm

HHL (for solving linear systems of equations)

Several QML algorithms

# Short-term Goals

Implement the Hamiltonian singular value transformation in Qiskit and prepare a user-friendly library/repository Qiskit users. This requires implementing Block encoding and generalized QAOA (Quantum Alternating Operator Ansatz). Implementing these harmoniously will be the main short-term challenge and goal of the team, first and foremost.

# Long-term Goals

Keep implementing different algorithms in the repository to create a rich QSVT library for Qiskit, demonstrating the unification of different quantum algorithms and potentially creating more NISQ-era friendly forms.
