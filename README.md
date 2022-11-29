# Shortest Path Finder For Airways

## Abstract
This project includes a program that determines the quickest route between airports. The shortest route or path between a source node and a destination node in a network must be determined in order to solve the Shortest Path Problem. In this work, we used Dijkstra's Algorithm to find the shortest path between two points in an airline network. Each defined edge must have a value that is not negative. One of the most significant difficulties airlines face is moving people and commercial goods between large cities in a shorter amount of time and at a cheaper cost. Using a simulation environment, we are developing the Dijkstra algorithm to resolve this challenging issue and to update it to see the shortest path from the origin node (city) to the destination node (other cities). The experimental findings demonstrate the simulation's capacity to identify the most economical route in the smallest amount of time (seconds) to identify the most practical route for flights in the shortest amount of time and regardless of the defined number of ports on the map.

## Introduction
Pathfinding is the plotting by the computer program of the shortest route between source and destination. One of the popular applications is resolving mazes. Here, Dijkstra is used as a major foundation for finding the shortest path on a weighted path. The shortest path problem in graph theory, which deals with how to determine the route that best meets certain criteria (shortest, cheapest, fastest, etc.) between aircraft in a large network, is closely related to pathfinding. At its core, a path-finding method searches a graph by starting at one vertex and exploring neighbouring nodes until a destination node is reached, usually with the intention of finding the cheapest route.  
This project is a model which has a real-life implementation of the traversing paths of connected flights across India. This is a user-friendly GUI project with the liberty of editing the cost and time-efficient values to help the user work on what they prefer. Sometimes we need to travel to a place faster and sometimes economical travel is more efficient. This project is reliable for finding the shortest path distances between airports to see and compare the best possible routes for passengers or for the transportation of exquisite goods.
We’ve used Priority Queues for the implementation of Dijkstra because priority queues are best when we have to arrange the values. In the Graphical user interface, we have imported the Map of India which has the marked airports for easy selection of source & destination. We can make all the possible nodes by just mouse clicking at that location. The factual values are added as the edges from each node in the text field. The user can select the source & destination and now the work is done. After clicking the button FIND SHORTEST PATH!, the path which is shortest and most convenient to the user is highlighted. 


![unnamed](https://user-images.githubusercontent.com/78655015/204598638-6e07472c-1f58-487d-9ec0-6b464ea90d5b.png)


# Problem Statement
The recurring problem of in-flight customer wait time and the rise in the cost of airfare.

# Objectives

● It is used for finding the shortest path of flights using the Dijkstra algorithm which will save Time and Cost for the customer.
● To study, determine and identify the shortest path in a network used for the organization of Flights.
● We utilized a graph to depict a map, where the vertices are cities and the edges are the routes between the cities. The graph will be directed if the routes are one-way; otherwise, it will be undirected.


# DATA STRUCTURES
## ADJACENCY LISTS: 
By far the most common data structure for storing graphs is the adjacency list. It is an array of lists, each containing the neighbors of one of the vertices or the out-neighbors if the graph is directed.
An adjacency list is an array of linked lists that represents a graph. The array's index corresponds to a vertex where each element in its linked list corresponds to different vertices that form an edge with a vertex.
Due to the fact that we only need to store the values for the edges, an adjacency list is efficient in terms of storage. It also makes it easier to find all the vertices adjacent to a vertex.


## PRIORITY QUEUES: 
A priority queue in Java is a special type of queue wherein all the elements are ordered as per their natural ordering or based on a custom Comparator supplied at the time of creation.
The front of the priority queue contains the least element according to the specified ordering, and the rear of the priority queue contains the greatest element.
So when you remove an element from the priority queue, the least element according to the specified ordering is removed first.

## HEAP:
A heap is a complete binary tree, and the binary tree is a tree in which the node can have utmost two children.A complete binary tree is a binary tree in which all the levels except the last level, i.e., leaf node should be completely filled, and all the nodes should be left-justified.

## ARRAY LIST: 
Array List is a class of Java Collection framework. It uses a dynamic array for storing the objects. It is much similar to Array, but there is no size limit in it. We can add or remove the elements whenever we want. We can store the duplicate element using the ArrayList; It manages the order of insertion internally.

# Algorithms
## Dijkstra's Algorithm:
A Dutch computer scientist, Edsger Dijkstra, 1959, proposed an algorithm that can be applied to a weighted graph. The graph can either be directed or undirected with the condition that the graph needs to embrace a non-negative value on every edge. He named this algorithm “Dijkstra’s Algorithm” at his name.
An algorithm used for finding the shortest distance, or path, from starting node to the target node in a weighted graph is known as Dijkstra’s Algorithm.
Dijkstra's algorithm makes use of the weights of the edges to find the path that minimizes the total distance (weight) between the source node and all other nodes. This algorithm is also known as the single-source shortest path algorithm.

## METHODOLOGY


## Applications
● This project can be used in a more defined and well rounded Flight Routing Management System.
● Project can be used in Air traffic flow management. (It will suggest the different routes that can be followed to reach a destination which have less traffic) 
● The target beneficiaries of the proposed methodology are the people who need to travel to destinations faster for business purposes. It is also helpful in emergencies as it will reduce the customer wait time and also reduce the delays in flights.
● Vehicle Routing Problem, the goal is to find optimal routes for vehicles visiting a set of locations(cities).


## Conclusion

The main goal of the project is to use it in airlines in the country to help reduce the time. By improving on-time performance, decreasing customer wait times, increasing the working availability of aircraft and ground assets, and assisting employees in making the most efficient use of their valuable time. This will help to significantly reduce costs while improving the experience of both employees and customers.


## References
[1] Banerjee, A. and Kumar, P., 2022. Review of Shortest Path Algorithms. International Journal of Computer Science and Mobile Computing, 11(4), pp.1-8.
[2] Salem, I., Mijwil, M., Abdulqader, A. and Ismaeel, M., 2022. Flight-schedule using Dijkstra's algorithm with comparison of route findings. International Journal of Electrical and Computer Engineering (IJECE), 12(2), p.1675.
[3] Ö. O. Dursun and A. Özger, “Multi-depot heterogeneous fleet vehicle routing problem with time windows: Airline and Roadway Integrated Routing,” International Journal of Industrial Engineering Computations, vol. 13, no. 3, pp. 435–456, 2022. 



