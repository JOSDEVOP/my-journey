# $ man -k commandname i want to learn how to use. example $ man -k ls brings the manual on how to use use the command ls which is used in bring the content of a directory of a foöder.
# The structure or syntax of linux commands is that the commandname first then [-options] then inputname,filename. 
# $ ls -lh directoryname -- example ls -lh filename  brings all list contents in a human readable format.
# https://www.geeksforgeeks.org/linux-commands-cheat-sheet/ using this link to get cheat codes

# Linux Cheat Sheet for DevOps Engineers

This cheat sheet includes essential Linux commands and concepts commonly used in the DevOps workflow:

# File System Navigation:

# pwd: Print the current working directory.
# ls: List files and directories in the current directory.
# ls -l: List files and directories in long format.
# ls -a: List all files and directories, including hidden ones.
# cd: Change the current directory.
cd ~: Change to the home directory.
cd ..: Move up one directory level.
touch: Create an empty file.
mkdir: Create a new directory.
rm: Remove files or directories.
rm -rf name of directory or path : Remove directories recursively.example rm -rf go/ this would delete this directory permanently
mv: Move or rename files and directories.
cp: Copy files and directories.
find: Search for files and directories.
grep: Search for text within files.
cat: Display the contents of a file.
more or less: View file content page by page.
head and tail: Display the beginning or end of a file.
file: Determine file type.
File Permissions:

chmod: Change file permissions.
chown: Change file ownership.
chgrp: Change group ownership.
umask: Set default permissions for new files and directories.
Process Management:

ps: List running processes.
ps aux: List all processes.
top: Monitor system processes in real-time.
kill: Terminate processes.
killall: Terminate processes by name.
bg and fg: Manage background and foreground processes.
nohup: Run a command that continues running even after you log out.
Package Management (Debian/Ubuntu):

apt-get update: Update package lists.
apt-get upgrade: Upgrade installed packages.
apt-get install: Install new packages.
apt-get remove: Remove packages.
apt-cache search: Search for packages.
dpkg: Debian package management commands.
Package Management (Red Hat/CentOS):

yum update: Update packages.
yum install: Install packages.
yum remove: Remove packages.
yum search: Search for packages.
rpm: RPM package management commands.
Networking:

ifconfig or ip: Display network interface information.
ping: Check network connectivity.
netstat: Network statistics.
ssh: Securely access remote systems.
scp: Securely copy files between systems.
curl or wget: Download files from the internet.
nc: Netcat for network-related tasks.
iptables or firewalld: Configure firewall rules.
System Information:

uname: Display system information.
df: Show disk space usage.
du: Show directory space usage.
free: Display memory usage.
top or htop: Monitor system resources.
lscpu or cat /proc/cpuinfo: CPU information.
lsblk or fdisk -l: List block devices.
date: Display the system date and time.
Shell Scripting:

Create and edit shell scripts using a text editor like nano, vim, or emacs.
Use #!/bin/bash (or another shell) as the shebang line.
Make the script executable with chmod +x script.sh.
Execute the script with ./script.sh.
Version Control:

git: Git commands for version control.
svn: Subversion commands for version control.
Containerization (Docker):

docker: Docker commands for container management.
docker-compose: Compose multiple containers.
Automation (cron):

crontab: Schedule recurring tasks.
Text Processing:

sed: Stream editor for text manipulation.
awk: Text processing tool.
cut: Extract sections from lines of files.
Monitoring and Logging:

Use tools like syslog, journalctl, and logrotate for system logs.
Use monitoring tools like Nagios, Zabbix, or Prometheus for system health.

