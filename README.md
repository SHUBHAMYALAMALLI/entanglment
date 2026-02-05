Multipartite Quantum Entanglement Simulator

This project is a Python-based simulator designed to study and visualize quantum entanglement in multipartite qubit systems. It provides a computational framework to analyze how entanglement is distributed among different subsystems using tools from quantum information theory, such as density matrices, partial traces, and purity measures.

The simulator begins by constructing an initial separable quantum state from individual probability distributions. These local states are combined using tensor products to form a global product state. Random quantum phases are then applied to introduce superposition and coherence, allowing the system to evolve into a potentially entangled state. From this state, the full density matrix is constructed, enabling systematic analysis of subsystem correlations.

To quantify entanglement, the program performs partial traces over selected subsystems, producing reduced density matrices for different partitions. For each reduced state, the purity is computed as
Purity = Tr(ρ²).
Purity serves as a simple and effective indicator of entanglement: values close to 1 correspond to weakly correlated or separable states, while lower values indicate stronger quantum correlations and higher entanglement.

The simulator automatically generates human-readable subsystem partitions, including fully local, single-versus-rest, and balanced bipartitions for larger systems. This allows users to compare entanglement across multiple structural decompositions of the same quantum state. The results are presented through clear bar plots, offering an intuitive visual representation of how entanglement varies with partition choice.

This project is useful for students and researchers interested in quantum computing, quantum communication, and foundational studies of multipartite systems. It offers an accessible way to experiment with entanglement measures while maintaining a solid theoretical foundation.

By combining numerical simulation with visualization, this tool bridges abstract quantum concepts and practical computation. It also serves as a flexible platform for future extensions, such as incorporating specific entangled states (GHZ, W, cluster states), higher-dimensional systems, decoherence models, or alternative entanglement measures.
