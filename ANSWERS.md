# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

[A process is an independent program that has its own memory space and system resources, while a thread is a smaller unit of execution within a process that shares the same memory with other threads. Processes are more expensive to create and manage because each process requires separate memory and communication between processes is slower using inter-process communication (IPC).

Threads, on the other hand, are lightweight and faster because they share memory and resources. In this assignment, threads were used instead of processes because the simulation requires fast execution and frequent context switching. Using threads makes the Round-Robin scheduler more efficient and allows multiple processes to run concurrently with less overhead.]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

In Round-Robin scheduling, if a process does not finish within its assigned time quantum, it is placed back into the ready queue to continue execution later. The scheduler then selects the next process in the queue, ensuring that all processes get equal CPU time.

Example from my output:
P1 ran for 3000ms, remaining time: 2000ms
P1 is not finished → re-added to the ready queue

Explanation:
In this example, P1 did not complete its execution within the given time quantum, so it was re-enqueued at the end of the queue. This allows other processes to execute before P1 runs again. This behavior ensures fairness and prevents any single process from monopolizing the CPU.
---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**

1. New:
P1 is in the New state when the thread object is created but before the start() method is called.

2. Runnable:
P1 becomes Runnable after the start() method is called and is ready to be scheduled by the CPU.

3. Running:
P1 enters the Running state when the scheduler selects it and executes its run() method.

4. Waiting:
P1 enters the Waiting state when Thread.sleep() is used during execution, simulating processing time.

5. Terminated:
P1 reaches the Terminated state when its remaining time becomes zero and the execution is complete.

---

## Question 4: Real-World Applications

Example 1: Web Server

Description:
A web server is responsible for handling multiple client requests simultaneously, such as loading web pages, processing API calls, and managing user sessions.

Why Round-Robin works well:
Round-Robin scheduling ensures that each client request gets an equal share of CPU time, which improves system responsiveness. It prevents any single request from taking too long and blocking others, ensuring fairness. This makes the system more efficient and provides a better user experience, especially when many users are accessing the server at the same time.

---

Example 2: Time-Sharing Operating Systems

Description:
Modern operating systems run multiple applications at the same time, such as web browsers, text editors, and background services.

Why Round-Robin works well:
Round-Robin scheduling allows each application to receive a fair portion of CPU time, which prevents starvation and ensures smooth multitasking. It also provides predictable performance and keeps the system responsive, even when many processes are running concurrently. This is essential for maintaining a stable and user-friendly environment.
---

## Summary

**Key concepts I understood through these questions:**
1. The difference between threads and processes.
2. How Round-Robin scheduling ensures fairness.
3. The lifecycle of a thread.

**Concepts I need to study more:**
1. Thread synchronization.
2. Performance optimization in multithreading.
