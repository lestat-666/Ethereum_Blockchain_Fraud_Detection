# ETHEREUM_BLOCKCHAIN_FRAUD_DETECTION

## Applied graph representation learning to detect anomalous wallets in Ethereum blockchain transactions using node embeddings and GCNs.

## Project Overview

This project develops a comprehensive graph-based machine learning framework to detect phishing scams on the Ethereum blockchain using node classification models. The system processes real transaction data to construct complex network graphs and applies multiple embedding strategies to identify fraudulent wallet addresses with high accuracy.

## Key Findings

- **Dataset Scale**: Successfully processed 1,600+ verified phishing addresses creating transaction network with 30,000+ nodes and 80,000+ transaction edges
- **Superior Performance**: GCN model achieved 98.87% accuracy with 99.53% precision for legitimate transactions and 79.37% recall for fraud detection  
- **Comparative Analysis**: GCN significantly outperformed traditional embedding methods (Node2Vec: 95.5%, GraphSAGE: 98.0% accuracy)
- **Novel Approaches**: Ego-graph methods effectively captured localized fraud patterns with reduced computational requirements
- **Class Imbalance Impact**: Demonstrated significant challenges in minority class detection, highlighting need for advanced sampling techniques
- **Scalability**: Full-graph methods showed computational limitations compared to localized subgraph approaches

## Technical Stack

**Graph Processing**: NetworkX, PyTorch Geometric, Node2Vec, Graph2Vec
**Machine Learning**: Scikit-learn, PyTorch, Random Forest, SVM, Logistic Regression, K-NN
**Neural Networks**: Graph Convolutional Networks (GCN), GraphSAGE, Graph Neural Networks
**Data Engineering**: pandas, NumPy, Python, SMOTE
**Network Analysis**: Karateclub, Gensim, Word2Vec
**Visualization**: matplotlib, seaborn, NetworkX plotting

## Authors

Anastasiia Golovchenko et al.
