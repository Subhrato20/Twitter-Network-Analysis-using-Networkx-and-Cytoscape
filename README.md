# Twitter-Network-Analysis-using-Networkx-and-Cytoscape
## Visual Representation of the Network
![Screenshot 2022-06-11 165240](https://user-images.githubusercontent.com/61539946/173186041-362bfc9b-59e8-43d1-be8b-8fd8e83ac60e.png)
  
## Introduction:-
In our project, we have used the Higgs Twitter dataset for performing its social network analysis. The link for the dataset is- https://snap.stanford.edu/data/higgs-twitter.html. In our project we have used NetworkX, Pandas and Mathplotlib libraries. 
NetworkX- NetworkX is a Python language software package for the creation, manipulation, and study of the structure, dynamics, and function of complex networks. It is used to study large complex networks represented in form of graphs with nodes and edges. Using NetworkX we can load and store complex networks. We can generate many types of random and classic networks, analyse network structure, build network models, design new network algorithms and draw networks.
Pandas- Pandas is an open-source library that is made mainly for working with relational or labelled data both easily and intuitively. It provides various data structures and operations for manipulating numerical data and time series. This library is built on top of the NumPy library. Pandas is fast and it has high performance & productivity for users.
Matplotlib- Matplotlib is a cross-platform, data visualization and graphical plotting library for Python and its numerical extension NumPy. As such, it offers a viable open source alternative to MATLAB. Developers can also use matplotlib’s APIs (Application Programming Interfaces) to embed plots in GUI applications.
The need of our project is that it is a very efficient example of Social Network Analysis. It can be used as a reference for bigger and more important datasets. It can be used to find all the major metrics of a Social Network and its data can be used in an effective manner. We have also used Cytoscape which is an Open Source Social Network Visualisation and Analysis software. This software isn’t a very popular software but it is a very efficient software. Using this software, we have visualised the graphs and we can see the details of each node in the graph and also handle individual nodes. 

## About the dataset-
The Higgs dataset has been built after monitoring the spreading processes on Twitter before, during and after the announcement of the discovery of a new particle with the features of the elusive Higgs boson on 4th July 2012. The messages posted in Twitter about this discovery between 1st and 7th July 2012 are considered.

We are using the friends/follower’s social relationships among user involved in the above activities. 
It is worth remarking that the user IDs have been anonymized, and the same user ID is used for all networks. This choice allows to use the Higgs dataset in studies about large-scale interdependent/interconnected multiplex/multilayer networks, where one-layer accounts for the social structure and three layers encode different types of user dynamics.
### Tools Used:-
Jupiter Notebook 
Cytoscape
### Libraries Used:-
•	Networkx
•	Pandas
•	Matplotlib
 
## About our project and the work done:
The widespread adoption of Online Social Networks (OSNs), the ever-increasing amount of information produced by their users, and the corresponding capacity to influence markets, politics, and society, have led both industrial and academic researchers to focus on how such systems could be influenced.
#### 1) Importing Libraries and Creating Edge list:-
In this step we have imported all the data and set it up as in edgelist format.

#### 2) Visualizing the edges:-
After the process of importing and edge list creation is done the we have investigated to learn more about few edges and also visualized it using networkx draw first and then using that plot to draw in large scale using Matplotlib.

#### 3) Finding most influential and most important node in the network:-
For finding most influential node we have found the degree centrality of each nodes in the network.

In networkx library there is a predefined function for degree centrality which we have used to find the degree centrality for each node in our dataset. And the outcome which we have found is that the node number 134 is the most influential node in the network. 

For finding most important node we have found the eigenvector centrality of each nodes in the network.

In networkx library there is a predefined function for eigenvector centrality which we have used to find the same for each node in our dataset. And the outcome which we have found is that the node number 27 is the most important node in the network while 134 which is the most influential node is second.

#### 4) Finding the shortest path to reach from one node to other:-
For finding the shortest path we used shortest_path which is also done using pre-defined function in the networkx library.

#### 5) Finding best connector in the network:-
We have used betweeness centrality measure for finding best connector in the network and found it to be 126th node. 
Betweenness centrality is a way of detecting the amount of influence a node has over the flow of information in a graph. It is often used to find nodes that serve as a bridge from one part of a graph to another. The algorithm calculates unweighted shortest paths between all pairs of nodes in a graph.
 
#### 6) Creating subgraphs of the connections of a particular nodes:-
We found the type of connections a node have in network here also using networkx module and plotted the same using Matplotlib

#### 7)Community Detection:-
###### Community:- 
The condition of sharing or having certain attitudes and interests in common. With respect to graph it is the group of nodes densely connected with each other.
###### Community Detection:- 
Community detection is creating small communities out of a large graph.
In this project we have used griven newman for community detection we have defined it by making a function which takes betweenness centrilty and removes nodes hence forming small communities.

#### 8) Finding modularity of the graph and nodes:-
Modularity is a measure of the structure of networks or graphs which measures the strength of division of a network into modules (also called groups, clusters or communities). Networks with high modularity have dense connections between the nodes within modules but sparse connections between nodes in different modules.
Finding clustering value of each node:-

#### 9) Visualizing the graph using cytoscape:-
Cytoscape is an open source bioinformatics software platform for visualizing molecular interaction networks and integrating with gene expression profiles and other state data. In our project we have used cytoscape to learn more about our network and then analyse nodes with respect to above performed actions.


