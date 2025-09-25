🚀 Queue in C++ 

A Queue is a linear data structure that operates on the FIFO (First In, First Out) principle. It is widely used in programming for managing tasks, buffering data, and scheduling processes.
🔄 Core Operations
Operation	Description
enqueue()	Adds an element to the rear of the queue
dequeue()	Removes an element from the front of the queue
display()	Shows all elements from front to rear
📌 Characteristics

    Linear Structure: Elements are arranged in a sequence.

    Two Pointers: front (deletion point) and rear (insertion point).

    Fixed Size: In static queues (array-based), size is predefined.

    Dynamic Size: In linked list-based queues, size grows as needed.

🧰 Implementation Types

    Array-Based Queue

        Simple to implement

        Limited by fixed size

        May lead to unused space after multiple dequeues

    Linked List-Based Queue

        Dynamic memory allocation

        No overflow unless memory is full

        Efficient for frequent insertions and deletions

    Circular Queue

        Optimizes space usage

        Rear wraps around to front when space is available

    Priority Queue

        Elements are dequeued based on priority, not order

    Deque (Double-Ended Queue)

        Insertion and deletion allowed at both ends

🧠 Use Cases

    CPU Scheduling: Round-robin algorithms

    Print Queue: Managing print jobs

    Breadth-First Search (BFS): Graph traversal

    Call Center Systems: Managing incoming calls

    Streaming Buffers: Handling real-time data

✅ Advantages

    Maintains order of execution

    Simple and intuitive logic

    Efficient for task management

    Forms the basis of many system-level algorithms
