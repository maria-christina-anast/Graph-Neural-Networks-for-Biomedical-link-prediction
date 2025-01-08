# Project Name: Graph Neural Networks for Biomedical link prediction

This project focuses on parsing a large biomedical RDF dataset (OREGANO), creating subgraphs, and evaluating models using GNNs (Graph Neural Networks) and Node2Vec-based methods.

---

## **Project Structure**
The project contains the following files:
1. **`Subgraphs_creation.ipynb`**: Parses the full dataset (`oreganov2.1.rdf`) and creates smaller subgraphs.
2. **`Node2Vec-LRcv-EvaluationMetrics-specificDatasets-Grid-Class.ipynb`**: Implements Node2Vec with Logistic Regression and evaluates performance using cross-validation and specific datasets.
3. **`3ModelsGNN-specificDatasets-Class.ipynb`**: Implements three GNN models for classification tasks and evaluates their performance.

---

## **How to Use**

### **Step 1: Prepare the Environment**
Ensure you have the following installed:
- Python 3.8+ 
- Jupyter Notebook
- Required Python libraries: `rdflib`, `networkx`, `numpy`, `scikit-learn`, `torch`, etc.

More information about the dataset could be found in the below paper:
https://www.nature.com/articles/s41597-023-02757-0
