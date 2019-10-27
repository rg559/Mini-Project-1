## Terminal Commands

- **CD:** Change directory is used to browse through different folders and directories through terminal. This command makes              it easy for the user to browse through different parts of computer without using much effort and is much faster                than using a mouse.

 **Syntax:** &nbsp;&nbsp;&nbsp;*cd directory*

- **mkdir:** The mkdir command in UNIX allows users to create directories or folders as they are referred to in some operating systems. This command can create multiple directories at once and also set permissions when creating the directory.

**Syntax:** &nbsp;&nbsp;&nbsp;*mkdir newdir  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   mkdir new1 new2 new3*

![syntax for mkdir](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-from-2018-12-11-17-50-45.png)


- **CP:** The CP command is used to copy any file from one folder to other. This commands makes it easy to copy files, especially when dealing with multiple files in a folder, without having to browse for the specific file in a folder and hence saving time.

**Syntax:** &nbsp;&nbsp;&nbsp; *cp source destination*

- **pwd:** pwd stands for Print Working Directory. It prints the path of the working directory, starting from the root.

**Syntax:** &nbsp;&nbsp;&nbsp; *pwd*

![syntax for pwd](http://www.cellbiol.com/bioinformatics_web_development/wp-content/uploads/2017/01/shell_pwd_screenshot.png)

- **mv:** mv stands for move. mv is used to move one or more files or directories from one place to another in file system. It can also be used to rename a file.

**Syntax:** &nbsp;&nbsp;&nbsp; *mv [option] source destination*

![syntax for mv](https://linoxide.com/wp-content/uploads/2014/01/mv_directory.png)

- **rm:** rm stands for remove. rm command is used to remove objects such as files, directories, symbolic links and so on from the file system. To be more precise, rm removes references to objects from the filesystem, where those objects might have had multiple references (for example, a file with two different names).

**Syntax:** &nbsp;&nbsp;&nbsp; *rm dir1  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   rm dir1 dir2 dir3*

![syntax for rm](https://static.javatpoint.com/linux/images/linux-file-rm1.png)

- **history:** history command is used to view the previously executed command. In Bash shell history command shows the whole list of the command. It can also show the required number of commands as per user.

**Syntax:** &nbsp;&nbsp;&nbsp; *history  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   history 5*

![syntax for history](https://media.geeksforgeeks.org/wp-content/uploads/Screenshot-from-2018-12-14-07-13-54.png)


- **Home directory and tilde:** Users can navigate to their home directory by simply typing cd in terminal. The tilde(~) is used to refer to the home directory. 

- **File paths in Linux:** A path is a unique location to a file or a folder in a file system of an OS. A path to a file is a combination of / and alpha-numeric characters. There are two types of paths in linux: 

    1. **Absolute Path:** An absolute path is defined as the specifying the location of a file or directory from the root directory(/). In other words we can say absolute path is a complete path from start of actual filesystem from / directory.
Examples of Absolute path are: 

                               /var/ftp/pub

                               /etc/samba.smb.conf

                               /boot/grub/grub.conf

   2. **Relative Path:** Relative path is defined as path related to the present working directory(pwd). Suppose I am located in /var/log and I want to change directory to /var/log/kernel. 
Examples of Relative path are:  
   
                               pwd
                               /var/log
                               cd kernel
                              
 
- **Using the tab key to complete file paths:** The tab completion feature is extremely useful when you are accessing lengthy paths in your filesystem. It helps in completing the directory name or filename without having to type the entire length. You can use the tab key to autocomplete any path in the Finder Go To Folder window, so whether you’re trying to navigate to a local user directory, or some deeply embedded path in the file system, tab it out!

- **Using up and down arrow for history:** When working on terminal, the user can press up or down arrow key to access any commands previously used and stored in the history. This feature is helpful when accessing files while having to browse at multiple locations. The user can simply press up arrow to browse to the previous location. It can also be used to edit any commands with error by adding it on the terminal page first.
