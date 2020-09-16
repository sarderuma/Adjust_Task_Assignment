# Adjust_Task_Assignment
#Task 1 assignment

Please design a script that writes the numbers from 1 - 10 in random order. Each number should appear only once. You can use bash only. Please provide tests for the script, along with documentation which should include the following:

    • Build instructions
    • Usage
    • Description
    • Known limitations / bugs

Answer: 

Build instructions: 

    • In order to run the assignment, at first we have to make sure that bash software is running on the operating system successfully. The operating system used during development os Ubuntu 18.04LTS. 
    • Clone the github repository.  And move to the directory containing “task1.sh” file. 

    •  Change the file permission in executable mode by using “chmod +x task1.sh” command.
      
Description:

Here, “bash shuf command” is used to pseudo randomize a given input number. The option -i, drags shuf to operate as range shuf. Lower and higher range shuf produces a range of integers in random order. The program is able to generate any range of random numbers by a given input range.

Usage: 

To execute the code, use “ sh  task1.sh 1 10”  command  in the specific folder to generate a range of integers from 1 to 10 in random order . The output looks like as (It changes in each different run). 
7
9
3
4
1
2
10
8
5

Exception Handling:

Following exceptions are automatically handled by “shuf”.

    • Negative input value will generate an error. 
    • If lower range is greater than the higher range order, then “shuf” generates an error. 


Limitations/bugs:

The program doesn’t generate any float number. This will only generate the integer numbers in terms of a given input range. 
