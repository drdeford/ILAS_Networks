# Applications of Linear Algebra to Graph Theory and Network Sciece

This repository contains some resources related to my <a href="https://la-education.oucreate.com/monthly-video-podcasts-2023/">ILAS vodcast</a> about relationships between linear algebra, graph theory, and network science. The slides that I used for the presentation are above (ILAS_Slides.pdf) and there are some additional resources here: https://github.com/drdeford/CISER2023NetworkX/ for getting started with Python and NetworkX if you'd like to learn more. 

The notebooks that I discussed in the video include: 

*  **ILAS_Examples.ipynb** This notebook walks through the initial graph examples for our toy graph, including the basic spectral properties of the adjacency matrix and Laplacian. 
* **1\_Ego\_Networks.ipynb** This notebook explores the basic properties of the Graph object in networkx by directly constructing ego networks. We will see how to access properties of the corresponding nodes and edges and visualize the networks using the `draw` function. 
* **2\_Social\_Networks.ipynb** In this notebook we will examine how to work with larger and more complex networks and evaluate the results of graph algorithms, including centrality calculations. The main motivating examples will show some of the common properties of social networks and how they differ from structured combinatorial graphs and random network models. 
* **3\_Network\_Dynamics.ipynb** In the next notebook we will put everything together, looking at how to model random walks, heat diffusion, and epidemiological disease spreading using networkx. 
* **4\_Network\_Clustering.ipynb** In the final notebook we look at some examples of network clustering and investigate the relationship between clusters and spectral structure. 


![Network Diffusion](https://github.com/vrdi/Networks-Breakout/blob/master/Day4/100_node_diffusion.gif)
