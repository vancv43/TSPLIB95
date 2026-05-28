# TSPLIB
Traveling Salesman Problem (TSPLIB Dataset)

Library of Traveling Salesman problems from http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/ <sup>[1]</sup>

This is just the Symmetric TSP data.
Currently known best solutions are in the `solutions` file.

<sup>[1]</sup> Reinelt, G. "TSPLIB--A Traveling Salesman Problem Library." ORSA Journal on Computing, Vol. 3, No. 4, pp. 376-384. Fall 1991.

Dataset Scale and Content: The TSPLIB library serves as a standardized benchmark, providing a comprehensive collection of problem instances designed for evaluating the performance of optimization algorithms. The scale of these datasets varies significantly, ranging from small-scale instances with approximately 48 to 51 nodes (e.g., eil51, berlin52) to large-scale networks exceeding 1,300 nodes, such as nrw1379 or fl1400.

Popular Benchmark Instances: Several categories and datasets are frequently extracted from TSPLIB for experimental validation, including:

Pr-group: pr76, pr152, pr299, pr439, and pr1002.

Kro-group: kroA100, kroB100, kroC100, kroD100, and kroA200.

Standard instances: ch150, d198, rat783, p654, and eil101.

Extended Applications: Although the original TSPLIB dataset primarily provides distance metrics for the Symmetric Traveling Salesman Problem (STSP), where travel costs are identical in both directions, it has been robustly adapted and extended by the research community to serve as a foundation for testing complex, real-world variants:

Probabilistic TSP (PTSP): TSPLIB instances are utilized to generate homogeneous or heterogeneous scenarios by assigning specific visitation probabilities (ranging from 0.1 to 0.9) to each customer.

Multiple TSP (MTSP) / Multi-depot Multiple TSP (MMTSP): The node and cost structures of TSPLIB (such as the Pr-group datasets) are applied to evaluate routing and clustering problems involving multiple sales agents originating from single or multiple depots.

Traveling Salesman Problem with Drone (TSP-D): TSPLIB datasets are repurposed to simulate last-mile delivery challenges involving truck-drone synchronization, providing a basis for comparing metaheuristic methods (e.g., Bat Algorithm, Particle Swarm Optimization, Genetic Algorithms) against known optimal solutions.

