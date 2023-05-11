# What are Linked Lists?
## A linked list is a collection of nodes, where each node contains data and a reference to the next node in the list. The first node in the list is called the head, and the last node is called the tail. The tail node's reference points to a null value, indicating the end of the list.

## Each node in a linked list contains two parts: data and a pointer to the next node. The data part can be any type of data, such as an integer, string, or object. The pointer part is a reference to the next node in the list.

## There are two types of linked lists: singly linked lists and doubly linked lists. In a singly linked list, each node contains a reference to the next node in the list. In a doubly linked list, each node contains a reference to both the next node and the previous node in the list.



# Linked List - A data structure that contains nodes that links/points to the next node in the list.
# Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
# Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
# Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
# Next - Each node contains a property called Next. This property contains the reference to the next node.
# Head - The Head is a reference of type Node to the first node in a linked list.
# Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.