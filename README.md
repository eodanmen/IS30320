IS30320 LAB EXERCISE ON NETWORK REPORT PRESENTED IN MARKDOWN CODE/FORMAT
===========================================================================

THE PROCESS OF CREATING MY NETWORK GRAPH USING GEPHI
------------------------------------------------------

Within last week’s lab exercise, we were required to utilize Gephi, in order to produce an illustration of a partially-directed social network, such as facebook, consisting of clear labels for each node, showing at least 2 coloured clusters with bonding and bridging or strong and weak ties. The illustration was expected to aim for the Schneiderman’s Netvizz Nirvana standard of graph quality.

The first thing I did in order to begin deriving a solution to this exercise was to visit facebook, logging into my account on the Social Media Network and immediately using Netvizz to capture my network data from within facebook for visualization purposes. Netvizz is a tool that extracts data from different sections of the facebook network and puts them into a GDF (.gdf) file for data visualization purposes. It is a free tool to utilize for this purpose within facebook and presents a partially-directed or fully-directed network, depending on how the tool is configured and can be easily searched for within facebook. I configured my version of Netvizz to provide me with a partially-directed network of my facebook friend network, showing all of the friends (nodes) existing within my network and the various relationships (edges) existing between them only.

Upon obtaining the GDF file from facebook, I then proceeded to launching my previously downloaded (from https://gephi.github.io/) and successfully installed version of the Network Data Visualization Software Program known as GEPHI. 

Within Gephi, I selected a New Project and opened up my Netvizz GDF (.gdf) file, which I had already obtained using facebook and made sure the Graph Window was opened upon the loading of the Netvizz GDF file. This was ensured by clicking on the Window tab and selecting Graph. Upon loading the Netvizz GDF file, it was not at first very informative, as it only presented me with huge chunk of nodes and edges clustered together. So I selected a suitable layout (Force Atlas 2) and ran it from second sub-pane along the left pane of the Gephi interface. This presented a much clearer breakdown of all nodes and edges, making the necessary clusters of nodes and edges become very visible. I then further customized the layout chosen and kept on running it with the changes I kept on making, until I was finally satisfied with the concluding result. I zoomed in to get a better view of the Network Graph from within the layout and turned on labels by clicking on the T symbol at the bottom pane of the Gephi interface.

With all of this working properly, I went on to try out the Modularity feature within Gephi. This was achieved under Statistics on the right pane of the Gephi interface. The purpose of the Modularity feature is when ran or activated is to perform a collection of calculations concerning the various clusters and nodes to determine the level of modularity existing within and between them. Upon completing this step, I selected the Partitioning feature, navigated to my generated modularity class and hit the APPLY button, in order to proceed to colour code the various nodes with various colours to uniquely identify various nodes within the various clusters. I then went on to experiment with the Filter feature, located right next to the Statistics feature and selected Degree Range under Topology, in order to filter out certain nodes that possessed absolutely no edges or below a degree of 5 edges or relationships. I used Preview to view a final version of my Network Graph, which worked perfectly well for me, before then exporting the graph as PDF document and saving to my computer.

MY UNDERSTANDING OF THE VARIOUS TERMS FROM SOCIAL COMPUTING
------------------------------------------------------------

-	NODE: A node is a basically an entity within a network. This could be an individual, animal, place or just about any physical noun. They are also called vertices.
-	EDGES: These are relationships or associations existing between various nodes within a network. They could be symmetrical or asymmetrical in nature.
-	INFLUENCE: This refers to how much a node depends on the existence of another node in the network.
-	BRIDGING: This refers to weak ties or smaller number of edges between nodes.
-	BONDING: This refers to strong ties or higher number of edges between nodes.
-	DEGREE: This refers to how closely related 2 or more nodes are to one another. That is the number of edges existing between nodes or vertices.
-	BETWEENESS: This is an indication of a node’s centrality in a network and is a factor of the number of shortest paths from all vertices to all other vertices that pass through that node. 
-	CLOSENESS: This is basically the shortest path between one vertex and another vertex in a network.
-	EIGEN-VECTOR CENTRALITY: This is the measure of the influence of a node in a network.
