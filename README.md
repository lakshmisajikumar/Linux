* `mkdir EV4`
    Creates a new directory named EV4.

* `cd EV4`
    Changes the current working directory to ev4.

* `mkdir 37`
    Creates a directory with the given roll number inside EV4

* `cd 37`
    Moves into that directory.

* `cd -`
    moves back to the previously visited directory.

* `cd .`
    stays in the current directory.

* `cd ..`
    moves to the parent directory.

* `cd ~`
    Navigates to the user’s home directory.

* `cd /`
    Navigates to the root directory of the Linux file system.

* `pwd`
    Displays the absolute path of the current working directory.

* `ls -l`
    Lists files and directories.

* `ls -al`
    Lists all files including hidden files

* `mkdir emptydummy`
    Creates an empty directory named emptydummy.

* `mkdir dummy`
    Creates a directory named dummy.

* `touch f1`
    Creates an empty file named f1.

* `touch f2`
    Creates an empty file named f2.

* `rm -i f2`
    Deletes file2 after asking for user confirmation.

* `rmdir emptydummy`
    Removes the directory emptydummy since it is empty.

* `rmdir dummy`
    Fails because dummy is not empty.(only works when file is empty)

* `rm -r dummy`
    Deletes the directory dummy along with all its contents.

* `cat > f1.txt`
    Creates f1.txt and allows the user to enter text from the terminal.

* `cat > f2.txt`
    Creates f2.txt and stores user-entered text.

* `cat f1.txt f2.txt > filecombined.txt`
    Combines the contents of both files into filecombined.txt.

* `cat f3.txt >> filecombined.txt`
    Appends the content of f3.txt to filecombined.txt.

* `grep -i hello file*`
    Searches for the word “hello” (case-insensitive) in all files starting with file.

* `cp f1.txt ~/ev4`
    Copies f1.txt to the ev4 directory.

* `mv filecombined.txt combined`
    Renames the file to combined.

* `chmod u+x combined`
    Gives execute permission to the file owner.

* `chmod g-r combined`
    Removes read permission from the group.

* `chmod 777 combined`
    Gives full read, write, and execute permissions to all users.

* `sudo useradd lakshmi`
    Creates a new user named lakshmi.

* `sudo passwd lakshmi`
    Sets or changes the password for user lakshmi.

* `sudo userdel lakshmi`
    Deletes the user lakshmi from the system.
