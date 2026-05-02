# linux notes

## core concepts

- linux is a multi-user operating system  
- everything is treated as a file  
- permissions control access to files and directories  
- the command line is the main way to interact with the system  

---

## file system structure

- / → root directory  
- /home → user directories  
- /etc → configuration files  
- /var → logs and system data  
- /bin → essential commands  

---

## navigation commands

pwd        # show current directory  
ls         # list files  
ls -la     # list all files with details  
cd         # change directory  
cd ..      # go up one directory  
cd ~       # go to home directory  

---

## file and directory management

touch file.txt         # create file  
mkdir folder           # create directory  
rm file.txt            # delete file  
rm -r folder           # delete directory  
cp file1 file2         # copy file  
mv file1 file2         # move or rename file  

---

## viewing and editing files

cat file.txt           # display file contents  
less file.txt          # view file page by page  
head file.txt          # first lines  
tail file.txt          # last lines  
nano file.txt          # edit file  

---

## file permissions

- read (r) → view file contents  
- write (w) → modify file  
- execute (x) → run file  

example:  
-rwxr-xr-x  

chmod 755 file  
chmod +x script.sh  
chown user:file file  

---

## users and privileges

whoami  
id  
sudo -l  

- root = full control  
- users = limited access  
- sudo = temporary admin access  

---

## process management

ps aux                # list processes  
top                   # live process view  
kill <pid>            # terminate process  
kill -9 <pid>         # force kill  

---

## service management

systemctl status ssh  
systemctl start ssh  
systemctl stop ssh  
systemctl enable ssh  

---

## networking basics

ip a                  # show ip address  
ping google.com       # test connectivity  
netstat -tuln         # open ports  
ss -tuln              # modern alternative  

---

## package management

apt update  
apt upgrade  
apt install <package>  
apt remove <package>  

---

## logs and monitoring

- logs are stored in /var/log  

cat /var/log/syslog  
tail -f /var/log/syslog  

---

## useful tips

- tab → autocomplete  
- arrow keys → command history  
- ctrl + c → stop command  
- ctrl + l → clear screen  

---

## notes

still building confidence with command-line usage, permissions, and system behavior
