<img src="logo.png"  width="600" height="200">    
  

# Linux Operating System    
  
   
---
+ Open Source operating system.    
+ The source code is open to all developers and users, publicly visible and editable. 
+ Easy modification and redistribution.
+ The command line is case-sensetive.    
+ Debian, Fedora, Red Hat, and Ubuntiu are some of the common distributions of Linux.   

+ **What is a terminal?**    
A terminal is a program (text-based interface) used to interact with the computer system.      
  
+ When we open the terminal, by default we are in the home directory.
+ "|" pipe operator can be used for multiple commands in one line. 
---   

## Simple Commands    
date &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> gives the current date and time    
cal &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> calendar of the current month       
cal -y &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> calendar of the current year (all of the 12 months)    
cal 1999 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> gives the calendar for a particular year 1999 (specify the year)      
cal 1 2021 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> calendar for January 2021 (1 = January, specify the month and the year)  
cal -3 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> calendar for the previous, current and the next month (displays total 3 months)  
clear &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  -> clears the terminal (retains history)    
exit &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  -> exits the terminal (closes the terminal)    

   
## File System       

<img src="file_structure.png"  width="600" height="200">      

 File system is similar to any other operating system.    
 + Folders are called as directories, sub-folders as sub-directories.         
 + "." represents current directory.    
 + ".." represents parent directory or parent.     
 + Absolute Path: starts from the root directory to the destination directory (complete/full path).      
 + Relative Path: Starts with the current working directory and gives a path for a location relative to the current working directory. Never starts with "/" (root) directory.        
 + "~" represents home directory.
 + When we open the terminal, by default we are in the home directory.
 + "*" means multiple files.   

       
#### Commands   
  
pwd &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> Print working directory (absolute path)       
ls &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> Lists all of the directories inside current working directory      
cd Desktop &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; |    
cd ./Desktop &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp; -> } cd = change directory. (takes to the desktop from the current directory)  
cd /home/mehul/Desktop &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |      
cal -3 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -> calendar for the previous, current and the next month (displays total 3 months)  
clear &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  -> clears the terminal (retains history)    
exit &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;  -> exits the terminal (closes the terminal)      
  
