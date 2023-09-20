# Graph_Feature_Augmentation
Abstract
Today, graph data constitutes a wide range of data. Maintaining the graph structure of data is very important when working with them. One of the prominent tools in the field of machine learning is graphical neural networks. Graph neural networks are able to maintain the graph structure of the data during training. Unlike traditional neural networks, which work on vector or matrix data, graph neural networks can learn about the relationships between nodes and edges, or connections, in a graph. This makes them suitable for tasks such as node classification, graph classification, and link prediction.
The input of a neural network is a graph that consists of nodes (vertices) and edges (links). Nodes represent the entities in the graph and edges represent the relationships between those entities. Nodes and edges also have their own associated properties, such as node properties and edge weights. A node may have certain properties that make it unique or distinct from other nodes, and these properties are called node properties and provide more information about the properties or behavior of the node. For example, in a social network graph, a node that is equivalent to a person may have characteristics such as age, gender, occupation, etc.
Node properties are critical in many graph-related tasks, such as node classification, link prediction, and community detection. By using node properties, these tasks can be performed more accurately and efficiently, leading to better insight and understanding of the graph structure.
In this project, graph algorithms are used to define new feature vectors in neural graph networks for the extension of the feature vector of nodes. In particular, the performance of the new feature vector is investigated in four popular neural graph neural network models: GCN, GraphSAGE, GAT, and SGN. The results of these extensions are compared on the CORA data set and it is shown that the use of the proposed techniques for the feature vector causes improvements in the performance of the model, and the results show that the combination of graph algorithms in the feature engineering process can increase the expressive power of neural graph networks. and improve their ability to learn structured data representation with graphs, and if the content features of the node are not accessible through the dataset, with these methods, the features vector can be replaced.
The proposed  methods for feature augmentation are:
feature_1: Using a constant vector for all nodes
feature_2: Using  unique IDs for each node and digitizing these IDs
feature_3: Using  unique IDs for each node as a single string
feature_4: Using  the welsh coloring algorithm for nodes and digitizing the colors
feature_5: Using the welsh coloring algorithm for nodes, digitizing the colors and extending the length of the resulting vector
feature_6: Using a self-defined coloring algorithm for nodes, digitizing the colors and extending the length of the resulting vector
feature_7: Using a  self-defined coloring algorithm for nodes, digitizing the colors
feature_8: Using a  self-defined coloring algorithm for nodes
feature_9: Using  graph algorithms like Page Rank, Clustering Coefficient, Node Centrality,Node Betweenness, Node Closeness
The project file consists of:
Algorithms.zip: implementation of the GNN algorithms  used in this project
features.zip: implementation of the 9 mentioned methods to create  results without the original features
augmentation.zip: augmenting original features with our 9 obtained features to compare the results
iterations.zip: In order to validate the results, we repeat the experiment 10 times with different parts of the CORA data set and in
Each time, we select 100 unique members of the data set from a subset.
