# Transformation of Quantum expectation value problem to Classical Machine and Deep Learning problem
Conversion of quantum expectation value problem using shadow tomography to deep learning problem by doing fewer measurement 

In this project, I have used **de-randomized shadow tomography** to get a classical description of unknown quantum many-body states by repeated measurement. Then, I applied classical machine and deep learning to predict expectation values from Pauli operators and coefficients by conducting **only 185 measurements, 1315 less than related works of other authors and achieved an RMSE of 0.20 on test data relative to RMSE of 0.06 by paper named "Efficient estimation of Pauli observables by derandomization" authors for 1500 measurements.** Moreover, I have used **Explainable AI (Lime and Sharp)** to explain the predictions.

Papers work I have extended:
1) **Predicting many properties of a quantum system from very few measurements (https://www.nature.com/articles/s41567-020-0932-7)**
2) **Efficient estimation of Pauli observables by derandomization (https://arxiv.org/abs/2103.07510)**
3) **Information-theoretic bounds on quantum advantage in machine learning (https://www.arxiv.org/abs/2101.02464)**

The code of the original papers is hosted on the following links

1) https://github.com/hsinyuan-huang/predicting-quantum-properties
2) https://github.com/renatawong/classical-shadow-vqe

Quick guide for some necessary tutorials for this work

1) https://www.youtube.com/watch?v=NXejv2wVwas
2) https://www.classiq.io/algorithms/variational-quantum-eigensolver-vqe
3) https://qiskit-community.github.io/qiskit-nature/tutorials/06_qubit_mappers.html
4) https://www.youtube.com/watch?v=YtepXvx5zdI
