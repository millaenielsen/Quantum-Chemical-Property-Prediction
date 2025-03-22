# Quantum-Chemical-Property-Prediction

Dataset Description: The PCQM4Mv2 dataset contains approximately 3.7 million molecules rep- resented as graphs, where nodes represent atoms (with atomic features) and edges represent chemical bonds (with bond features). The task is to predict the HOMO-LUMO energy gap (a quantum chemical property crucial for understanding the reactivity and optoelectronic properties of a molecule). This regression task is evaluated using Mean Absolute Error (MAE). The dataset is split into training, val- idation, and test sets, with a separate out-of-distribution test set to evaluate generalization

Objective: develop a graph neural network model that can accurately predict the
HOMO-LUMO energy gap of molecules, achieving better performance than the GIN-virtual baseline
(MAE: 0.1083 on validation).

