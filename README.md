# POSIST-ROUND-2
this repository is the solution to the coding problem given to us during the second round of Posist campus recruitment at JIIT sector 62.

Implemented : 
1. A structure called "NodeData" that takes OwnerId, value and OwnerName
2. A structure called "Node" that has following members: 
    -> a float "timestamp" that gets it's value from getTimestamp() function
    -> a NodeData variable "Data"
    -> a NodeNumber that is unique to all nodes and is auto-incremented
    -> a NodeId that is the address of the current node
    -> a refId that has the address of the parent node
    -> a vector of Node type pointers pointing to children nodes called childRefId
    -> a genesisId that takes the value of root node
3. A function insertNode() that checks if the current node's value is not greater than remaining sum left of parent node, else return -1(error).
4. A getTimestamp() function that generates timestamp using library ctime.
