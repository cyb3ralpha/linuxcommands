# Linux for Hackers - Command Reference

[![Repo Stars](https://img.shields.io/github/stars/cyb3ralpha/linuxcommands?style=for-the-badge)](https://github.com/cyb3ralpha/linuxcommands/)
[![Repo Forks](https://img.shields.io/github/forks/cyb3ralpha/linuxcommands?style=for-the-badge)](https://github.com/cyb3ralpha/linuxcommands/)
[![Repo Views](https://komarev.com/ghpvc/?username=cyb3ralpha&repo=linuxcommands&color=blue&style=for-the-badge)](https://github.com/cyb3ralpha/linuxcommands)
[![Contributors](https://img.shields.io/github/contributors/cyb3ralpha/linuxcommands?style=for-the-badge)](https://github.com/cyb3ralpha/linuxcommands/graphs/contributors)
[![Issues](https://img.shields.io/github/issues/cyb3ralpha/linuxcommands?style=for-the-badge)](https://github.com/cyb3ralpha/linuxcommands/issues)

## 📌 Table of Contents
- [System Information](#system-information)
- [User Management](#user-management)
- [File and Directory Operations](#file-and-directory-operations)
- [File Permissions](#file-permissions)
- [Process Management](#process-management)
- [Networking](#networking)
- [Disk and Storage](#disk-and-storage)
- [Compression & Archiving](#compression--archiving)
- [Package Management](#package-management)
- [Logging & Monitoring](#logging--monitoring)
- [Anonymity & Privacy](#anonymity--privacy)

---

## 🖥️ System Information
```bash
uname -a        # Display system information
hostname        # Show the system hostname
uptime          # Display how long the system has been running
whoami          # Show current user
who             # Show logged-in users
id              # Display user ID and group ID
lsb_release -a  # Show Linux distribution information
```
## 👤 User Management
```bash
who             # Show logged-in users
w               # Display who is logged in and what they are doing
adduser hacker  # Create a new user
passwd hacker   # Change user password
usermod -aG sudo hacker  # Add user to sudo group
groups          # Show groups the current user belongs to
```
## 📂 File and Directory Operations
```bash
ls -lah         # List files in a directory (detailed view)
cd /path/to/dir # Change directory
pwd             # Print working directory
mkdir newdir    # Create a new directory
touch file.txt  # Create an empty file
cp file1 file2  # Copy files
mv oldname newname  # Rename or move a file
rm -rf dir/     # Remove a directory recursively
find / -name targetfile  # Search for a file
```
## 🔒 File Permissions
```bash
ls -l          # View file permissions
chmod 755 file # Change file permissions
chown user:group file # Change file ownership
```

## ⚙️ Process Management
```bash
ps aux         # Show running processes
top            # Display active processes in real-time
htop           # Interactive process viewer
kill PID       # Kill a process by PID
pkill -9 name  # Kill a process by name
nohup command &  # Run command in background
```
## 🌐 Networking
```bash
ifconfig         # Show network interfaces (deprecated)
ip addr show     # Show IP addresses
ping google.com  # Send ICMP request
netstat -tulnp   # Display open ports
ss -tulnp        # Alternative to netstat
nmap -sS target  # Scan open ports (requires nmap)
wget URL         # Download a file from a URL
curl -I URL      # Fetch headers of a URL
whois domain.com # Get domain information
```
## 💾 Disk and Storage
```bash
df -h            # Show disk usage
du -sh *         # Show disk usage per directory
fdisk -l         # Show disk partitions
mount /dev/sdb1 /mnt # Mount a drive
umount /mnt      # Unmount a drive
```
## 🗜️ Compression & Archiving
```bash
tar -cvf archive.tar file  # Create a tar archive
tar -xvf archive.tar       # Extract a tar archive
zip -r archive.zip dir/    # Create a zip archive
unzip archive.zip          # Extract a zip file
```
## 📦 Package Management
# Debian-based (Ubuntu, Kali, Parrot OS)
```bash
apt update         # Update package lists
apt upgrade        # Upgrade all packages
apt install tool   # Install a package
dpkg -i package.deb  # Install a .deb package
```
# Arch-based (BlackArch, Manjaro)
```bash
pacman -Syu        # Update system
pacman -S tool     # Install a package
```
# RedHat-based (CentOS, Fedora)
```bash
yum install tool   # Install a package
dnf install tool   # Install a package (Fedora)
```
## 📜 Logging & Monitoring
```bash
dmesg | tail      # View kernel logs
journalctl -xe    # View system logs
cat /var/log/syslog  # View system logs (Debian-based)
tail -f /var/log/auth.log  # View authentication logs
```
## 🕵️‍♂️ Anonymity & Privacy
```bash
tor                # Start Tor service
proxychains nmap -sS target  # Run commands through Tor
anonsurf start     # Enable anonymous mode (Parrot OS)
curl ifconfig.me   # Check your public IP
```
### Contributing
We welcome contributions to improve this command list. If you'd like to contribute, Feel free to submit issues or pull requests to improve.

## 📫 How to Reach Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdullahismail)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ab5875176@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/cyb3ralpha)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cyb3ralpha)
