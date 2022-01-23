# Use Mac Terminal Commands for GIT
1. ON THE MAC, we have TWO DIFFERENT SHELLS, TWO DIFFERENT TEXT INTERFACES.

1.1 First one is the older one: BASH

1.2 The latest is the Z or zsh the so-called Z-shell

1.2.2 Z-shell - this is pronounced as "zat shell"

2. THREE DIFFERENRT OPTIONS IN THE WINDOWS MACHINE
2.1. CMD, which is the command prompt. It is the traditional and initial Windows shell
2.2. Latest is the POWERSHELL (from Windows 7 Release)
2.3. GIT BASH - it is a bash emulation for Windows. If you're working also on the Mac, it is better to install this in Windows and use it rather than the CMD or PowerShell

3. Mac Terminal Commands
3.1 pwd >>> stands for print current directory
3.2 cd or cd ~ or cd -- >>> takes you back to your root directory
3.3 cd .. >>> takes you back one hierarchy level up
3.4 clear >>> to clear up your terminal space
3.5 / >>> it means that we are in the root directory. The root directory is where the Users directory is located.
3.6 ~ >>> this tilde means that we are in the Users or Home directory. That is, this is same as /Users/satorusotoyama
3.7 so if you are in the root directory (/) you can go to your home directory by typing "cd ~"
3.8 cd /Users >>> type this to take you back to your Users directory
3.9 NOTES: we have 3 main directories in our Mac book
3.9.1 ROOT
3.9.2 USERS
3.9.3 HOME DIRECTORY
3.10. WHEN YOU START A NEW TERMINAL, YOU ENTER THE HOME DIRECTORY
3.11. YOU CAN ALWAYS QUIT AN EXISTING TERMINAL WITH COMMAND "EXIT"
3.12 rmdir >>> to remove directory or folder. However, for a folder that is being tracked by git, this command won't work. There is a separate command rm -r to be used but that will be covered in another topic.
3.12.1 rmdir >>> to remove directory or folder. However, for a folder that is being tracked by git, this command won't work. There is a separate command rm -r to be used but that will be covered in another topic. One thing to keep in mind is that the rmdir command will not work if you have files in the directory or folder. First is to remove those files first.
3.13 rm >>> to delete files permanently. you won't have warnings here and you won't also find your files in the trash. If you delete a file here in the terminal, the file is gone.
3.14 rm -r >>> to remove a directory or folder together with it's files in it
3.15 Moving the cursor at the start or end of a line of text
3.15.1 ctrl + a >>> moves the cursor at the beginning of the line
3.15.2 ctrl + e >>> moves the cursor at the end of the line
3.16 ls -s >>> outputs the the data and byte size of the files
3.17 ls -l >>> outputs the files, the date they were created, byte size, and many more
3.18 ls -ls >>> combines both ls -s and ls -l
3.19 for more information on flags, simply use the man command
3.19.1 man ls >>> provides more information about the command ls
3.20 cp <source path> <target path>  >>> used for copying files
3.21 cp -r <folder to be copied>/ <target folder>/ >>> copies a folder to another folder
3.21.1 NOTE: be careful not to forget the / after the folder names
3.21.2 However in my MacBook Pro, without the / it works. 
3.22.3 So it really depends on the version of the Mac terminal that you're using.
3.23 mv >>> to move files or folders and works in the same way as for the cp command of copying files and folders.
3.23.1 mv <source folder/folder to be moved> <target folder> moves a folder within a folder to another folder
3.23.2 mv <current name of file> <new name of file> >>> change a name of a file in the same folder

4. On accessing folders, use TAB to autofill when moving from one folder to the other.

5. Absolute and relative paths
5.1 RELATIVE PATH >>> means always start with my current location
cd Users >>> this is an example of relative path because I'm currently in the C folder and am accessing one of the folders within this folder, which is the C folder
5.2 C:\> cd Users\satoto\Documents\SCCAF >>> this is another example of a relative path where you go directly to the SCCAF folder from the root folder C:\>
5.3 cd / >>> takes you back to the root folder
5.4 cd:\Users> cd:\Users\satsoto\Documents\SCCAF >>> takes you directly to the SCCAF directory by typing the complete path from the root folder of the current drive, which is C:\ in our example. This is an example of ABSOLUTE PATH.
5.5 Software developers normally use ABSOLUTE PATH so that the path doesn't break regardless of you move it to another computer or anything else. I'll find more about this later since I don't fully understand it.
5.6 cls >>> is equivalent to clear fro Mac to clear up the window or screen
5.7 /Users/satorusotoyama/projects/git-demo is an example of an absolute path. 
5.7.1 Note that it always starts with the root directory

