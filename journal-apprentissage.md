Cybersecurity Learning Journal

Day 1 — Linux Fundamentals

Platform: OverTheWire Bandit

Objective: Learn to navigate a Linux environment and identify files.

1.	Commands Learned

“whoami”| Identifies the current user
“pwd”| Displays the current directory
“ls”| Lists files and directories
“cd”| Changes the current directory
“cat”| Displays file contents
“file”| Identifies the type of a file

2.	What I Learned

I learned how to identify the current user, locate myself in the Linux filesystem, list files and directories, and distinguish between displaying file contents and identifying file types.

3.	Difficulties

I sometimes confused the purposes of the “cat”, “cd”, and “file” commands.

4.	How I Improved

I answered practical questions, corrected my mistakes, and reviewed the purpose of each command.

5.	What I Need to Practise

- Navigating directories with “cd”.
- Reading files with “cat”.
- Identifying file types with “file”.
- Using commands independently.


Day 2 — Linux System Observation
Environment: Kali Linux in a virtual machine.
Objective: Learn how to observe a Linux system, inspect running processes, and understand basic network configuration.
1. Commands Practised
•	whoami: identifies the current user.
•	pwd: displays the current working directory.
•	uname -a: displays system and kernel information.
•	ps: displays running processes.
•	ps aux: displays a detailed list of processes.
•	ip addr: displays network interfaces and their IP addresses.
•	ip route: displays network routing information.
2. What I Learned
I learned how to identify the current user, inspect system information, and observe running processes.
I discovered that 127.0.0.1 is the IPv4 loopback address, which allows a machine to communicate with itself.
I also learned the difference between an IP address, a network subnet, and a gateway:
•	An IP address identifies a network interface on an IP network.
•	A subnet represents a range of IP addresses grouped by a network prefix.
•	A gateway can forward traffic toward other networks.
3. Process Investigation
I examined a Linux kernel worker thread named kworker.
I learned that a process name alone is not sufficient to determine whether a process is malicious. Investigations require additional evidence and context.
4. Difficulties
I initially confused the meaning of a gateway with the meaning of a subnet.
5. How I Improved
I worked through practical examples to distinguish the IP address of a machine, its gateway, and its subnet.
6. What I Need to Practise
•	Interpreting complete routing tables.
•	Identifying network interfaces and their addresses.
•	Understanding how packets travel between networks.
•	Investigating processes using relevant system information.
7. Next Step — Day 3
Study network interfaces, IPv4 addresses, gateways, and routing through practical exercises.

