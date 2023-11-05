# HPC-Assignment
Certainly! Here's a sample README file for your Java program:

# Binary Search Tree (BST) Testing

## Introduction

This Java program, "BST_Test," is designed to test the performance and functionality of a binary search tree (BST) data structure using a multithreaded approach. It allows you to simulate various operations (insertion, deletion, and contains) on the BST while measuring the throughput and total operations performed.

## Program Components

- `BST_Test.java`: The main class that controls the program's execution.
- `BinarySearchTree.java`: The class that defines the binary search tree data structure and its associated methods.
- `Node`: A static inner class within `BinarySearchTree` to represent the nodes of the tree.
- `ThreadID.java`: A utility class to retrieve the current thread's ID.

## Setup

To compile and run the program, follow these steps:

1. Ensure you have Java installed on your system.
2. Compile the program using the following command:
   ```bash
   javac BST_Test.java
   ```
3. Run the program with the appropriate arguments, which include the number of threads, prefill size, and workload:

   ```bash
   java BST_Test [num_threads] [prefillSize] [workload]
   ```

   - `[num_threads]`: The number of threads to be used for parallel testing.
   - `[prefillSize]`: The size of the initial tree.
   - `[workload]`: A string specifying the operation percentages (e.g., "30C-60I-10D" for 30% contains, 60% insert, and 10% delete operations).

## Running the Program

The program will perform the specified operations on the BST using multiple threads, measuring the total operations and throughput. The results will be displayed in the console.

## Example Usage

```bash
java BST_Test 4 1000 30C-60I-10D
```

This command will run the program with 4 threads, an initial tree of 1000 nodes, and a workload of 30% contains, 60% insert, and 10% delete operations.

## Output

The program will provide output in the following format:

```
BST_Test:num_threads:4:totalOps:2400 :throughput:0.241
```

- `num_threads`: The number of threads used.
- `totalOps`: The total number of operations performed.
- `throughput`: The throughput in operations per second.

## Conclusion

This program allows you to evaluate the performance of a binary search tree in a multithreaded environment. By specifying the number of threads and workload, you can measure the efficiency and functionality of the tree for various use cases.

#Graphs plotted against throughput by varying no.of threads for different locks 
![image](https://github.com/Sumedareddy/HPC-Assignment/assets/145221872/052cc59e-060a-4c9d-a919-6fe0885787a3)

![image](https://github.com/Sumedareddy/HPC-Assignment/assets/145221872/63da5c8f-9df4-4edd-bb59-2c5eee79a369)

![image](https://github.com/Sumedareddy/HPC-Assignment/assets/145221872/d00f7263-5b05-48f1-9ff3-e0632ba2841c)

![image](https://github.com/Sumedareddy/HPC-Assignment/assets/145221872/e6765ad2-8467-4e11-b1ee-6b0671d34c70)

![image](https://github.com/Sumedareddy/HPC-Assignment/assets/145221872/46035158-43e2-48a6-94fe-50875d9b903d)

![image](https://github.com/Sumedareddy/HPC-Assignment/assets/145221872/989ce6f0-f32b-4c37-9013-657b44ab3abe)



