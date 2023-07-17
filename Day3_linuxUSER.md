# Linux For User
**Overview of Kali Linux**
1) Information gathering
● Tools for information gathering, in system, network, host
2) Vulnerability Analysis
● Tools for Finding Vulnerabilities
3) Web Application Analysis
● Tools for Finding Vulnerabilities and exploits on websites.
4) Database Assessment
● Tools for Finding Vulnerabilities and exploits on Databases.
5) Password Attacks
● Tools for exploiting Passwords for login, websites, applications, and Windows.
6) Wireless Attacks
● Tools for exploiting Wireless Systems like wifi, and Bluetooth.
7) Reverse Engineering
● Tools for exploiting Software, Mobile Applications, and any binary files
8) Exploitation Tools
● Tools for exploiting Software, Mobile, Computers, websites, and any things
9) Sniffing & Spoofing
● Tools for Listening or hijacking networks
10) POST exploitation
● Tools for Maintaining our access. Used after exploiting a system
11) Forensics
● Tools for Doing research and investigating Cyber Attacks.
12) Reporting tools
● Tools for Report preparation. After some forensics, you will get data and write a report; these tools will help you.
13) Social Engineering tools
● Tools Used for Social engineering attacks
14) System Services
● Buttons used to start some services.
15) Usually used applications
● Software for some basic purposes Shutdown, lock, restart Workspace manager Used to Classify our works on different Windows desktop Properties Background Changes

## **Linux Commands**
● Linux Systems use a shell. The shell helps us to Communicate with the kernel and helps to execute codes.
● *Shell also called **“Terminal”*** 
**The shell**
● The terminal has 5 parts.
○ Username = solyana
○ Hostname = kali
○ Current Directory = PATH
○ Privilege = $-(user) , #-(root)
○ Command place = _
● Home directory is ~
● Local directory with.
● All directories *
Directory = folder
**Linux Command Basics**
● On Linux there are over 100 commands. But we will see the main and the useful only.
● Also those commands have their options and arguments.
What is command “Small programs that do one task well”
**ls / List Directory**
 List information about the FILEs (the current directory by default).
● ls -l *list*
● ls -a *list + hidden although*
● ls -f *filename*
● ls -R => *recursive open all all files*
You can combine them, **ls -Rla**
Linux hidden files start **with dot.**
**cd / Change Directory**
It is used to change the current working directory. 
 
● cd / => *root*
● cd => *home*
● cd .. => *1x Back*
● cd ../.. => *2x Back*
● cd ***"foldername"***
If the folder name has space you have to add the name inside “ folder name “
cd **“folder name”**
**Pwd / print working directory**
SYNOPSIS
pwd [-options]
DESCRIPTION
 It prints the path of the working directory, starting from the root.
Example after typing pwd:
/home/Omar/Desktop/OSLab
 **echo** 
SYNOPSIS
 echo [option] [string]
DESCRIPTION
 echo command in Linux is used to display lines of text/string that are passed as an argument. This built-in command is mostly used in shell scripts and batch files to output status text to the screen or a file. 
● You can write texts into files.
○ echo text > file.txt
● You can add texts(append)
○ echo text >> file.txt
SYNOPSIS
 cat [FILE]...
DESCRIPTION
 Used to show the content of a file
 touch
SYNOPSIS
 touch [FILE1] [FILE2] [FILE3]
DESCRIPTION
 Creates any kind of Files with the name you gave it. With empty inside.
**Mkdir / make directory**
SYNOPSIS
 mkdir [FOLDER-NAME1] 
[FOLDER-NAME2] [FOLDER-NAME3]
DESCRIPTION
 Creates a Folder with the name u gave it.
- DON’T forget to add the “ “ when you are using folders with space between them.
**clear**
SYNOPSIS
 clear
DESCRIPTION
 Clears your screen.
 **rm / remove**
SYNOPSIS
 rm [FILE1] [FILE2] [FILE3]
DESCRIPTION
 Remove file
● rm -r => **recursive(4 folders)**
● rm -i => **for prompt(ask)**
● rm -f => **force delete**
You can use them in combination too like rm -rf ‘filename’
**Cp| mv/copy, move**
SYNOPSIS
 cp [oldFILEplace] [newfilePlace]
 Mv [oldFILEplace] [newfilePlace]
DESCRIPTION
 Copy/move files & folders.
grep - a global search for regular expression
● grep [options] pattern [files]
● The grep filter searches a file for a particular pattern of characters and displays all lines that contain that pattern. The pattern that is searched in the file is referred to as the regular expression (grep stands for a global search for regular expression and printout).
● grep -i **“search” file** 
○ - case insensitive
● grep -c **“search” file** 
○ - count numbers
● grep -l **“search”** 
○ - displays the filename
● grep -R **“search” folder name** 
○ - search text in folders
● grep -v **‘term’ filename**
○ To display without this term
● grep -n **“term” file**
○ To display the term find number 
**Wc - word count**
SYNOPSIS
 wc [OPTION]... [FILE]...
DESCRIPTION
 It is used to find out several lines, word count, byte and character count in the files specified in the file arguments.Line(-l) word(-w) byte(-c) 
Multiple Command Executions
● You can run/ execute multiple commands in 1 line.
● using 3 methods:
○ And ( && )
○ Or ( || ) 
○ Pipeing( | )
**AND ( && )**
On AND operation All commands you entered will be executed. If both are working without error
**OR ( || )**
On OR operation the command will be executed. If it has an error or not 
**Piping ( | )**
On pipe, will help you run commands by using the output of the 1st command as the input for the next one.