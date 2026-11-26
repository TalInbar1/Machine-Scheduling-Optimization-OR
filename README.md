# Machine Scheduling Optimization & Approximation Algorithms

## Project Overview
This project addresses the classical "Parallel Machine Scheduling" problem, aiming to minimize the maximum completion time ($C_{max}$) for tasks with varying processing times on machines with different speeds ($S_1, S_2$). 

The project combines theoretical proofs of NP-hardness and approximation ratios with a practical VBA-based simulation tool.

## Key Components & Analysis
*   **Mathematical Modeling:** Formulated the problem as a **Linear Programming (LP)** model using binary variables for optimal task assignment.
*   **Algorithm Analysis:** Proved approximation ratios for several heuristics:
    *   **Load Balancing (Algorithm H):** Analyzed the performance bound relative to the optimal schedule.
    *   **Greedy Heuristics:** Evaluated "Mr. Balanced" and "Mrs. Speedy" strategies, determining the best algorithm based on machine speed ratios ($S_2$).
*   **Custom Heuristic (H4):** Developed a novel $O(n)$ heuristic designed to balance loads based on an "Ideal Load" calculation.

## Implementation
*   **VBA & Excel:** Developed a robust tool in Excel using **VBA (Macros)** to automate task scheduling and visualize machine loads.
*   **Complexity:** Ensured all implemented heuristics maintain polynomial runtime complexity, specifically $O(n^2)$ or better.

## Academic Insights
*   Proven that the problem is NP-hard for specific speed ratios.
*   Established tight lower bounds based on perfect machine balancing and the "Longest Processing Time" (LPT) logic.

## Technologies Used
*   **Languages:** VBA (Excel Macros)
*   **Concepts:** Operations Research (OR), Approximation Algorithms, Linear Programming, Computational Complexity.
