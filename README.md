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
