<h2 style="color:blue;text-align:center;">Everything about Linux</h2>

Information and Install Linux on Oracle Virtual Box:
- **Setup-Instruction :** <a href="https://www.youtube.com/watch?v=v1JVqd8M3Yc">click here</a>
- **Download Virtualbox :** <a href="https://www.virtualbox.org/wiki/Downloads">check</a>
- **Download Linux :** <a href="https://ubuntu.com/download/desktop">Downloads</a>
- **Note :** Dont forget to eneble windows virtualization technology on Bios
- **Best Seller Course :** <a href="https://drive.google.com/drive/folders/1OQcRg7TROlXHLwG1wNmx7ib016wnSEDU?usp=sharing"> Click here to download</a>
 
## Lets talk about the Command 
---- check name of environment `uname`

#### 1. About Directory
- `pwd` check the current directory.
- `ls`check folder on directory  `ls -a` show hidden file also `ls -l` show details & `ls -la`, human readable`ls -lah`
-  `mkdir newFolder` make directory on folder, long folder `mkdir -p new/bdh/efgh/twi`
- `rmdir directory_name` delete empty directory 
- `rm -r directory_name` delete not empty directory, `rm -i files` delete multiple files
- `touch file.txt, touch file.py` create any file 
- `ls *.txt` present file which extention txt
- `mv file.py location` move file to anohrt path also rename in one another 
- `cp file3.txt file4.txt`, `cp -r file3 file4` both file content will be same and also copy to another location
-`locate filename`  find any file using 
- `clear`  erase the display.
- `echo I am Linux command writer >>file.txt` write something on text file
- `cat file.txt` display those contents like , `cat text1.txt, text2.txt, text3.txt ->all.txt` `cat all.txt` see all content in same file
- `nano file.txt`, `vi file.txt` to write content on nay file.
- `head file.txt`, `tail file.txt` view 10 first or 10 last row
- `wc file.txt` word and character in file
- `man --help` Check command and how it work

#### 2. Some Intermediate Command
- `df -m` check which file contain how much storage.
- `zip file_folder` to zip and `unzip` to unzipe file folder.
- `chmod +x file.py` a file on running mode, `sudo chmod +x file.py` to give root permission.
- `hostname`, `hostname -I` show hostname and ip Address.
- ` ping google.com` to check internet connection.
-  `sudo halt` to power off and reboot the computer by using the command  `sudo reboot`.
- `Ctrl C` stop `Ctrl Z` forcefully stop
- `uptime` run from how much times.
- ` free -h` current storage limit
- `man ps` `man file` check details about manual command

#### 3. Networking
- `ifconfig` to find that install `sudo apt install net-tools`
- `ip -a` to check ip and can manipulate by other commands.

#### 4. Packet Manager: 
- `sudo` stands for "SuperUser Do". So, if you want any command to be done with administrative or root privileges, you can use the sudo command. For example, if you want to edit a file like `viz. alsa-base.conf`, which needs root permissions `sudo nano alsa-base.conf.`, `sudo passwd` for change password.
- `sudo apt install file`  to install, check update `sudo apt update` do update `sudo apt upgrade` apt stand for advance packet manager tools.
- `sudo apt search` search package  and remove `sudo apt remove filename`

#### 5. User Athenication
- `id user` check details about user
- `sudo su` to go root user
- `which useradd` where we can add user
- `sudo useradd username` add any kind of user  --- main user can any sub user group

#### Random Command 
- `env`, ->`echo $PATH`, `alias`

