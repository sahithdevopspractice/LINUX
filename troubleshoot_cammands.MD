Here are ten essential troubleshooting commands for Linux systems, often used by DevOps and Site Reliability Engineers (SREs):

1.top
 - Displays real-time system information, including running processes, CPU usage, memory usage, and more.

 top
 

2. htop
 - An improved version of `top` with a more user-friendly interface and additional features.
 
 htop
 

3. ps
 - Displays information about active processes. Commonly used with options to filter or format output.
 
 ps aux 

4. netstat
 - Displays network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.
 
 netstat -tuln

5. ss
 - Provides detailed information about socket connections, similar to `netstat`, but with more modern features and better performance.
 
 ss -tuln

6. df
 - Displays the amount of disk space used and available on mounted file systems.
 
 df -h
 

7. du
 - Estimates file space usage, often used to find large files and directories.
 du -sh 
 

8. dmesg
 - Prints the kernel ring buffer messages, useful for diagnosing hardware and driver issues.
 
 dmesg | less
 

9. journalctl
 - Queries and displays logs from `systemd` journal, which captures logs from various system services and applications.

 journalctl -xe
 

10.ping
 - Tests the reachability of a host on an IP network and measures the round-trip time for messages sent to the destination

 ping google.com

11.traceroute
 - Displays the route packets take to a network host, useful for diagnosing network path issues.

 traceroute google.com

12.curl
 - Transfers data from or to a server using various protocols, often used for testing API endpoints and network services.

 curl -I http://example.com
 

13.nslookup:-

 - Queries Internet name servers interactively to find DNS details, such as IP addresses associated with a domain.

 nslookup example.com

14.lsof:- 

 - Lists open files and the processes that opened them, helpful for diagnosing issues related to file locks and network ports.
 
 lsof -i :8080

15.Free:-

 - Displays the amount of free and used memory in the system.
 
 free -h
