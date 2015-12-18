# Terminal
Created Friday 05 June 2015

Ctrl+A [Key] > First in the line
Ctrl+E [Key] > End of line
Up [Key] > History (Most recent command)
echo ~ > Home directory, eg. [/home/tyr](file:///home/tyr) 
Tab [Key] >command completion
Tab Tab [Key] > All options available
clear > Clear up the terminal
man (command) > Manual for command 

#Navigation:
**List files:**  
ls >  List (all contents of the active directory)
pwd > Print Working Directory, eg. [/home/tyr](file:///home/tyr) 
ls (argument) > list contents of a directory, eg. ls Music or ls Music Documents (two arguments)
ls argument works with absolute or relative path. eg. ls [/home/tyr/Documents](file:///home/tyr/Documents)  or ls Documents or ls [~/Documents](file:///home/tyr/Documents)
Naigating folders with space in the name: use single quote '' or double quote"" or escape with backslash+space:
ls "Calibre Library" or ls 'Calibre Library' or ls Calibre\ Library

ls -l > list details
ls -a > list all files
ls -t > sort files by last modified
ls -t  -l -a >list all files with details and sort by last modified
ls -tls >list all files with details and sort by last modified

**Change directory:**
cd directory > absolute or relative path, eg. cd Documents or cd [~/Documents](file:///home/tyr/Documents) or cd [/home/tyr/Documents](file:///home/tyr/Documents) 
cd .. >up one directory
Tips: drag a file/folder on the terminal to get the full path like '/home/tyr/Documents/dns-industry-ecosystem.pdf' or /home/tyr/Documents/My Videos' 
xdg-open filename > opent the file in default application

**Open a file**
xdg-open filename > opent the file in default application
**How do I open a text file in my terminal?**
For short files:
cat <path/your_file>
directly shows a text file in the terminal.
For longer files:
less <path/your_file>
lets you scroll and search (/ text to search Enter) in the file; press q to exit.
e.g.
cat /home/john/RESULTS.txt
less /home/john/RESULTS.txt

**Make Copy Move Link files**
touch Filename >  Create a new file named Filename
nano Filename >open or create a file and open in text editor named nano. Ctrl+X to exit.
mkdir Directoryname > create a new directory named Directoryname
touch  Directoryname/Filename >create a new file in new directory
cp afile afile.bak > copy afile to new file afile.bak
Tips: Do not name the copied file to an existing file's name; otherwise it will overwrite the existing file.
cp adir seconddir > copy adir directory to new directory seconddir. However if the directory adir has files in it, it will show you error.
cp -r  adir seconddir > copy recursively adir directory to new directory seconddir. 




[MagicQuotes](./MagicQuotes.markdown)























 

