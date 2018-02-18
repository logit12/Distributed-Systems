# Systemes_Repartis
#==================================================
@Author : Lorraine NYEMBI
Date : Nov, 24th 2016
#==================================================
This folder contains the whole SHAVADOOP project 
Eclipse Version: Luna Service Release 2 (4.4.2)
OS: Linux
#==================================================

To launch the program, please to follow these steps:

1 - download the zip files following this link => https://github.com/logit12/Systemes_Repartis

2 - then go into the folder Systemes_Repartis. Unzip the package SHAVADOOP in a choosen folder, for instance "~/hostname/workspace/"


==> You should find these files : 
	-> master.jar
	-> slave.jar
	-> MASTER_SHAVADOOP_JAR which is the java project for the master
	-> SLAVE_SHAVADOOP_JAR which is the java project for the slaves
	-> filetoread.text which contains all machines names where the slaves could run
        -> Input.text which is the input file for our program
	-> batch.sh which is my script to launch our program
	-> sample_in_shell_script.txt 

3 - open the shell script and go to the place where you have unzipped the package SHAVADOOP

$ cd ~/hostname/workspace/

4 - in case of, give the rigths to the batch.sh file

$ chmod u+x batch.sh

5 - execute the batch file

$ ./batch.sh

The program start. If you see the below line, it means that the code have been well executed.

****************Tout est fini***************************************************

6 - to see the results, go to the place where you have unzipped the package SHAVADOOP
New files have been created. The most important is the file SHAVADOOP_RESULTS.text

========================================================================
Notes for batch.file:

You can adapt the batch file and set the value of the different variables
========================================================================
