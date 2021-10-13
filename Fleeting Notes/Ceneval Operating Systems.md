# Ceneval Operating Systems
Created: 2021-10-11 14:47
- Operating Systems handle system resources; the execution of programs and acts as the middleman between computer and machine
- Admin mode is used for creating new processes; writing on disk; disabling interruptions
- **offline processing** principal contribution is the synchronization of I/O jobs with other computations
- nT + nTk/10 + nTp
- STATES
	- ready = waiting for a processor to be assigned
	- waiting = waiting for an event
	- terminated = previous state was running and current state isn't ready or waiting
	- running = the process that is running at the present moment at least on 1 processor
	- new = Waiting to be admitted for the first time on the ready state
	- blocked = It has finished its execution but its waiting a device to send needed information
	- zombie = Execution has stopped, but the process hasn't been removed from the operating system
- system calls are the interface between a process and the operating system OR the interface between a process and the kernel
`so1.txt`
`1,2,3,a,b`
write on console
`$cat so1.txt so1.txt so1.txt`
console writes this back
`1,2,3,a,b 1,2,3,a,b 1,2,3,a,b`

the  pipe operator `a|b` executes a and sends its results to b  
the `head -n 4` gives back the last 4 lines of a block of text that has been piped to it

![[Pasted image 20211011175654.png]]
## Reference
1. 