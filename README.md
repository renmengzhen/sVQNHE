This README.md file provides an overview of the main Python files, the sVQNHE algorithm class, and the results folder in this repository.

Main Python Files.
The main_*.py files are the primary scripts for running simulations. Specifically:

main_exact.py corresponds to the Ideal Numerical Simulation;

main_noise_heisenberg.py corresponds to the Noisy Numerical Simulation (finite sampling and device noise);

main_maxcut.py corresponds to the maxcut example, considering only finite sampling noise.


sVQNHE Algorithm Class.
The vqes folder contains the sVQNHE algorithm class. Before running the main scripts, you need to replace the original vqes.py file in the tensorcircuit library's VQNHE method with the corresponding file from this folder.

Results Folder.
The results folder contains all the running results corresponding to the article.
