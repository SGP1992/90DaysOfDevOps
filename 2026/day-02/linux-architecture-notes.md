
The core components of Linux (kernel, user space, init/systemd)
1.	Kernel
2.	System Libraries
3.	Shell
4.	Hardware Layer
5.	System Utilities (User-Space Tools)

1. Kernel
The kernel is the heart of Linux. 
The kernel is the core of the Linux operating system and that manages hardware resources and controls communication between software and hardware.
kernel  Allocates CPU time, Assigns memory, Handles disk/network I/O

2. System Libraries
System libraries provide essential functions that allow applications to interact with the kernel without needing to access it directly.
glibc (GNU C Library),libpthread,libssl,libm,*.so file

3. Shell
The shell is the command-line interface that allows users to communicate with the operating system by entering commands.
Bash,Sh,zsh

4. Hardware Layer
The hardware layer consists of physical components that execute commands and provide system resources.
Includes CPU, RAM, storage, and input/output devices.
.
5. System Utilities (User-Space Tools)
System utilities are built-in tools that help users manage, configure, and maintain the operating system.
Linux commands come under this 
File tools: ls, cp, mv, rm
Process tools: ps, top, htop
Disk tools: df, du, mount
Network tools: ping, ss, netstat
System tools: systemctl, journalctl


Explain process states (running, sleeping, zombie, etc.)
Running: Process is currently executing on CPU or ready to run
Sleeping : Process is waiting for something like user input,network data or timer
Stopped : Process execution is paused
Zombie : 
    Process has finished execution
    But parent process did NOT collect exit status
    Process is dead but entry remains

List 5 commands you would use daily
# ls –ltr
# df –hT
# top
# ps –ef 
# netstat –tulnp
# ping
# nslookup

•	What systemd does and why it matters
	SystemD I is runs in user space as PID 1
	systemD PID is 1 and this is parent of all processes  start/system call by kernel 


