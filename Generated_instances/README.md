# Benchmark Instances

This folder contains the instances used in the study:  
**"An Efficient Divide-and-Conquer Enhanced Metaheuristic for Operating Room Scheduling: A Real-World Case Study"** (Chouraqui et al., 2026).

## Important Notes on Instances

*   **Generator vs. Legacy Data:** The instances were generated using an earlier version of the Python script provided in the main directory. While the script has been cleaned and translated into English for clarity, the instances themselves may still contain legacy parameters in French (e.g., `nb_chirurgiens`, `horaire_debut`) and auxiliary variables (e.g., `I`, `L`, `temps_infection`) that are no longer used in the final model.
*   **Setup Times Calculation:** Note a difference in how setup times are handled. While the current Python generator outputs the pre-calculated operation-to-operation setup time matrix (`TD`), these instance files require you to compute `TD` manually. You can easily reconstruct it by mapping the operation types matrix (`T`) to the setup times between operation types (`TCSTO`).
*   **Real-World Data:** Please note that instances **R1 and R2**, which correspond to the real-world hospital data discussed in the paper, are **not provided** in this repository due to strict medical confidentiality and data protection agreements.

## Dataset Description

The public instances are organized as follows:

*   **G1 Set**: Small-scale instances with $\le 100$ operations.
*   **G2 Set**: Medium-scale instances with $150$ to $200$ operations.
*   **G3 Set**: Large-scale instances with $1000$ operations.
*   **B1 & B2**: Classic benchmark instances used for baseline comparison.

---


