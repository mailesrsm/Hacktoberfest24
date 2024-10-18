# Queues in C++

- **Definition:** A queue is a linear data structure that follows the First In First Out (FIFO) principle.
- **Basic Operations:**
  - Enqueue: Add an element.
  - Dequeue: Remove the front element.
- **Implementation:**
  ```cpp
  class Queue {
      private:
          std::vector<int> arr;
      public:
          void enqueue(int x) { arr.push_back(x); }
          void dequeue() { arr.erase(arr.begin()); }
          int front() { return arr.front(); }
  };
  ```
