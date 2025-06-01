# Module-14: Data Structures and Algorithms in C
## Aim:
To implement and understand various data structures and algorithms in C, including circular queues, deques, priority queues (max-heaps), and the Round Robin scheduling algorithm.

## Contents:

### 1. Circular Queue Operations
Aim:
To perform insertion and deletion operations on a circular queue and handle the wrap-around condition.

#### Algorithm:
Initialize front and rear to -1.

For insertion:

Check if the queue is full.

If not, insert the element at the rear and update the rear pointer.

For deletion:

Check if the queue is empty.

If not, remove the element from the front and update the front pointer.

#### Program:
Refer to main_function_of_a_circular_queue.md in the repository.

#### Output:
Demonstrates the state of the queue after each insertion and deletion operation.

#### Result:
Successfully implemented circular queue operations with proper handling of edge cases.

### 2. Deque Operations
Aim:
To implement insertion at the rear end of a double-ended queue (deque).

#### Algorithm:
Check if the deque is full.

If not, insert the element at the rear and update the rear pointer.

If the rear reaches the end, wrap around to the beginning if space is available.

#### Program:
Refer to addRear_function_in_deque.md in the repository.

#### Output:
Displays the deque after inserting elements at the rear.

#### Result:
Successfully implemented rear insertion in a deque with wrap-around handling.

### 3. Priority Queue (Max-Heap)
Aim:
To maintain the max-heap property after deletion in a priority queue.

#### Algorithm:
Replace the root of the heap with the last element.

Reduce the size of the heap by one.

Call the heapify function to restore the max-heap property:

Compare the current node with its left and right children.

Swap with the largest if necessary and continue heapifying.

#### Program:
Refer to heapify_function_in_priority_queue.md in the repository.

#### Output:
Shows the state of the heap after deletion and re-heapification.

#### Result:
Successfully maintained the max-heap property after deletions.

### 4. Round Robin Scheduling Algorithm
Aim:
To calculate the Waiting Time (WT) and Turnaround Time (TAT) for each process using the Round Robin scheduling algorithm.

#### Algorithm:
Input the number of processes, their arrival times, and burst times.

Input the time quantum.

Initialize the remaining burst times and time.

Loop through the processes in a round-robin manner:

If a process has remaining burst time greater than the time quantum, execute it for the time quantum.

If the remaining burst time is less than or equal to the time quantum, execute it completely.

Update the waiting time and turnaround time accordingly.

Calculate average WT and TAT.

#### Program:
Refer to round_robin_scheduling.md in the repository.

#### Output:
Displays the WT and TAT for each process along with their averages.

#### Result:
Successfully implemented the Round Robin scheduling algorithm with accurate computation of WT and TAT.

## Conclusion:
This module provides hands-on experience with fundamental data structures and algorithms in C, reinforcing concepts through practical implementation.

