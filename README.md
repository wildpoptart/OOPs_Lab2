# OOPs_Lab2
C++ algorithm to search a given schedule
Prepared by Stanyslav Borsh
Fall 2018

Lab 2 was the main goal was to read information from a text file and then be able to have the user be able to search the information by either hour or by activity. The text file that was given is an itinerary of tasks performed throughout the day organized by the hour. This text file needs to be imported into the program using certain libraries. The task is to enable the user to search the imported text file by the hour and return the activity, and search by activity and return the hour. The main steps to complete this assignment is to first, write the algorithm in pseudocode first, then the code is written, and then test the code to see if it works. 
Firstly the pseudocode was written to structure and have an understanding of the code to be written. In the supplement document, Figure 1 shows the pseudocode written for the code. Simply put, the user will be prompted by a menu to input a number 0-2 depending on the search they want. If they search by the hour, then the code will search the appropriate array then display them according to activity. If the user wants to search by activity, then they will input an activity, and the code will output the appropriate hour. Having written out the pseudocode, the next steps are to write the code out. The general layout of the code was a while loop and series of for loops and if statements.  
After writing the code, the algorithm successfully searches for either the hour or the activity and if the search is not a proper hour or a proper activity the program will ask for a resubmit for the user. This can be seen in Figure 1. 
After completing this lab, the most important aspect learned from it is the ability to import data from a text file by using the “fstream” library. Being able to import data into an array means now the types of programs that are now possible are now much greater now the outside data can be read and manipulated, and potentially written too. Another aspect about this lab that was useful was the refreshing practice with arrays and how to read and write to and from them. 
Figure 1: Output from program

