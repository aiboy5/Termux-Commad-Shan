### Chapter 5: Network & System Management Commands
___
#### Part 1:

1. **curl [URL]**: Downloads files or data from servers using various protocols (HTTP, HTTPS, FTP).
   
2. **wget [URL]**: Downloads files from web servers with support for recursive downloads.
   
3. **ssh [user@host]**: Connects to remote servers securely using SSH protocol.
   
4. **scp [source] [destination]**: Securely copies files between local and remote systems.
   
5. **rsync [options] [source] [destination]**: Synchronizes files and directories efficiently.
   
6. **nmap [target]**: Network exploration tool and security scanner for discovering hosts and services.
   
7. **netstat**: Displays network connections, routing tables, and network interface statistics.
   
8. **ps**: Shows currently running processes with their process IDs (PIDs).
   
9. **kill [PID]**: Terminates a process by its process ID.
   
10. **killall [process_name]**: Terminates all processes with the specified name.
   
11. **htop**: Interactive process viewer and system monitor (enhanced version of top).
   
12. **free**: Displays memory usage information including RAM and swap.
   
13. **du -h [directory]**: Shows disk usage of files and directories in human-readable format.
   
14. **find [path] -name [pattern]**: Searches for files and directories matching specified criteria.
   
15. **grep [pattern] [file]**: Searches for text patterns within files.
   
16. **awk '{print $1}' [file]**: Text processing tool for pattern scanning and data extraction.
   
17. **sed 's/old/new/g' [file]**: Stream editor for filtering and transforming text.
   
18. **tar -czf [archive.tar.gz] [directory]**: Creates compressed archive files.
   
19. **tar -xzf [archive.tar.gz]**: Extracts compressed archive files.
   
20. **zip -r [archive.zip] [directory]**: Creates ZIP archive files.
   
21. **unzip [archive.zip]**: Extracts ZIP archive files.
   
22. **crontab -e**: Edits the cron table for scheduling automated tasks.
   
23. **systemctl status [service]**: Checks the status of system services (if available).
   
24. **mount**: Displays or manages filesystem mount points.
   
25. **umount [device]**: Unmounts a filesystem from its mount point.

#### Part 2:

1. **iptables -L**: Lists current firewall rules and network filtering configuration.

2. **tcpdump -i [interface]**: Captures and analyzes network packets for debugging.

3. **ping6 [IPv6_address]**: Tests IPv6 network connectivity to remote hosts.

4. **traceroute [host]**: Traces the network path packets take to reach a destination.

5. **dig [domain]**: DNS lookup utility for querying domain name information.

6. **nslookup [domain]**: Interactive DNS lookup tool for resolving domain names.

7. **whois [domain]**: Retrieves domain registration and ownership information.

8. **nc (netcat) [host] [port]**: Network utility for reading/writing data across connections.

9. **socat**: Advanced networking tool for bidirectional data transfer.

10. **openssl s_client -connect [host:port]**: Tests SSL/TLS connections to servers.

11. **gpg --encrypt [file]**: Encrypts files using GNU Privacy Guard.

12. **gpg --decrypt [file]**: Decrypts GPG-encrypted files.

13. **base64 [file]**: Encodes files to Base64 format for safe transmission.

14. **base64 -d [file]**: Decodes Base64 encoded files back to original format.

15. **md5sum [file]**: Calculates MD5 checksum for file integrity verification.

16. **sha256sum [file]**: Calculates SHA-256 checksum for enhanced security verification.

17. **screen**: Creates detachable terminal sessions that persist after disconnection.

18. **tmux**: Terminal multiplexer for managing multiple terminal sessions.

19. **nohup [command] &**: Runs commands that continue after terminal disconnection.

20. **jobs**: Lists active background jobs in the current shell session.

21. **bg [job_id]**: Moves a job to background execution.

22. **fg [job_id]**: Brings a background job to foreground execution.

23. **disown [job_id]**: Removes a job from the shell's job table.

24. **at [time]**: Schedules commands to run at a specific time.

25. **batch**: Executes commands when system load permits.

26. **watch [command]**: Repeatedly executes a command and displays updated output.

27. **timeout [seconds] [command]**: Runs a command with a specified time limit.

28. **strace [command]**: Traces system calls made by programs for debugging.

29. **lsof**: Lists open files and the processes using them.

30. **fuser [file/port]**: Identifies processes using specific files or network ports.

31. **chroot [directory]**: Changes the root directory for command execution.

32. **sudo [command]**: Executes commands with elevated privileges (if configured).

33. **su [user]**: Switches to another user account.

34. **passwd**: Changes user password.

35. **id**: Displays user and group IDs for the current user.

36. **groups**: Shows group memberships for the current user.

37. **who**: Displays currently logged-in users.

38. **w**: Shows who is logged in and what they are doing.

39. **last**: Displays login history and system reboot information.

40. **uptime**: Shows system uptime and load averages.

41. **date**: Displays or sets the system date and time.

42. **timedatectl**: Controls system time and date settings (if available).

43. **locale**: Displays current locale settings for internationalization.

44. **env**: Shows environment variables or runs commands in modified environment.

45. **export [variable=value]**: Sets environment variables for the current session.

46. **alias [name='command']**: Creates command shortcuts and abbreviations.

47. **unalias [name]**: Removes previously defined command aliases.

48. **history**: Displays command history for the current session.

49. **fc -l**: Lists recent commands from command history.

50. **source [file]** or **. [file]**: Executes commands from a file in current shell.
___
___

These commands provide comprehensive network management, system administration, and process control capabilities within Termux, enabling advanced automation, security operations, and system monitoring tasks.
___
