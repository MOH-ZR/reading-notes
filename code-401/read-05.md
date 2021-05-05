# Linked Lists
A Linked List is a data structure consists of sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link.  

There are three types of Linked List:
1. singly linked list
    * there is only one reference, and the reference points to the Next node in a linked list.
2. doubly linked list
    * there is a reference to both the Next and Previous node.
3. circular linked list
    * there is a reference form the last node to the first.


**Node:** the individual iten tha conyaic the data  
**Head:** reference to the first node  
**Next** reference to the next node  
**Current:** reference to the node that is currently being looked at  
**Tail** reference to the last node  


**Traversal**
The pseudo-code for an Includes is as so:
```
ALGORITHM Includes (value)
// INPUT <-- integer value
// OUTPUT <-- boolean

  Current <-- Head

  WHILE Current is not NULL
    IF Current.Value is equal to value
      return TRUE

    Current <-- Current.Next

  return FALSE
```

**Time complexity:** O(n)
**Space cpmplexity:** O(1)

Operations on linked list:
1. adding a node
2. delete a node
3. search a node