# igraphtool
Network analysis tool (wrapper for python-igraph)
-------------------------------------------------

PACKAGES 

python v2.7
igraph
matplotlib

--------------------------------

Installation

FOR DEBIAN USING APT

sudo apt-get install python-igraph
sudo apt-get install python-matplotlib

USING PIP

pip install python-igraph
pip install  matplotlib

---------------------------------

USAGE

python Tool.py input_file

----------------------------------

INPUT FILE FORMATS

Graphml file
Adjacency matrix
Edgelist format
Weighted Edgelist
Lgl 
*also generates a Random network to benchmark your data and compare it against random dataset  

-----------------------------------------

ABOUT Tool.py 

This accepts network file in major formats as edgelist, graphml file ,adjacency matrix ,lgl,and for benchmarking random network also generated to compare data against random dataset 

One can use this script to evaluate many parameters or to analyse data for many purpose 
 
Histogram  of degree 
Centrality
*Eigenvector centrality
*Betweenness centrality
Average path length
Degree distribution
Clustering coefficient
Shortest path between two pair of nodes 
Shortest path between all nodes
Degree distribution power law
Functional motifs
Neighbour vertex
*for two specified pair of vertex
*for all vertex of graph
Modularity  
Connectivity 
Vertex *for given two pairs vertex.  
*overall.
    Edge   *for given two pairs  vertex
*overall  
No. of clusters
Adjacency matrix of network
Given node id its corresponding node  attribute 
All node ids and their  corresponding node attribute 
Edgelist.
Diameter of graph 
Average path length
Giant_component into a file 
Add vertex(single)
Add vertices(many)
Delete vertex(single)
Delete vertices(many)
Maximum degree   nodes
Minimum degree nodes.
Deleting all node one by one  saving in file to check how it affects 
----------------------------------------------------------------------




