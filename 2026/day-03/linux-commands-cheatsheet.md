---

==>  Process Management

# ps -ef

    --> Displays all running processes on the server in full format.

# ps -ef | grep -i <filter_word>

    --> Displays running processes and filters the output based on a keyword.

# ps aux | grep <pid>

    --> Displays all running processes and filters the output to lines containing the given PID (text match).

# top

    --> Shows live running processes in a text-based, real-time interface.

# htop

    --> Shows live running processes in an interactive, colorful interface with enhanced controls.

# kill -9 <pid>

    --> Forcefully terminates the specified process using its PID.

# pstree

    --> Displays running processes in a hierarchical tree structure showing parent–child relationships.

---

==>  File System

# df -hT

    --> Displays disk space usage in human-readable format along with filesystem types.

# lsblk

    --> Lists block devices, their sizes, partitions, and mount points in a tree format.

# mount

    --> Mounts a filesystem to a specified directory (mount point).

# umount

    --> Unmounts a filesystem from the specified mount point.

---

==> Network Troubleshooting

# ip r l

    --> Displays the Linux routing table, showing how packets are routed to different networks.

# ifconfig

    --> Displays IP address and network configuration of Ethernet interfaces (legacy command).

# netstat -tulnp

    --> Lists listening TCP and UDP ports along with their IP addresses, PIDs, and process names.

# telnet <ip> <port>

    --> Checks connectivity from the source server to a destination IP and port.

# ping <ip/hostname>

    --> Checks basic network connectivity and reachability.

# ifup <interface>

    --> Brings a network interface up and activates the connection.

# ifdown <interface>

    --> Brings a network interface down and deactivates the connection.

# traceroute

    --> Shows the network path (hops) packets take to reach a destination and identifies delays or drops.

# dig

    --> Queries DNS servers directly to troubleshoot and verify domain name resolution.

# nc -zv <host> <port>

    --> Tests connectivity to a remote host and port without sending data.

# ss -tulnp

    --> Displays listening TCP and UDP ports along with the associated PID and process name.

# nmcli

    --> Command-line tool used to configure and manage network interfaces via NetworkManager.

# curl

    --> Transfers data to or from a server using URLs, commonly used to test APIs and web services.

# wget

    --> Downloads files from the internet using HTTP, HTTPS, or FTP in a non-interactive mode.


