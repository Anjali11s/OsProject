Adaptive OS Scheduler for Real-Time Systems.
Project Overview
The Adaptive OS Scheduler for Real-Time Systems dynamically adjusts task priorities to optimize performance based on workload and deadlines. It provides an interactive simulation of real-time scheduling algorithms, ensuring efficient task execution.

🌟 Features
🔹 Dynamic Priorities – Automatically adjusts task priorities based on system workload.
🔹 Real-Time Scheduling – Schedules tasks with strict deadlines and real-time constraints.
🔹 Workload Adaptation – Adjusts dynamically for enhanced system efficiency.
🔹 User-Friendly Interface – Clean UI built with HTML, Tailwind CSS, and JavaScript.

🧮 Implemented Scheduling Algorithms
📌 Rate-Monotonic Scheduling (RMS)
Assigns higher priority to tasks with shorter periods.

Best for fixed, periodic tasks where deadlines are predictable.

Ensures deadline guarantees if CPU utilization conditions are met.

📌 Earliest Deadline First (EDF)
Prioritizes tasks with the earliest deadlines.

Works well for dynamic workloads with varying deadlines.

More flexible than RMS but requires efficient scheduling overhead.
