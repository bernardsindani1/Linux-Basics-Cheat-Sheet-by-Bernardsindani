# Linux-Basics-Cheat-Sheet-by-Bernardsindani
A quick reference guide for daily Linux tasks. Handy for beginners and those who need a refresher.
# 🐧 Linux Basics Cheat Sheet

A handy reference for daily Linux tasks.  
This guide is meant for beginners and intermediate users who want quick commands for everyday use.

---

## 📂 File and Directory Management
# List files
ls
ls -la        # detailed list including hidden files

# Navigate directories
cd /path/to/directory
cd ..         # go up one level
cd ~          # go to home directory

# Create & remove
mkdir new_folder
rmdir empty_folder
rm -rf folder_name   # remove folder and contents (use with caution)

# Copy & move
cp file.txt /path/to/destination
mv file.txt /path/to/destination
📄 File Viewing & Editing
cat file.txt          # show content
less file.txt         # scroll through file
head -n 10 file.txt   # first 10 lines
tail -n 10 file.txt   # last 10 lines
nano file.txt         # edit file
vim file.txt          # edit with vim

🔍 Searching
find /path -name filename.txt   # find file by name
grep "text" file.txt            # search for text inside file
grep -r "text" /path            # recursive search in folder

⚙️ Permissions
ls -l                    # view permissions
chmod 755 file.sh        # change permissions
chown user:group file    # change ownership

📦 Package Management
Ubuntu/Debian
sudo apt update
sudo apt upgrade
sudo apt install package_name
sudo apt remove package_name

🌐 Networking
ping google.com
curl http://example.com
wget http://example.com/file.zip
ifconfig       # network info
ip addr show   # newer alternative

🖥️ System Monitoring
top           # real-time processes
htop          # better view (install first)
df -h         # disk usage
du -sh *      # folder sizes
free -h       # memory usage
uptime        # system load & uptime

👤 Users and Groups
whoami
id
adduser new_user
passwd username
usermod -aG groupname username

⚡ Useful Shortcuts
Ctrl + C   # stop running command
Ctrl + Z   # pause command
Ctrl + D   # logout/exit
!!         # repeat last command
history    # show command history
!123       # run command #123 from history
[Linux_CheatSheet.pdf](https://github.com/user-attachments/files/21822868/Linux_CheatSheet.pdf)
