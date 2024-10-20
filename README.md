# Markov Jump Processes and M/M/1 Queue Simulation

## Overview

This project focuses on understanding **Markov Jump Processes (MJP)** and implementing them in Python through simulations. Specifically, the project addresses **M/M/1 queueing systems**, combining theoretical analysis with computational simulations. 

The key tasks involved:
- Developing a clear understanding of Markov Jump Processes.
- Implementing simulations of M/M/1 queues using Python.
- Providing theoretical justifications for the behavior of the M/M/1 system.
- Creating an original proof related to the M/M/1 queues and verifying it through simulation.

## Project Goals
- To simulate **M/M/1 queues** using Python.
- To provide a theoretical foundation for the queue dynamics.
- To derive and present an **original proof** related to the M/M/1 queue, followed by validating the proof with simulations.

## Key Concepts

1. **Markov Jump Processes**: A stochastic process where transitions between states occur at random time intervals, with the next state depending only on the current state (Markov property).
   
2. **M/M/1 Queue**: A classic queueing model where:
   - Arrival times are determined by a Poisson process (exponential inter-arrival times).
   - Service times are also exponentially distributed.
   - There is only one server.
   - The model assumes infinite capacity for waiting customers.

3. **Original Proof**: A novel proof was developed from scratch to justify certain behaviors in the M/M/1 queue system. The proof was not based on pre-existing templates and was independently derived.

## Project Structure

- **Theoretical Justifications**: Detailed mathematical derivations explaining the behavior of the M/M/1 queue system.
- **Simulations**: Python code implementing the M/M/1 queue, allowing for both visual and computational verification of the theoretical analysis.
- **Proof and Validation**: An original proof related to the system’s behavior, followed by simulation-based validation.

## How to Run the Project

1. **Install Dependencies**:
   Make sure you have Python installed along with the necessary libraries (e.g., `numpy`, `matplotlib`). You can install them using:
   ```bash
   pip install numpy matplotlib
   ```

2. **Run the Simulation**:
   Execute the provided Python script to run the M/M/1 queue simulations and see the results.
   ```bash
   python simulation.py
   ```

3. **View Theoretical Justifications**:
   Refer to the provided documentation or notebook file for a detailed explanation of the theoretical concepts behind the simulations.

## Conclusion

This project serves as a hands-on exploration of Markov Jump Processes through a practical implementation of the M/M/1 queueing system. By combining theory with simulation, the project offers a comprehensive understanding of the dynamics involved in this fundamental queueing model.

## License

This project is open-source and licensed under the MIT License.

---

Feel free to explore the code, theory, and simulations provided in this project. For any questions or contributions, please reach out via the repository's issue tracker.
