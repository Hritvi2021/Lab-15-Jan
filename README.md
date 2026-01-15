# Lab-15-Jan

STEP-1
# EC2 Setup and Linux Basics: Install Amazon Linux1.
1. Create a Virtual Machine:
    - VM: Create a new VM, allocate 2 GB RAM, 2 CPU cores, and 20 GB disk space.
2. Login: Login to Linux Machine using the created username and password.

STEP-2
# Explore Directory Structure1. Open Terminal: Open the terminal application.(Moba/Putty)
1. pwd: Print the current working directory.
# Command
bash
pwd
Output: `/home/username`

2. ls: List files and directories in the current directory
# Command
bash
ls
Output: `directories Folders'

3. cd: Change directory to the root directory.
# Command
bash
cd /

4. ls: List files and directories in the root directory.
# Command
bash
ls
Output: `bin  boot  dev  etc  home  lib  lib64  lost+found  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var`

STEP-3
1. Create Directories and Files1. mkdir: Create a new directory.
# Command
bash
mkdir mydirectory

2. touch: Create a new file.
# Command
bash
touch myfile.txt

3. ls: Verify the directory and file creation.
# Command
bash
ls
Output: `mydirectory  myfile.txt`

4. rmdir: Remove the directory (only if empty).
# Command
bash
rmdir mydirectory

5. rm: Remove the file.
# Command
bash
rm myfile.txt

STEP-4
1. File Viewing and Editing1. cat: View the contents of a file.
# Command
bash
cat /etc/os-release
Output: `NAME="Ubuntu" VERSION="20.04 LTS (Focal Fossa)"`

2. less: View the contents of a file page by page.
# Command
bash
less /etc/os-release

3. vi: Edit a file using nano.
# Command
bash
vi myfile.txt

STEP-5
1. File Permissions1. ls -l: View file permissions.
# Command
bash
ls -l
Output: `-rw-r--r-- 1 username username 0 Oct 10 10:00 myfile.txt`

2. chmod: Modify file permissions.
# Command
bash
chmod 755 myfile.txt

3. chown: Modify file ownership.
# Command
bash
sudo chown root myfile.txt

STEP-6
1. System Monitoring1. top: View system resource usage.
# Command
bash
top

2. htop: View system resource usage (install htop first).
# Command
bash
sudo apt install htop
htop

3. df -h: View disk space usage.
# Command
bash
df -h

4. free -m: View memory usage.
# Command
bash
free -m


Command Log File (Used commadns)
# Command Log

## Directory Structure
- `pwd`: Print current working directory
- `ls`: List files and directories
- `cd /`: Change to root directory

## Create Directories and Files
- `mkdir mydirectory`: Create a new directory
- `touch myfile.txt`: Create a new file
- `rmdir mydirectory`: Remove directory (only if empty)
- `rm myfile.txt`: Remove file

## File Viewing and Editing
- `cat /etc/os-release`: View file contents
- `less /etc/os-release`: View file contents page by page
- `nano myfile.txt`: Edit file using nano
- `vim myfile.txt`: Edit file using vim

## File Permissions
- `ls -l`: View file permissions
- `chmod 755 myfile.txt`: Modify file permissions
- `sudo chown root myfile.txt`: Modify file ownership

## System Monitoring
- `top`: View system resource usage
- `htop`: View system resource usage (install htop first)
- `df -h`: View disk space usage
- `free -m`: View memory usage
