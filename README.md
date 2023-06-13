# Snap_Net# Network Analysis and Comparison

This project focuses on analyzing and comparing different types of networks using network analysis techniques. It utilizes the SNAP package for Python to perform the analysis tasks and provides insights into various network properties. 

## Dataset Selection
Select a directional dataset from [Stanford SNAP](http://snap.stanford.edu/data/index.html#socnets) as the basis for network analysis.

## Network Analysis
Perform the following analysis for the selected dataset:

A. The number of nodes in the network.
B. Count the number of directed and undirected edges.
C. Calculate the average clustering coefficient to measure the degree of clustering in the network.
D. Identify and count the number of poorly connected components.
E. Determine the number of nodes in the largest strongly connected component.

## Degree Distribution Analysis
Draw the distribution of input degrees and output degrees in log-log form. This analysis provides insights into the network structure and degree distribution.

## Network Model Comparison
Compare three network models with the real-world dataset:

1. Random Network: Create a random network using the Aqdosh-Rini model (G(n,m)) with n=5242 nodes and m=14484 edges. The edges should be placed randomly without using ready-made methods from SNAP.
2. Small World Model: Create a grid-like small world network with 5242 nodes. Each node is connected to its left and right neighbors, forming a ring structure. Connect each node to the neighbors of its neighbors. Finally, randomly select 4000 pairs of nodes and create edges between them.
3. Real World Network: Utilize the CA-GrQc.txt dataset file (attached with the exercise text file) and remove ring and duplicate edges. This network should contain 5242 nodes and 14484 edges.

## Excess Degree Distribution Analysis
Calculate the excess degree distribution (kq) based on the given degree distribution (kp) for each of the three networks. Draw the excess degree distribution curves in log-log form and analyze the differences between the obtained curves.

## Dependencies
- Python
- SNAP package for Python

## Usage
1. Clone the project repository.
2. Install the required dependencies, including Python and the SNAP package.
3. Select a directional dataset from Stanford SNAP.
4. Run the network analysis tasks using the provided Python scripts.
5. Examine the generated results, plots, and analysis for the selected dataset and network models.

This project provides valuable insights into network analysis techniques, network properties, and the comparison of different network models. It aims to enhance understanding of network structures and behaviors, facilitating further research and analysis in the field of network science.
