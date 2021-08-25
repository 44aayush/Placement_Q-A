1. **What is a Process?**

   -> A process is an instance of a program in execution.

2. **What is a Thread?**

   -> A thread is a single sequence stream within a process. Because threads have some of the properties of processes, they are sometimes called lightweight processes.

3. * **Thread has it's own** - program counter (PC), a register set, and a stack space.
   * **Thread shares** - code section, data section, and OS resources like open files and signals. 

4. **What is Thrashing?**

   -> Thrashing is a situation when the performance of a computer degrades or collapses. Thrashing occurs when a system spends more time processing page faults than executing transactions.

5. **What is Belady's Anomaly?**

   -> An anomaly with some page replacement policies were increasing the number of page frames results in an increase in the number of page faults. Occurs in FIFO page replacement.

6. **What is Demand Paging?**

   -> The process of loading the page into memory on demand.

7. **What is Kernel?**

   -> A kernel is the central component of an operating system that manages the operations of computers and hardware. It basically manages operations of memory and CPU time. It is a core component of an operating system. Kernel acts as a bridge between applications and data processing performed at the hardware level using inter-process communication and system calls.

8. **What is a deadlock?**

   -> Deadlock is a situation when two or more processes wait for each other to finish and none of them ever finish.

9. **Deadlock happens due to?**

   * Mutual Exclusion
   * Hold and Wait
   * No Preemption
   * Circular Wait

10. **Methods for handling Deadlock?**

    * Deadlock Prevention or Avoidance - Banker's Algorithm
    * Deadlock detection and recovery
    * Ignore the problem altogether

11. **How does dynamic loading aid in better memory space utilization?**

    -> With dynamic loading, a routine is not loaded until it is called. This method is especially useful when large amounts of code are needed in order to handle infrequently occurring cases such as error routines.

12. **What are overlays?**

    -> The concept of overlays is that whenever a process is running it will not use the complete program at the same time, it will use only some part of it.

    The concept of overlays is that whenever a process is running it will not use the complete program at the same time, it will use only some part of it.

13. **What is caching?**

    -> The cache is a smaller and faster memory that stores copies of the data from frequently used main memory locations. 

14. * **Preemptive** - the process is interrupted in the middle of execution when higher priority one comes.
    * **Non-Preemptive** - the CPU is allocated to the process till it terminates or switches to waiting for state.

15. * **Zombie Process** - A process that has finished the execution but still has an entry in the process table to report to its parent process is known as a zombie process
    * **Orphan Process** - A process whose parent process no more exists i.e. either finished or terminated without waiting for its child process to terminate is called an orphan process.
    * **Starvation** - A process does not get the resources it needs for a long time because the resources are being allocated to other processes. 
    * **Aging** - A technique to avoid starvation in a scheduling system. It works by adding an aging factor to the priority of each request.

16. **What is concurrency?**

    -> A state in which a process exists simultaneously with another process than those it is said to be concurrent.

17. **Problems related to concurrency**

    * Non-Atomic
    * Race Condition
    * Blocking
    * Starvation
    * Deadlock

18. **What is Buffer?**

    -> A buffer is a memory area that stores data being transferred between two devices or between a device and an application.

19. **What are the different kinds of operations possible on Semaphores?**

    * wait()
    * signal()

20. * **Micro Kernel** - It is a minimal OS that executes only important functions of OS. It only contains a near-minimum number of features and functions that are required to implement OS. 
    * **Monolithic Kernel** - It is an OS architecture that supports all basic features of computer components such as resource management, memory, file, etc.  
