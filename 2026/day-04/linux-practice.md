# Practice Linux fundamentals 

## Process Command
- To check running processes we use command name 
`ps aux | head` 

![](/process.jpg)

- To list the all PID of process with their respective child process
 `pgrep code`.

 ![](/pgrep.png)

## Services Command
- TO inspect systemd service we use status
`systemctl status bluetooth`

![](/servicestat.png)


- TO list the services unit (top 10)
 `systemctl list-units | head`

![](/servicelist.jpg)