# Doubly-linked-list-Library-
I have been created  my own the double linked list, 
# Generic Doubly Linked List (C++)

A lightweight, efficient, and generic **Doubly Linked List** data structure implemented in C++ using Templates. This implementation supports standard sequential operations along with index-based node manipulation.

## Features

- **Generic Data Type:** Built using C++ Templates (`template <class T>`) to support any data type (int, string, custom classes, etc.).
- **Dynamic Size Management:** Automatically tracks the size of the list in $O(1)$ time complexity.
- **Node Navigation:** Every node maintains pointers to both its `next` and `prev` neighbors for bi-directional traversal.

## Supported Operations

### 📥 Insertion
- `InsertAtBeginning(T value)`: Adds a new node at the start of the list.
- `InsertAtEnd(T value)`: Adds a new node at the end of the list.
- `InsertAfter(Node* currentNode, T value)`: Inserts a node after a specific node pointer.
- `InsertAfter(int Nodeindex, T newValue)`: Inserts a node after a specific index.

### 🗑️ Deletion
- `DeleteFirstNode()`: Removes the head node.
- `DeleteLastNode()`: Removes the tail node.
- `DeleteNode(Node* nodeToDelete)`: Deletes a specific node from the list.
- `Clear()`: Deletes all nodes and frees memory.

### 🔍 Search & Retrieval
- `Find(T value)`: Searches for a node by its value and returns its pointer.
- `GetNode(int index)`: Retrieves a pointer to the node at a specific index.
- `GetItem(int index)`: Returns the value stored at a specific index.

### 🛠️ Utilities
- `UpdateItem(int index, T new_value)`: Updates the value of a node at a given index.
- `Reverse()`: Reverses the entire linked list in place.
- `Size()`: Returns the total number of elements.
- `IsEmpty()`: Checks if the list is empty.
- `PrintList()`: Prints all elements sequentially.
