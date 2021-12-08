# Linux Guide For All

### Table of Content
- [What is Unix?](#what-is-unix)
- [What is Linux?](#what-is-linux)
- [Where is Linux?](#where-is-linux)
- [Who Uses Linux?](#who-uses-linux)
- [List of some popular linux distributions.](#some-linux-distro)
- [Comparison between Windows and Linux](#linux-vs-windows)
- [Points to remember while using linux](#points-to-remember-while-using-linux)
- [Linux File System Explained](#file-system-in-linux)
- [Linux Commands For All](#linux-commands-for-all)

### Before You Begin!
- [How To Install Linux In Your Computer? | Watch Video Tutorial Here👈](https://youtu.be/a7WFvniGGxQ)
- [Learn Linux In Nepali | Full Playlist Here👈](https://www.youtube.com/playlist?list=PL2OJkQtHPRidnlAitTMpRPh_LkyjHJvRC)
- [Get PDF HANDBOOK of this Guide for Offline Reading](/Assets/Pdfs/Linux-Guide-For-All.pdf).

---
---

# What Is Unix
Unix comes before linux, so if you know a little bit, it will be great for you. Unix is an operating system whose development started in 1969 for multi-user, multi-tasking. Unix is not free and open source os. It can be only utilized by its copywriters. So linux came into the picture.
Some examples of unix operating systems are: SunOS, Solaris, SCO Unix, HP/UX.


# What Is Linux
To understand simply, like Windows, Mac, Linux is an operating system \[OS\] based on Linux Kernel. Operating systems lie between computer hardware and computer users, so that users can interact with computers easily.  It was developed by Linus Torvalds in 1991.
It is free and open source means you can use it for free, view its source code. We can change the source code of linux and use it for personal as well as commercial purposes.

E.g: Ubuntu, Arch Linux, Debian GNU etc.


# Where Is Linux
- TV
- Mobile Phones
- Self Driving Car
- Plane
- Rocket
- Super Computers
- Servers (Many websites are hosted on Linux.)

# Who Uses Linux
- US Government 
- Top Tech Companies like Google, Microsoft, Amazon by various means
- Hackers and cybersecurity experts
- Financial Institutes
- Computer Programmers and Researchers
- Those who want to acquire high technical knowledge

# Some Linux Distro
- Ubuntu
- Fedora
- Elementory OS
- Red Hat OS
- Cent OS
- Kali Linux
- Arch Linux
- Gentoo Linux
- Void Linux
- Linux From Scratch (LFS)

# Linux Vs Windows
- Linux runs for months or years without reboot, but in windows often reboot is required.
- Most of the software is available for windows but not in linux. 
- Linux is Secure than windows.
- Linux is Fully Customizable but Windows is not.
- Linux is Free and open source But Windows is Paid and proprietary (closed source). 
  <details><summary>Are all linux based OS free?</summary>
  No, not all linux based OS are free. Enterprise level linux based operating systems are paid. E.g Red Hat Enterprise Linux(generally used at servers) is a paid OS; if we have a problem the Red Hat team will support and provide us a solution.</details>

 
### Windows Filesystem Vs Linux Filesystem
![windows vs linux file system image](Assets/Images/linux-vs-windows-file-structure.png)

# Points To Remember While Using Linux
- Folder in linux is called directory and shortly denoted as dir.
- Linux is a case sensitive System. A is different than a. E.g: `linux.txt` and `Linux.txt` are two different files in linux.
- Avoid using filename as space.
- Super Admin/Super User is also called root who can do anything.
- Software is called a package.
- Be careful while using `sudo` command. Don't use `sudo` unless you know what does the command actually do. Wrong commands with `sudo` can break your system. Eg: `sudo rm -Rf /` removes everything from your system including your operating system.

# File System In Linux
![linux file system explained](Assets/Images/linux-filesystem.png)

### Linux File Hierarchy Standard
| Path     | Content                             |
| -------- | ----------------------------------- |
| `/bin`   | Binaries (User)                     |
| `/root`  | Files of root user                  |
| `/boot`  | Static boot loader files            |
| `/etc`   | Host specific configs               |
| `/lib`   | Shared libraries and kernel modules |
| `/sbin`  | Binaries (System/root)              |
| `/var`   | Varying files (e.g. Logs)           |
| `/usr`   | 3rd party (User Installed) software |
| `/proc`  | Pseudo file system                  |
| `/sys`   | Pseudo file system                  |
| `/mnt`   | Mountpoint for internal drives      |
| `/media` | Mountpoint for external drives      |
| `/home`  | User homes                          |
| `/run`   | PID files of running processes      |

---
---

# Linux Commands For All
*NOTE: Emojis ⚪ and ⚫ are used only to easily differentiate between different commands and make the reading easy. They do not have anything to do with the actual commands.*

**Help And Manuals**
| Command | Example | Description | 
| :------ | :------ | :-----------|
| `man <command>` |⚪ `man cd`<br>⚫ `man ls` | Read help/manual of a particular command.<br>(close with <kbd>q</kbd>)|
|⚪ `<command> --help`<br>⚫ `<command> -h`|⚪ `ls --help`<br>⚫ `cd -h`|Also **help**.|
|`sudo <command>`|⚪ `sudo reboot`<br>⚫ `sudo rm a.txt` |Run commands as super user/Forcefully do a task.<br>⚪ Forcefully restart your system.<br>⚫ Forcefully remove a.txt.<br>`sudo` is basically used to perform tasks<br>that cannot be done by a regular user. |
|<kbd>Tab</kbd> (1x or 2x) |⚪ <code>cle<kbd>Tab</kbd></code><br>⚫ <code>cd Dow<kbd>Tab</kbd></code> |Auto completion.<br>⚪ when pressed <code>cle<kbd>Tab</kbd></code>,<br>it autocompletes the command to `clear`<br>⚫ when pressed <code>cd Dow<kbd>Tab</kbd></code>,<br>it autocompletes the command to `cd Downloads/`|
|<kbd>↑</kbd>|&nbsp;|See previous command.|
|<kbd>Ctrl</kbd>+<kbd>C</kbd>| |Kill the current process or command.|
|<kbd>Ctrl</kbd>+<kbd>R</kbd>| |Search through your history.<br>Start typing and it will auto-complete.<br> Hit <kbd>Ctrl</kbd>+<kbd>r</kbd> again,<br>and it will cycle though the other auto-completion options.<br>Hit <kbd>Enter</kbd> and the command will execute.<br> Hit <kbd>←</kbd>,<kbd>→</kbd> to edit commands.|

---

**Basic Commands**
| Command 	| Description                                                       |
| --------- | ----------------------------------------------------------------- |
| `whoami`  | Display current user name                                         |
| `hostname`| Display current host name                                         |
| `date`    | Display current date and time                                     |
| `clear`   | Clear Screen (Clear contents in currently open terminal emulator) |
| `users`   | Display Currently logged in user/s                                |
| `reboot`  | Restart your machine                                              |
| `poweroff`| Shut down your machine                                            |
| `pwd`     | Display Current/Working directory                                 |

---

**Linux Everyday Commands**

| Command | Example			 | Description                                       |
| ------- | ------------ | ------------------------------------------------- |
| `mkdir` |⚪ `mkdir LinuxGuide`<br>⚫ `mkdir a b c d`<br>⚪ `mkdir {A..Z}`<br>⚫ `mkdir -p Linux/Guide/Pdfs`|⚪ Create a directory named LinuxGuide.<br>⚫ Create directories a, b, c,d.<br>⚪ Create directories from A to Z at once.<br>⚫ Create directories with parent/s (directory inside a directory).|
| `cd`    |⚪ `cd LinuxGuide`<br>⚫ `cd Linux/Guide/Pdfs`<br>⚪ `cd ..`<br>⚫ `cd ../..`<br>⚪ `cd ~`<br>⚫ `cd -`|⚪ Navigate to LinuxGuide directory.<br>⚫ Navigate to Linux/Guide/Pdfs directory.<br>⚪ Navigate one directory backward.<br>⚫ Navigate two directories backward.<br>⚪ Navigate to home.<br>⚫ Navigate to last directory.|
| `ls`    |⚪ `ls`<br>⚫ `ls -a`<br>⚪ `ls -l`<br>⚫ `ls -r`<br>⚪ `ls -R`<br>⚫ `ls -S`<br>⚪ `ls -t`|⚪ List all the contents of the directory.<br>⚫ Show hidden items.<br>⚪ Format as lists.<br>⚫ Invert Order.<br>⚪ Recurse. (Quiet similar to tree listing)<br>⚫ Sort by size.<br>⚪ Sort by date modified.|
|         |`ls -Sal`|Different options can be combied.<br>Here `ls -Sal` shows all contents in the directory<br>including hidden items in a list format according to size.|
| `rmdir` |⚪ `rmdir Linux`<br>⚫ `rmdir -p Linux/Assets/Pdfs`|⚪ Remove an empty directory named Linux.<br>⚫ Removes `Pdfs` directory & its ancestor dirs<br>(empty dirs only) |
| `echo`  |`echo "Hello!"`| Displays Hello!(Display a line of text)	 |
| `touch` |⚪ `touch a.html`<br>⚫ `touch ch{1..9}.txt`|Change timestamps of any kind of file.<br>⚪ Create a file `a.html`.<br>⚫ Create files ch1.txt to ch9.txt. <br>Update the access and modification times<br>of each FILE to the current time.|
| `cat`   | `cat a.txt` 			| Print content of file a.txt (top to bottom) |
| `tac`   | `tac a.txt` 			| Print content of file a.txt in reverse (bottom to top) |
| `cp`	  |⚪ `cp source destination`<br>⚫ `cp -r source destination` |⚪ Copy file from source to destination location.<br>⚫ Copy folder (recursively)|
| `mv`    | `mv sourcefile destination` | Move file and folders from source to destination.	|
| `rm`    |⚪ `rm a.txt`<br>⚫ `rm -r Linux/`<br>⚪`rm -rf Linux/`<br>⚫ `rm *.jpg` |⚪ Remove file `a.txt`<br>⚫ Remove non-empty direstory `Linux`.<br>⚪ Force remove non empty directory `Linux`.<br>⚫ Remove all .jpg files within the directory. |
| `find`  |⚪ `find -iname filepattern`<br>⚫ `find -mmin n`<br>⚪ `find -mtime n`<br>⚫ `find -regex pattern`<br>⚪ `find -size n[kMG]`<br>⚫ `find ! searchparams` |⚪ Search dir/file case-insensitive<br>⚫ Last modified n minutes ago<br>⚪ Last modified n days ago<br>⚫ Path matches pattern<br>⚪ By file size (`-n` less than; `+n` greater than)<br>⚫ Invert search |
| `locate`| `locate file` | find your file by name(faster than find)<br>(Must run `sudo updatedb` before using this command) |
| `sort`  | ⚪ `sort file`<br>⚫ `sort -ru file`|⚪ Display sorted contents of file.<br>⚫ Print sorted descending without dublicates.|
| `uniq`  | `uniq file` 			| Hide consecutive identical lines. |
| `wc`    |⚪ `wc file`<br>⚫`wc -l file`|⚪ Count Lines, Words, Chars (Bytes) in file<br>⚫ Count Lines in file. (-w/-c for words/characters) |

---

### Stream Redirection
#### STDOUT (Standard Output Stream)
- `>` overwrite
- `>>` append

#### STDIN (Standard Input Stream)
- `<` input

*For examples:*
| Command                           | Description |
| --------------------------------- | ----------- |
| `echo "I LOVE LINUX" > a.txt` 	  | Creates a.txt if it doesn't exist and writes `I LOVE LINUX` inside a.txt<br>If a.txt exists already, overwrites the content inside it with `I LOVE LINUX`. |
| `echo "LINUX IN NEPALI" >> b.txt` | Creates b.txt if it doesn't exist and writes `LINUX IN NEPALI` inside b.txt.<br>If b.txt exists already, it appends `LINUX IN NEPALI` to a new line<br>without overwrithing/erasing the previous contents in the file. |
| `wc -l < a.txt` | As you should know what does `wc -l` do,<br>it shows the number of lines in a file.<br>Here `wc -l` takes `a.txt` as input file to count the lines of.|

---

### Check Memory Stats and CUP Stats as Linux Admin
| Command | Example    | Description | 
| :------ | :--------- | :-----------|
| `free`  |⚪ `free -m`<br>⚫ `free -g`<br>⚪ `free -h`|⚪ Display amount of free & used memory in Megabytes.<br>⚫ Display amount of free & used memory in Gigabytes.<br>⚪ Display amount of free & used memory in human readable format.|
| `vmstat`|⚪ `vmstat -a`<br>⚫ `vmstat -d`<br>⚪ `vmstat -D`|⚪ Display active/inactive/virtual memory status.<br>⚫ Display disk stastistics.<br>⚪ Display summarized disk stastistics.|

---

### Add And Remove User Account In Linux
Linux is a multi-user operating system, which means that more than one user can use Linux at the same time. Linux provides a beautiful mechanism to manage users in a system. One of the most important roles of a system administrator is to manage the users and groups in a system.

Super User permission is required to add/remove user; So, `sudo` should be used before following commands:

| Command   | Example 		    | 		Description 								         |
| --------- | --------------- | ---------------------------------------- |
| `useradd` | `useradd brp`   | Create a new user account named `brp`.	 |
| `passwd`  | `passwd brp`    | Add/change password for user `brp`.      |
| `userdel` | `userdel -r brp`| Delete user named `brp` from the system. |

---
