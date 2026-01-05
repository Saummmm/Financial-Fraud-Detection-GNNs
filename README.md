# Financial-Fraud-Detection-GNNs
A study on financial fraud detection with Graph Neural Networks

Detecting financial fraud has become increasingly
challenging with improvements in fraud techniques, especially
in the age of online transactions. Because of this, traditional
machine learning models often struggle to capture the intricate
relationships and temporal dynamics within transactional data.
To address this, we explore the use of Graph Neural Networks
(GNNs) for credit card fraud detection by representing trans-
actions as nodes and behavioural or feature-based similarities
as edges in a graph. Using the BankSim dataset, we construct
transaction graphs through k-nearest neighbour methods and
evaluate four GNN architectures: Graph Convolutional Network
(GCN), Graph Attention Network (GAT), GraphSAGE, and
Adaptive Sampling and Aggregation-Based GNN (ASA-GNN).
Their performance is compared with standard classifiers, in-
cluding k-Nearest Neighbours (KNN), XGBoost, and Random
Forest. This experiment is carried out on both balanced and
imbalanced datasets using the synthetic minority oversampling
technique (SMOTE) and stratified sampling to balance out the
unbalanced nature of transactional datasets. The performance of
the models was based on precision, recall, F1 score, and area
under the ROC curve (AUC), with a focus on F1 score. The
final results show that GAT and GraphSAGE outperform the
other models. GAT achieved an F1 score of 92.19% becoming
the highest score out of all four GNNs. ASA-GNN, while designed
to handle class imbalance, underperformed when applied to the
selected dataset. These findings show the future of GNNs in
building more robust fraud detection systems by combining the
structural and temporal context in transaction data.