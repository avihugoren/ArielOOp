
Name : Avihu Goren





In this project I implemented  data structure that represents an unidirectional  weighted graph and algorithms connected to this data structure 
The project consists of 4 departments:
The first one is : NodeDataW 
This class is designed as an private  internal class of a graph so that the user can not create vertices from the outside nor access them without accessing the graph.
This class contains a number of very simple functions such as
SetKey getKey SetInfo getInfo SetTag GetTag.
The second class is Neighbors:
Like a node class, this class is a private and internal class of the graph.
The role of the class is to represent a list of node neighbors in the graph the structure that the class uses is a HashMap that has the ability to perform get and contain in constant time.
This class has several functions such as get weight which returns the weight between the node to which this list belongs and the node sent to the function in addition there is a function called hasNi 
which gets a number(key) and returns true if it is a neighbor of the node that holds this list of neighbors in addition there is a function that returns a collection Of the node keys that are neighbors to this node additionally has a function of removing a neighbor.
The third class is WGraph_DS
This class actually represents the graph The main structure that the class uses is hashMap because of its ability to perform contain and get at a fixed time This class has a number of functions
 which characterize a graph like adding and removing a node  connecting 2 nodes Returning a collection Of all the nodes in the graph and alsoReturning a collection  all the nodes that are neighbors of a particular vertex each graph also has a conunter of action counter of nodes and counter of edges. 
The forth calss is WGraph_Algo
This class is basically a class that implements algorithms on an unidirectional  weighted graph. The main algorithm that was used in the disease is the dijkstra algorithm.
This class has several functions:
Checking the minimum distance between 2 nodes and returning the weight, returning a list of the shortest route between 2 vertices, deep copying of a graph, initialization of a graph on which the class will actually work, saving a graph to a file and also restoring the graph from the file (load). .
In this class there are 2 more auxiliary functions that I implemented in order to make the Load more elegant.
Details of the runtimes of the algorithms can be found in the code itself


