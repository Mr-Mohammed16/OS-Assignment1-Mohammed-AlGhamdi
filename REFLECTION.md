# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:**

[In this assignment, I learned the fundamental concepts of multithreading and how threads can be used to execute multiple tasks concurrently within the same program. I understood how to create threads using the Runnable interface and how each thread represents an independent unit of execution. I also learned about the different thread states such as New, Runnable, Running, Waiting, and Terminated, and how a thread transitions between these states during execution.

Additionally, I gained practical experience with methods like Thread.start(), Thread.sleep(), and Thread.join(), and how they control thread behavior. One important concept I learned is how threads share memory, which makes communication faster compared to processes. I was also able to see how multithreading is used in scheduling algorithms like Round-Robin to ensure fairness between tasks. Overall, this assignment helped me understand how threads work in real systems and how they improve performance and responsiveness.
]

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:**

[The most challenging part of this assignment was understanding the existing starter code and how the scheduling simulation works. At the beginning, it was difficult to follow the logic of how processes are managed, how threads are created, and how the ready queue operates. In particular, implementing the waiting time feature was quite challenging because it required accurate time tracking and correct placement of calculations within the code.

Another difficulty was ensuring that the new features did not break the existing functionality of the program. I had to be careful when modifying the Process class and the SchedulerSimulation class. Debugging issues related to incorrect outputs also took time and effort. Overall, the complexity of combining multithreading with scheduling logic made this assignment difficult to understand and implement.]

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:**

[I overcame these challenges by breaking the problem into smaller parts and focusing on one feature at a time. First, I carefully read the code multiple times to understand how each part works, especially the scheduling loop and thread execution. I also used debugging techniques such as printing intermediate values to track how the program behaves during execution.

In addition, I referred to lecture materials and online resources to better understand concepts like thread lifecycle and time management. When implementing features, I tested the program after each modification to ensure everything was working correctly. This step-by-step approach helped me identify and fix errors more efficiently. Over time, I became more comfortable working with the code and understanding how multithreading works in practice.
]

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:**

[Multithreading is widely used in real-world applications to improve performance and responsiveness. For example, web browsers use multithreading to load multiple tabs at the same time, allowing users to browse different websites without delays. Each tab can run in a separate thread, which ensures smooth and efficient execution.

Another example is in video games, where threads are used to handle different tasks such as rendering graphics, processing user input, and managing physics calculations simultaneously. This allows the game to run smoothly without lag. In this assignment, I saw how Round-Robin scheduling distributes CPU time fairly between processes, which is similar to how operating systems manage multiple applications. These concepts are essential for building efficient and responsive software systems.
]

---

## Additional Reflections (Optional)

### What would you like to learn more about?

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?

[Rate yourself and explain: Beginner / Intermediate / Confident]

[Explain your rating - what do you understand well? What needs more practice?]

---

### Feedback on the assignment

[This assignment was very difficult and challenging to understand and implement. The concepts of multithreading and scheduling required a deep level of understanding, and the starter code was complex to follow at first. It took significant time and effort to fully understand how the system works and to correctly implement the required features. Despite the difficulty, it was a valuable learning experience that helped me improve my problem-solving skills and understanding of operating systems concepts.]
