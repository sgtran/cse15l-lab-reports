# Lab Report Five 
---
Author: Sean Tran 

PID: A16045509

## Researching Commands
* I chose to explore _grep_ for additional command line options.

***grep -r -c "[ANY STRING]" ./written_2***
* This command searches all of written_2 directory and finds how many occurances of a given string occur in each file.
* This option may be useful for when you are looking for how many times a word occurs in a entire directory. You may also use this option to find all the files that contain language you want to change.
* This first example shows us how many occurances of "sandal" are in each file. 
![Image](3.12.1.PNG)
* The second example adds an extra command ***| grep -v ":0*** to omit all lines of output that have zero occurances so it filters the output to only show the files that have atleast one occurance of the word "oak".
![Image](3.12.0.PNG)

***grep -r -n "[ANY STRING]" ./written_2***
* This command searches all of written_2 and prints each line that contains a given string for each file. 
* This option may be useful for when you want to know how a certain word is being used in every file in a directory. This may also be useful if you want to see the purpose of each word is in each file by reading the sentence it is used in. 
* This first example shows us how many occurrances of "sandal" being used in a line in each file in written_2 directory. 
![Image](3.12.2.PNG)
* This first example shows us how many occurrances of "morse" being used in a line in each file in written_2 directory. 
![Image](3.12.3.PNG)
 
 
