# Implementation of Symtable using Linked List and Hash Table

This project implements a symbol table using a combination of linked list and hash table data structures.

## Functions

### SymTable_new
- Allocates memory for the symbol table.

### SymTable_getLength
- Returns the length of the linked list.

### SymTable_free
- Deletes the memory allocated for the symbol table.

### SymTable_get
- If the key is present in the symbol table, return the corresponding value; otherwise, return a null pointer.

### SymTable_contains
- Returns 1 if the key is present in the linked list; otherwise, return 0.

### SymTable_put
- Checks if the key is present. If not found, creates a new node with the respective key and value and returns 1; otherwise, returns 0.

### SymTable_map
- Applies a given function to each node in the symbol table, passing additional data.

### SymTable_remove
- If the provided key is present in the linked list, deletes the node and returns the value it holds; otherwise, returns null.

### SymTable_replace
- If the key is present in the linked list, replaces the old value with the new value and returns the old value; otherwise, returns null

We have chosen to implement the symbol table using a hash table due to its superior efficiency over a linked list. By employing a hash function, we generate keys that determine the index where nodes are stored within the table. This strategy streamlines access to elements as we can directly locate items by their respective indices, resulting in significant time savings.




