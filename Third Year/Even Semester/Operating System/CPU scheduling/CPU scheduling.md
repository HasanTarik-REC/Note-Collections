### Chapter 5 (CPU Scheduling)

### **<br/>Define CPU scheduler.**
A CPU scheduler is a vital part of an operating system that acts as a traffic controller for the central processing unit (CPU).
It decides  the order and prioritizes in which various processes are executed on the CPU.
This is necessary because a CPU can only handle one task at a time. The CPU scheduler aims to make the system efficient, fast, and fair.
### **<br/>Types of CPU Scheduling Algorithm.**
- Preemptive
    - Shortest Job First Scheduling
    - Priority
    - Round Robin
- Non-Preemptive<br/>
    - First Come First Served Scheduling
    - Shortest Job First Scheduling
    - Priority
    - Multilevel<br/>
### **<br/>CPU Scheduling Criteria**
CPU scheduling algorithms rely on various criteria to determine how to prioritize and allocate CPU time to different processes.  These criteria influence how efficiently and fairly the system runs. Some key CPU scheduling criteria are mentioned below:<br/>
- `CPU Utilization:` This measures how effectively the CPU is being used. Ideally, the scheduler aims for high CPU utilization to minimize idle time.<br/>
- `Throughput:` This refers to the number of processes completed per unit time. A good scheduler should maximize throughput for efficient task completion.<br/>
- `Turnaround Time:` This is the total time taken by a process, from submission to completion. The scheduler strives to minimize turnaround time for faster overall processing.<br/>
- `Average Waiting Time:` This is the time a process spends waiting for the CPU after it's ready to run. The scheduler aims to keep waiting time low to prevent processes from being starved of resources.<br/>
- `Average Response Time:` This is the time it takes for a process to first respond after submitting a request. A good scheduler minimizes response time for a more responsive user experience.<br/>
