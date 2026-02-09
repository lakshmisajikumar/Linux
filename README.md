# Linux Commands Cheat Sheet

| Command | Description |
| :--- | :--- |
| `mkdir EV4` | Creates a new directory named EV4. |
| `cd EV4` | Changes the current working directory to ev4. |
| `mkdir 62` | Creates a directory with the given roll number inside EV4 |
| `cd 62` | Moves into that directory. |
| `cd -` | moves back to the previously visited directory. |
| `cd .` | stays in the current directory. |
| `cd ..` | moves to the parent directory. |
| `cd ~` | Navigates to the user’s home directory. |
| `cd /` | Navigates to the root directory of the Linux file system. |
| `pwd` | Displays the absolute path of the current working directory. |
| `ls -l` | Lists files and directories. |
| `ls -al` | Lists all files including hidden files |
| `mkdir emptydummy` | Creates an empty directory named emptydummy. |
| `mkdir dummy` | Creates a directory named dummy. |
| `touch file1` | Creates an empty file named file1. |
| `touch file2` | Creates an empty file named file2. |
| `rm -i file2` | Deletes file2 after asking for user confirmation. |
| `rmdir emptydummy` | Removes the directory emptydummy since it is empty. |
| `rmdir dummy` | Fails because dummy is not empty.(only works when file is empty) |
| `rm -r dummy` | Deletes the directory dummy along with all its contents. |
| `cat > file1.txt` | Creates file1.txt and allows the user to enter text from the terminal. |
| `cat > file2.txt` | Creates file2.txt and stores user-entered text. |
| `cat file1.txt file2.txt > file_combined.txt` | Combines the contents of both files into file_combined.txt. |
| `cat file3.txt >> file_combined.txt` | Appends the content of file3.txt to file_combined.txt. |
| `grep -i hello file*` | Searches for the word “hello” (case-insensitive) in all files starting with file. |
| `cp file1.txt ~/ev4` | Copies file1.txt to the ev4 directory. |
| `mv file_combined.txt combined` | Renames the file to combined. |
| `chmod u+x combined` | Gives execute permission to the file owner. |
| `chmod g-r combined` | Removes read permission from the group. |
| `chmod 777 combined` | Gives full read, write, and execute permissions to all users. |
| `sudo useradd alice` | Creates a new user named alice. |
| `sudo passwd alice` | Sets or changes the password for user alice. |
| `sudo userdel alice` | Deletes the user alice from the system. |
