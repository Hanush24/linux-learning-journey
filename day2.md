Today is the day 02 of learning linux basics

1. If we open a directory or file using (ls -l)command we can get something like -rw-r--r-- 1 usrname usrname 0 bla bla bla
r(read) w(write) x(excecute).
we can change permissions buy using a command called - chmod(change mode)
we can use it like : chmod -r filename  #this removes the readablity of the file hence -r is used
chmod +r filename #this adds the readabilty of the file hencce +r is used by using this we can change any of the files permission mode

2.hidden files
to open the hidden files in the system use the command (ls -a) this will show us all the hidden files.
every hiddenfile starts with a dot (.hiddenfile)
to create a hidden file use command(touch ~/.hiddenfile) this will create a hiddenfile

3.bash script
bash script is usually used to create a set of commands to run automatically in a single script it is said to be as bash script.
for example if you want to take a backup of your works daily in some other folder. if you set the script and saved. daily once you finished the work use this single bash script so that it can backup to a new folder. its easy to reduce complexity.
to create a bash script file use extension .sh (helloworld.sh)
first create a bash script and program it then save it. then run it using terminal
example: nano helloworld.sh
in bash
     echo "Hello world,Im using linux ubuntu distro"
save and exit
now you need to execute the bash file so make sure you have X(excecute) in address by using ls -l if not add it 
then to run the program use (./)before the script name = ./helloworld.sh
***BOOM*** you got the script run.

4.shortcuts
ctrl+a = start of the line
ctrl+e = end of the line
ctrl+u = erase everything before the cursor
ctrl+c = stops a running command

and yaaaaaaaaaaa todays learning was completed and we got this.