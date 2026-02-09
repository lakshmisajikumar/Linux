# ===============================
# STEP 1: Create and navigate directories
# ===============================

mkdir EV4                     # Create a new directory named EV4
cd EV4                        # Move into EV4 directory

mkdir 37                      # Create a directory with roll number
cd 37                         # Move into directory 62

cd -                           # Go back to the previous directory
cd .                           # Stay in the current directory
cd ..                          # Move to parent directory
cd ~                           # Go to home directory
cd /                           # Go to root directory

pwd                            # Display current working directory path

# ===============================
# STEP 2: List files and directories
# ===============================

ls -l                          # List files and directories (long format)
ls -al                         # List all files including hidden files

# ===============================
# STEP 3: Create directories
# ===============================

mkdir emptydummy               # Create an empty directory
mkdir dummy                    # Create a directory named dummy

# ===============================
# STEP 4: Create files
# ===============================

touch file1                    # Create empty file file1
touch file2                    # Create empty file file2

# ===============================
# STEP 5: Remove files and directories
# ===============================

rm -i file2                    # Delete file2 with confirmation
rmdir emptydummy               # Remove empty directory emptydummy
rmdir dummy                    # Fails because directory is not empty
rm -r dummy                    # Remove dummy directory with its contents

# ===============================
# STEP 6: File content operations
# ===============================

cat > file1.txt                # Create file1.txt and enter text manually
cat > file2.txt                # Create file2.txt and enter text manually

cat file1.txt file2.txt > file_combined.txt   # Combine contents into one file
cat file3.txt >> file_combined.txt             # Append file3.txt content

# ===============================
# STEP 7: Search text in files
# ===============================

grep -i hello file*            # Search for 'hello' (case-insensitive)

# ===============================
# STEP 8: Copy and rename files
# ===============================

cp file1.txt ~/ev4             # Copy file1.txt to ev4 directory
mv file_combined.txt combined  # Rename file_combined.txt to combined

# ===============================
# STEP 9: Change file permissions
# ===============================

chmod u+x combined             # Give execute permission to owner
chmod g-r combined             # Remove read permission from group
chmod 777 combined             # Give full permissions to everyone

# ===============================
# STEP 10: User management (Admin only)
# ===============================

sudo useradd alice             # Create a new user named alice
sudo passwd alice              # Set password for alice
sudo userdel alice             # Delete user alice
