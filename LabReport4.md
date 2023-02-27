# Lab Report Four 
---
Author: Sean Tran 

PID: A16045509

## Competetion Steps
* This lab will go over in depth how to perform the competition steps.
 
 
***Log into ieng6***
* Open VSCode and ssh with username and enter your password.
![Image](bash.PNG)	
* Once you log in, it should look like this.
![Image](logIn.PNG)
* If you have ssh key in ieng then you should not have gotten a password and got loggged in like this.
![Image](2.26.0.PNG)

***Clone your fork of the repository from your Github account***
* Type in the following line of code into terminal and press enter the following command
* git clone [ssh link]
* It should look like this:
![Image](2.26.1.PNG)

***Run the tests, demonstrating that they fail***
* The first step you need to do is cd in the lab7 directory by running the following command:
* cd lab7/
* It should look like this:
![Image](2.26.2.PNG)

* The second step is to compile junit tests by running following command:
* javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
* It should ook like this:
![Image](2.26.3.PNG)

* The third step is to run tests by running the following command:
* java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore TestListExamples
* It should look like this:
![Image](2.26.4.PNG)

***Edit the code file to fix the failing test***
* The first step is to enter the file to edit code by running following command
* nano ListExamples.java
* It should look like this:
![Image](2.26.5.PNG)


***Run the tests, demonstrating that they now succeed***
***Commit and push the resulting change to your Github account (you can pick any commit message!)***



