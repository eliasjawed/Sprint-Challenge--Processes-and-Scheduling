1. B - Considering 32 KB of memory is allocated and there are two processes
the memory addresses can exist on anywhere from 0 - 64,000 as they don't need to be in any specific order/sequence (like in answer A). 


2. **Created/New**: 
When it's first created, it is in a Created or New state (interchangeable) - awaiting the next state (Ready). Has yet to be approved (or alternatively delayed) by the scheduler. 

**Ready**
The process has reached primary storage ("main memory"/"internal memory") and is ready to be "run" on the CPU. 

**Running**
When a ready process is chosen, the instructions of the process are executed by the CPU, this state can be in two substates - Kernel mode (which allowsaccess to all hardware) and User mode (which is a less 'intrusive' state)

**Blocked**
The blocked state is common for when a process can no longer carry on with the resources it has access to. For instance, a process might require additional user input to execute correctly.

**Terminated**
The terminated state implies that the process is no longer running, which could mean that it has carried out the instructions or that the process is no longer needed and "terminated". 


3. printf takes 0.001112ms per iteration whilst write takes 0.01534ms per iteration. Thus printf is much faster.

4. Because printf uses a buffer so it reduces the number of "write" calls that are required. 

