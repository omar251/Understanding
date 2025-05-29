## Multiprocessing

This section explores multiprocessing in Python, a way to achieve true parallelism by running multiple processes, each with its own interpreter and memory space.  This bypasses the limitations imposed by the Global Interpreter Lock (GIL).

*   `intro.py`: Introduces the basic concepts of multiprocessing, including creating processes using the `multiprocessing` module, starting and stopping processes, and using process pools for efficient parallel execution.  Explains the differences between multiprocessing and threading.
*   `concurrent_queues.py`: Shows how to use queues for inter-process communication, enabling processes to share data safely.
*   `mutli_pool.py`: Demonstrates the use of the `Pool` object for parallel processing, potentially illustrating how to apply a function to multiple input values concurrently.

The objective is to understand how to leverage multiprocessing to take advantage of multiple CPU cores, improving performance for CPU-bound tasks that are not limited by the GIL.  This section emphasizes techniques for efficient inter-process communication and coordination.
