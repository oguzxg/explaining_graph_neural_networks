# Explaining Graph Neural Networks Predictions
Explainability in Machine Learning Models is an important topic. 
Unlike simpler models like linear regression or decision trees, Graph Neural Network's (GNN) black-box nature raises questions about how they arrive at
their predictions and what factors influence their decision-making.
The black-box nature of GNNs raises critical questions about interpretability.
How does a GNN arrive at a particular prediction? Which specific nodes or
edges in the graph hold the most influence over the decision? What are the
most relevant features that inform the GNNs decision-making process? These
questions highlight the need for interpretability techniques that can uncover the
underlying mechanisms of GNNs and provide transparent explanations for their
predictions.
Explaining the predictions of a Graph Neural Network is a crucial task for
several reasons. First, interpretability is vital in many real-world applications,
especially those with high stakes, such as healthcare, finance and law enforcement, where decision-making processes need to be transparent and justifiable.
Second, providing explanations can enhance user trust and acceptance of GNN based systems, allowing users to understand and verify the model’s reasoning
behind its predictions. Lastly, explanations can help identify potential biases,
limitations, or vulnerabilities in the model, driving improvements and reducing
potential risks.


### Getting started

#### **Dataset**
The dataset will be imported by the torch_geometric.datasets api while the runtime.


#### **Imports**
All additional library installs should be done by the first cell where every required !pip install {library_name} is mentioned
