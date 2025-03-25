Adaptive OS Scheduler for Real-Time Systems
Project Overview
This project focuses on developing an adaptive operating system scheduler designed specifically for real-time systems. The scheduler dynamically adjusts task priorities to optimize system performance based on workload and deadlines. It aims to provide an efficient scheduling mechanism that ensures real-time tasks meet their constraints while maintaining overall system efficiency.

Features
Dynamic Priority Adjustment: The scheduler modifies task priorities in real time based on system load and deadlines.

Real-Time Scheduling: Ensures that tasks are scheduled in a way that meets strict timing constraints.

Workload Adaptation: The system adapts dynamically to changes in workload, improving performance and resource utilization.

Interactive User Interface: A simple and intuitive web-based interface allows users to explore and understand the scheduling process.

Implemented Scheduling Algorithms
Rate-Monotonic Scheduling (RMS)
Rate-Monotonic Scheduling is a fixed-priority algorithm where tasks with shorter execution cycles are assigned higher priority. This approach is well-suited for systems with periodic tasks that do not change frequently. It ensures predictability and guarantees deadlines when system utilization conditions are met.

Earliest Deadline First (EDF)
Earliest Deadline First is a dynamic priority scheduling algorithm that assigns priority based on the task’s deadline. Tasks with the earliest deadlines are executed first. This approach is more flexible than RMS and can adapt to varying workloads, making it suitable for systems with changing deadlines.
