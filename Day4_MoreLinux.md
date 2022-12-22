# 💻 Linux File Hierarchy
- linux/UNIX file have a special file system than windows.

> linux:- system files appear under the **root directory**

## Linux file structures
1️⃣, /(root)
 - every single file and directory starts from the root directory
 - the only root user has the right to write under this directory

2️⃣, bin ( binary executables)
 - essential command binaries that need to be available in single-user-mode; for all users

3️⃣, /boot(boot loader files)
 - kernel initrd.vmlinux,grub files are located under **/boot**

4️⃣,  /dev (development files)
 - these includes terminal devices, usb, or any devices attached to the system.

5️⃣, /etc (etcetera)

 - contains configuration files required by all programs.
6️⃣, /home (home directory)
-home directories for all users to store their personal files.


7️⃣, /lib ( libraries essential for the binaries in /bin and /sbin)

 - library filenames are either id* or lib*.so*

8️⃣, /media ( mount points for removable media such as CD-ROMs)

- temporary mount directory for removable devices.

9️⃣ , /mnt (temporarily mounted file)

- temporary mount directory where sysadmins can mount filesystems.

1️⃣0️⃣, /opt ( optional application software packages)
 - contains add-on applications from individual vendors.
 > add-on applications should be installed under either /opt/ or /opt/sub-directory

1️⃣1️⃣, /sbin (essential system binaries)
 - just like/bin, /sbin also contains binary executables.
 > the linux commands located under this directory are used typically by system administrator, for system maintanance purpose.

1️⃣2️⃣, /tmp ( temporary files)
 - directory that contains temporary files created by system and users.
 > files under this directory are **deleted** when system is rebooted.

1️⃣3️⃣, /usr ( user utilities)
 - contains binaries , libraries, documentation, and source-code for second level programs.

## Text Editors
> linux command line text editors
 - VIM
 - nano
 - emacs
 - neovim

>linux graphical text editors

 - sublime
 - vscode
 - gedit
 - pluma


# Linux user management 
> every user habe GROUP

>  > But if users want to have a root access they add **SUDO** **( super- user do)**infront of the command 


## creating users

- useradd ->> simple
- Adduser ->> more Detailed

> to access root user 
 - > **sudo su**

