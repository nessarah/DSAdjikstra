# DSAdjikstra
the basic algorithm and the modified version-using pairing heap

- Basic Algorithm
The Dijkstra algorithm is employed in a single source routing, and the path is determined node by node by identifying the minimum adjacent node on each circulation. The fundamental operation of this algorithm is to find the minimum adjacent node, which can be accomplished using the heap technique. This operation is quite simple to do, as it cannot end until all of the heap properties are in order because an operation on a heap has the potential to damage one of the properties. However, the concern of the Dijkstra algorithm is that it takes too long to traverse the node table, remove the minimum node, and update the node table. 

- Modified Algorithm using Pairing Heap
Thus, to increase the effectiveness of the Dijkstra algorithm, the Pairing heap that is constructed by the Pairing heap nodes is built. Along with the queue elements, each heap node also contains the previous pointer, left child pointer, and right child pointer. A pairing heap can be operated on with the commands “merge”, “insert”, and “delete_min”. Every node receives a heap pointer, but memory space is not allocated in advance. When the algorithm reached this network node, the heap node was dynamically built. 

-Why it was modified that way?
Because the algorithm and memory usage are both efficient with this approach. Apart from that the time complexity is much better if using pairing heap compared to minheap and binaryheap.

![image](https://user-images.githubusercontent.com/95832485/213965743-753893b7-3ae8-4a23-86bb-2f8e13815a0e.png)


Resource :
Improved Dijkstra Algorithm Based on Pairing Heap. An Improved Dijkstra Algorithm Based on Pairing Heap. (2012). Beijing Institute of Petrochemical Technology College of Information Engineering. Retrieved January 15, 2023, from
https://ieeexplore.ieee.org/abstract/document/6406028  
