
Maintaining a efficient process utilization on windows - 

Collect process information using task viewer

Task viewer![taskview png](https://user-images.githubusercontent.com/71600146/119292253-a58efa00-bc6d-11eb-9bd3-ff93c6605620.png)

Terminate a process using windows power shell

first find the pid of a task you want to kill . go to task manager and click details to find the pid.

PID ( process ID )

![pid png](https://user-images.githubusercontent.com/71600146/119293400-fa337480-bc6f-11eb-8e11-2809f3e47db4.png)

Then open windows power shell and type the following command.

taskkill /pid [ your pid ]

![taskkill png](https://user-images.githubusercontent.com/71600146/119293751-b1c88680-bc70-11eb-8789-bef20c8a51b8.png)

To terminate multiple task, type the following command in windows power shell.

![multipletask kill png](https://user-images.githubusercontent.com/71600146/119293878-f05e4100-bc70-11eb-859f-98df939ca4c6.png)

