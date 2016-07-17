###Spider Algos Project

This project is for scheduling of the processes. It also takes care of processing multiple operations at the same time.<br />
The task scheduling is done by three processes:

**First Come First Serve**  
**Priority Scheduling**  
**Shortest Job First** 

The user is required to select which type of scheduling he wants.

####User documentation for FCFS:

+ First-come, first-served (FCFS) – is a service policy whereby the requests of customers or clients are attended to in the order that they arrived,
 without other biases or preferences.

+ The user is required to provide the following input:
  - The no of operations that are to be performed.
  - The overall memory available to the processor
  - The burst time, arrival time and the memory requirement for each process.

+ The output is given in the following manner:
  - Time, Process id (for example 4,P2) means that the process has begun at the given time(ie P2 has begun at time 4).
  - Process id, Time (P2,7) means that the process gets over by given time(ie P2 gets over by time 7).
  - Arrow mark symbol(->) is used to seperate two processes.

####User documentation for Priority Scheduling:

+ Priority scheduling is a method of scheduling processes based on priority. In this method, the scheduler chooses the tasks to work as per the priority.

+ The user is required to provide the following input:
  - The no of operations that are to be performed.
  - The burst time, priority and the memory requirement for each process.
  - The overall memory available to the processor.

+ The output is given in the following manner:
  - Time, Process id (for example 4,P2) means that the process has begun at the given time(ie P2 has begun at time 4).
  - Process id, Time (P2,7) means that the process gets over by given time(ie P2 gets over by time 7).
  - Arrow mark symbol(->) is used to seperate two processes.
  - If two processes start at the same time, they are separated by a comma(',').
