# Lab Report Three 
---
Author: Sean Tran 

PID: A16045509

## Researching Commands
* I chose to explore _find_ for additional command line options. 
* 1: **find ./written_2/ -[PERMISSION]**
* This searches the entire written_2 directory and all files you have permission to do a specific action.
* The first example shows us searching for all files we can read.
![Image](2.13.1.PNG)
* The second example shows us searching for all files we can write. 
![Image](2.13.2.PNG)

* 2: **find written_2 -type [FILE TYPE]**
* This command allows you to specify type of file you are looking for.
* The first example shows us searching for all directories in written_2
![Image](2.13.3.PNG)
* The second example shows us searhing for all files in written_2
![Image](2.13.4.PNG)

* 3: **find written_2 -maxdepth [DEPTH NUMBER] -type d**
* This command allows you to limit the depth of directories displayed from given directory. 
* The first example limits the depth to one level.
![Image](2.13.5.PNG)
* The second example limits the depth to two level.
![Image](2.13.6.PNG)

* 4: **find ./written_2 -mtime -[TIME]**
* This command allows you to find all the files and directories that were last modified in n given days.
* The first example limits max last time edit to 7 days.
![Image](2.13.7.PNG)
* The second example limits the max last time edit to 1 day.
![Image](2.13.8.PNG)
* Sources: **man find** command in terminal and https://www.redhat.com/sysadmin/linux-find-command
