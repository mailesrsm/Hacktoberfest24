# Stacks in C++

- **Definition:** A stack is a linear data structure that follows the Last In First Out (LIFO) principle.
- **Basic Operations:**
  - Push: Add an element.
  - Pop: Remove the top element.
- **Implementation:**
  ```cpp
  class Stack {
      private:
          std::vector<int> arr;
      public:
          void push(int x) { arr.push_back(x); }
          void pop() { arr.pop_back(); }
          int top() { return arr.back(); }
  };
  ```
