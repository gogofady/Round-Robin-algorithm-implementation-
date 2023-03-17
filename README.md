# Round-Robin-algorithm-implementation-
Round Robin algorithm implementation with java
## Round Robin is a CPU scheduling algorithm where each process is assigned a fixed time slot in a cyclic way. It is basically the preemptive version of First come First Serve CPU Scheduling algorithm. 

## Round Robin CPU Algorithm generally focuses on Time Sharing technique. 
The period of time for which a process or job is allowed to run in a pre-emptive method is called time quantum. 
Each process or job present in the ready queue is assigned the CPU for that time quantum, if the execution of the process is completed during that time then the process will end else the process will go back to the waiting table and wait for its next turn to complete the execution.
 
## Characteristics of Round Robin CPU Scheduling Algorithm:
It is simple, easy to implement, and starvation-free as all processes get fair share of CPU.
One of the most commonly used technique in CPU scheduling as a core.
It is preemptive as processes are assigned CPU only for a fixed slice of time at most.
The disadvantage of it is more overhead of context switching.

![My_Image](RRphoto.png)
