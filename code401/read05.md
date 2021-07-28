## What is a Linked List

- Linked List - A data structure that contains nodes that links/points to the next node in the list.

- Singly - Singly refers to the number of references the node has.

- Doubly - Doubly refers to there being two (double) references within the node.

- Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.

- Next - Each node contains a property called Next. This property contains the reference to the next node.

- Head - The Head is a reference of type Node to the first node in a linked list.

- Current - The Current is a reference of type Node to the node that is currently being looked at.

- traverse through a linked list :
Current: is node that will tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end.

- When constructing your code, a few things to keep in mind :

When making your Node class, consider requiring a value to be passed in to require that each node has a value.

When making a Linked List, you may want to require that at least one node gets passed in upon instantiation. This first node is what your Head and Current will point too.

- linear data structures:
which means that there is a sequence and an order to how they are constructed and traversed.

- non-linear data structures:
items dont have to be arranged in order, which means that we could traverse the data structure non-sequentially.