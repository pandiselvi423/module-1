Maintain efficient process utilization on windows
** collect process information using task viewer. **

@ [Task viewer](Task viewer.png)

** Terminate a specific task using windows powershell.**

first find the pid of the task you want to kill . Go to task manager . click the details tab to find the pid .

PID - process id

@ [ pid ](pid.png)

then open the windows power shell and type the given command.

" windows power shell command taskkill /pid [your pid]"

** Terminate multiple process using windows power shell. **

To kill multiple task , type the following command in the windows power shell.

" windows power shell taskkill /pid[your pid] /pid[your pid] "

! [ pid ](multipletask kill.png)

if you run this command the particular task which is running in the computer will be terminated .
