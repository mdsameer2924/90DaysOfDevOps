# Architecture of Linux

![](/Asset/os.svg)
### Application
This layer provide provide Software to operate Linux  Operating using `tools/ utilities` 
for example Terminal we use it.

### Shell
It's a Shell which provide interface between between Application and Kernel using 
Application software like `Terminal.` which use **(bash,zsh,sh)** to use command to communicate with kernal

### Kernel
It's a Heart of Operating system. Manage system resources, and utilize the hardware like **Memory, CPU etc.**

### Hardware 
computer's component like **Mouse**, **RAM** **Hard disk** etc.



# Booting Process
![](https://i.ibb.co/MxZ7kNm1/boot-process.png)

### How processes are created and managed ?
**Systemd** is the first process running as system boot. it's `PID 1` means **Process ID 1**
which intialize the other processes and **systemctl** command we use to manage and created different processes. 

### Process States
- Running : process is active 
- sleeping: Idle state of process
- Zombie : process has executed but it's process record remain in process table
- Stopped:  process is paused 

### 5 Command I use Daily
1. `ls` to list files and directories 
2. `cd` to navigate different directories
3. `pwd` to print working directory
4. `mkdir` to make directory 
5. `nano` to edit text


