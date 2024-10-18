# Linked Lists in C++

- **Definition:** A linked list is a linear data structure where elements are stored in nodes, each pointing to the next node.
- **Node Structure:**
  ```cpp
  struct Node {
      int data;
      Node* next;
  };
  ```
- **Example of Creating a Linked List:**
  ```cpp
  Node* head = new Node();
  head->data = 1;
  head->next = nullptr;
  ```
