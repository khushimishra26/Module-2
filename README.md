# Module-2
Contains screengrabs for assignments 1 and 2.

# Assignment 1 (Process Management)
Maintain Efficient Process Utilization on Windows

Eg: Kill a running task (say Notepad) using powershell

Take the PID (Process ID) from task manager (ctrl+shift+esc)


![](https://github.com/khushimishra26/Module-2/blob/main/assignment1/process%201.JPG)


Run the command in powershell:
taskkill /pid [pid goes here]

If success the following message will be printed:  SUCCESS: Sent termination signal to terminate the process with PID [id].
  
  
![](https://github.com/khushimishra26/Module-2/blob/main/assignment1/process%201%20kill.JPG)
  
  
Hence, the process will be terminated.
  
For multiple process termination use:
taskkill /pid [pid goes here] /pid [another pid goes here] ....


![](https://github.com/khushimishra26/Module-2/blob/main/assignment1/process%203.JPG)


![](https://github.com/khushimishra26/Module-2/blob/main/assignment1/process%203%20kill.JPG)


All the processes will be simultaneously terminated successfully.
  
# Assignment 2 (Operating System In Practice)
Using Logs to Help Track Down An Issue In Windows 

1. Assigning permissions for a file (eg- read or modify permissions to admin, guest etc)  


![](https://github.com/khushimishra26/Module-2/blob/main/assignment%202/permissions.JPG)

  
2. Deleting a file for which one does not have permissions


![](https://github.com/khushimishra26/Module-2/blob/main/assignment%202/delete.JPG)

  
3. Ending a running process using task manager


![](https://github.com/khushimishra26/Module-2/blob/main/assignment%202/end%20process.png)

  
4. Checking for updates for any installed application (here, VLC Media Player) on the system.  


![](https://github.com/khushimishra26/Module-2/blob/main/assignment%202/check%20updates%20vlc.JPG)

