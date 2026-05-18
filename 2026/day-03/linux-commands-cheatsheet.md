# Linux Cheat Sheet commands
## Process command 
- `ps aux`- to show snapshot of process
- `top` - to show live active process
- `kill <PID>` - to kill the process 
- `pgrep <process_name>` - to get all **PID** of that process
- `pkill <service name>` - to kill the process to instance their name 
not PID

## File system

### Basic File navigation command
- `pwd` - print working directory
- `cd /path` - change directory
- `mv [source] [path/new_name]` - To Rename or move the file 
- `cp` - to copy the file/dir 
- `rm` - remove the file/dir
- `ls` - list file/dir
- `rmdir` - remove empty dir
- `cd ..` - navigate to previous path

### File Manipulation
- `grep <flags> <pattern> [file/dir]` - to  search pattern, keyword in files or dirs.
- `head [file]` - to read the first 10 lines 
- `tail [file]` - to read last 10 lines
- `cat` - to read entire file
- `touch [filename]` - to create empty file
- `diff [file1/dir1] [file2/dir2]` to compare two files


## Networking 
- `ping <URL>` - to check to remote connections
- `ip addr` - to view the IP address
- `netstat -tuln` to view the socket, tcp and udp with their port

