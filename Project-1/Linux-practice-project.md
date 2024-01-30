## LINUX PRACTICE PROJECTS
### Introduction to Linux and Basic Commands 
### Pre-requisites: I spinned up an Ec2 instance and my virtual server is Ubuntu
#### A Linux command is a program or utility that runs on the command line interface - a console that interacts with the system via texts and processes.
##### Note: All Linux commands are case-sensitive.
## File manipulation
### Command: sudo apt update.
##### I ran this command to update the local package database on my system. this help enable information about the latest versions of packages available and that can be upgraded.
<img width="776" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/eba8a17a-40d5-43bd-b384-ea8cd55d4c3f">



### Command: apt list --upgradable
##### I ran this command to list the upgradable packages on my system. it shows the packages for which updated versions are available in the repositories that has been configured.
<img width="573" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/f6064949-042e-43b6-a101-cd6e7dd9ee10">


### Command: sudo apt upgrade. 
##### I ran this command to upgrade the installed packages on my Ubuntu Linux server. This was done to ensure that my system has the latest bugs fixed, security updates and feature improvements of the software.

<img width="457" alt="One" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/1d8a190d-b1f4-4330-b093-b1279407c2ca">

### Command: ls
##### The ls command lists files and directories within a system. Running it without a flag will show the current working directory's content. To see other directories' content, i used ls followed by the desired path.
<img width="350" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/c2f378a8-7999-4b9a-89a1-dc2e1f99ae1f">
<img width="843" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/46bfd0bf-2edd-4a04-9c04-b44079a8a966">



##### Using ls with the option -R lists all the files in the subdirectories.
<img width="722" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/a57b8b57-e5c7-4808-bd9e-42700f0f590b">

##### Using ls with  the option -a shows hidden files in addition to the visible ones.
<img width="851" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/32283451-8bad-47cc-88fa-a07939124821">


##### Using ls with the option -lh shows the file size in easily readable formats, such as KB,MB,GB and TB.
<img width="436" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/f95fcebb-6901-4d22-a16f-68d7b098aabe">


### Command: cd
##### This command was used to change into a directory. To navigate through the linux files and directories, the command cd is used. Depending on your current working directory, it requires either a full path or the directory name. However running this command without an option will take you to the home directory of the current working user and this is equivalent to just running the cd command alone, using the cd - moves to your previous directory and cd .. moves you to the parent directory of the current working directory.
<img width="414" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/1f9d5fba-49c7-4f7c-a851-4bda3c005a63">


### Command: pwd
##### Meaning print current working directory, this command was ran to find the path of the current/present working directory.
<img width="359" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/451c6846-d2b6-4470-ab2c-7b476d73b08c">

### Command: cat
##### The Concatenate command is used to list combine or merge and write file content to the standard output in other words to display the contents of a file in the terminal. i ran this command followed by the file i wanted to display on the screen.
<img width="742" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/e3a530ac-54ee-4de6-843f-8e8ede69c5c4">

##### I ran it as tac to display the content of the file in reverse order.
<img width="730" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/d0dc8bf4-52b6-4e16-9e02-bda96150e0a0">


##### I ran it to merge two files and store the output in another file.
<img width="854" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/dd2ea284-3037-4f54-a796-ccf13f73b760">





### Command: cp
##### The cp command is used to copy files or directories and their contents. I ran the cp command followed by the destination directory to copy the file to the directory.
<img width="791" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/07952897-4572-4eab-b59a-0ff520324b2e">

##### I ran it to copy the content of one file to another in the same directory.
<img width="467" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/31fb5ea6-2aaa-4bf0-9d27-7216e3a014ee">


##### I ran it to copy an entire directory using the -R flag before typing the source directory, followed by the destination directory.
<img width="574" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/9acb1680-c50a-4b42-8c81-ba3ad82a7471">

### Command: mv
##### The primary use of the mv command is to move and rename files and directories. Additionally, it doesn't produce an output upon execution. The mv command can also be used to rename a file.
##### I ran it followed by the file name and destination directory.
<img width="506" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/cc526282-b5f9-40f4-8c4e-acd6cb125bfe">

##### I ran it to rename a file by running th ecommand followed by the old_file_name and the new_file_name.
<img width="497" alt="Screenshot 2024-01-16 084547" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/e215b541-3abf-467f-bb0d-5f1415cbb8ec">

### Command: mkdir
##### This command is used to create one or multiple directories at once and set permissions for each of them. The user executing this command must have priviledge to make a new folder in the parent directory, or they may recieve a permission denied error.
##### I ran the command mkdir followed by the name of the new directory i created.
<img width="514" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/f653f1c7-a13d-4f74-9e2f-e16f9beda9d1">

##### To create a new directory inside the one that is already created. I ran the mkdir with the old_directory/new_directory.

##### To create a directory between two existing folders. I ran the mkdir command followed by the option -p in the format mkdir -p Process/Registration.
<img width="536" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/da7e7866-f0a5-4063-b4d4-454eb8cb5007">


##### To create a directory with full read,write, and execute permissions for all users. I ran the mkdir command followed by the option -m in the format mkdir -m777 Directory_name.
<img width="494" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/d50e5290-40d5-4b54-b71b-b1fde2b1eb0a">


### Command: rmdir
##### This command is used to permanently delete an empty directory. However, the user running this command should have sudo priviledges in the parent directory.
##### To delete an empty directory, i ran the rmdir command rmdir followed by the name of the empty directory.

##### To Delete an empty directory and sub_directory. I ran the rmdir command followed by the option -p in the format rmdir -p directory/sub_directory.
<img width="544" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/4a314628-d956-404d-b771-dadb63f3de7e">

### Command: touch
##### This command is used to create an empty file if it does not exist. It is also used to update the access and modification timestamps of a file or multiple files. To create a "hidden" file, enter touch ".filename". Any directory or file that begins with a period character is hidden.
<img width="872" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/73c2afb9-a4b0-43f4-922b-a1dee20589ae">
<img width="852" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/ed0ffc1e-622b-4258-aab4-dbcaecc6a31b">

### Command: rm
##### This command is used to delete files within a directory. However the user this command has to have write permissions.
##### To remove a file i ran the rm command followed by the name of the file.
<img width="791" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/67e9d707-f339-4b8d-9d1e-f1c3ce864bd5">
<img width="826" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/9ec5bbca-3d03-4991-a7d5-d298175eb081">
<img width="421" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/6de6a2f4-78db-4bcc-809c-cf49ab996f9a">

##### To remove multiple files. I ran the rm command followed by the file names.
<img width="758" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/01e331f5-2705-4612-9e40-553bb772dfde">

##### It can also be used to empty a directory using an asterisk at the end of the directory after typing in the command as can be seen below:
<img width="473" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/82f0dfee-0465-4980-98e3-07d2270a5f25">


### Command: locate
##### This command is used to find the location of a file or directory on the database. Adding the -i argument will turn off case sensitivity, so you can search for a file even if you do not remember its exact name.

<img width="421" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/d306680b-ed6a-4cff-9933-cb46637dda37">


<img width="627" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/2e68e0df-7616-408c-87b1-023606671fb1">

##### The command locate relies on a pre-built of files, which makes it faster than some other methods of searching and because of this, the locate command might not be able to find files that have recently or files in the directory that the system has not indexed yet. To update the index we use the updatedb command. 


### Command: find
##### This command is used to search for files within a specific directory also directories in a directory hierachy based on various criteria and perform subsequent operations. This command can be used to search for files by their name, type also files that have been modified within the last n days, files that are larger than a specified size.

<img width="403" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/38c14e06-95af-477e-a88c-6105c93a1c96">

<img width="596" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/fe4d35ce-747c-4d2a-9678-18743469ba37">

<img width="520" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/c0ff1862-284f-4884-800e-b08e87357ec5">

<img width="479" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/8133f9e0-a801-4fed-8610-faf0f1f92fe7">

<img width="584" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/b7f3eb43-a889-4cf6-9a82-ee6f25c5b04d">

### Command:grep
##### This command is used to search for a text by searching through all the texts in a specific file. Once the grep command finds a match, its print all the lines that contain the specific pattern. This command helps filter through large log files.
<img width="498" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/dc661402-eed7-4196-a4f6-4d9993bac786">



### Command: df
##### This command is used to report the system's disk space usage, it is shown in percentage and kilobyte. Adding the argument -h will enable you see the current directory's system disk space usage in a human readable format.
<img width="492" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/56f27c71-00a9-4c8b-a64b-2b61b3f81a7e">


### Command: du
##### This command allows you check how much space a file or a directory takes up. This allows you identify the part of the system that uses the storage excessively. Adding the flag -s shows you the total size pf a specified folder and -h informs the last modification date of the displayed folders and files.

### Command: head
##### This command is used to view the first ten lines of a text. Adding an option lets you change the number of lines shown. the head command is also used to output piped data to the CLI.
<img width="710" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/7af10a16-c66b-4e82-b121-993802393afb">


### Command: tail
##### This command displays the last few lines of a file. it allows users to check whether a file has new data or to read error messages. By default, running this command will show the last 10 lines of a file but you can adjust the number of lines by using the option -n.
<img width="714" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/68a8c7be-2d3c-4aa6-8b4e-a8231efdf6a4">

### Command: diff
##### This command is used to compare the context of 2 text files and display the differences between them. It is useful to help identify the changes between different version of a file. Developers often use the diff command to alter a program instead of rewriting the entire source code.

### Command: tar
##### This command is used to create, view and manipulate archive files. The tar command archives multiple files into a tar file which is a common Linux format similar to ZIP, with optional compression.
<img width="662" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/b30f3b53-08f3-4dad-829d-e5234eb382d2">

### Command: cut
##### This is a text processor command it allows you cut the output by taking  the input of a command or if you're reading the content of a file and cuts it to desired output.

### Command: awk
##### This is a command or utility/language designed for data extraction . Most of the time it is used to extract fields from a file or from an output. This command allows you to list by the columns.

### Command: sort
##### This a text processor command that sorts out the output in an alphabetical order.

### Command: uniq
##### This is a text processor command that  remove all duplicates in a file

### Command: wc
##### This is a text processor command that stands for word count. It tells us how many words, letters and lines you have in a file. The command reads either standard input or a list of files and generates: newline count, word count and byte count. you can use the options -l, -w and -c for number of lines, words and bytes.
<img width="442" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/b134cbc6-2c47-4214-8ada-dd6ddf93c91f">


## File Permissions and ownership
### Command:chmod
##### This command is used to modify a file or directory's read, write,and execute permissions. In Linux, each file is associated with three user classes - owner, group member, and others.

<img width="515" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/a47500ca-d441-49a6-a2bf-88da4fd323e0">

##### This permissions can be represented in two different formats which are in octal and alphabetical formats. To display this permission in octal format we use the command: stat -c %a file or directory name.
<img width="359" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/0e30cda8-97d5-4b44-a0eb-13e7080a5c14">

##### To see the permissions of the text file we run the ls -l command against the file or directory. The text file will have the permissions alphabetically displayed. The first character shows whether the file system is a file or directory. - for a file and d for a directory followed by a string of characters which is usually 3 groups of three characters.Each group of characters shows the permissions for user, group and others which corresponds to r for read permission, w for write permission and x for execute permission if any of them is a dash then that permission is denied.

##### I ran the chmod command to give and take execution permission to group users to the Revival_pharm directory.
<img width="521" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/d27992fd-6a7e-4f32-889b-2bc68bba0dc3">

 
### Command:Chown an abbreviation of "change owner"
##### This command lets you change the ownership of file, directory, or symbolic link to a specified username. To change the file to owned by the root user, we run the command: sudo chown root text-file. sudo is a command that lets me execute another command as another user. By default without another user specified, it will execute the second command as a super user.
##### To verify the change of ownership, enter ls -l command. I ran the chown command to change the Devops/ ownership to root.

<img width="632" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/3bc4f9c5-95d1-4703-83d8-93535e6ec07f">

##### To change both user and group we enter the command: sudo chown root:root text-file.
<img width="639" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/c8e178df-cfd1-4d42-8d93-e4dea19617f7">




### Command: jobs
##### A job is a process that the shell starts. The jobs command will display all the running processes along with their statuses. Remember that this command is only available in csh, bash,tcsh and ksh shells.
<img width="338" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/b8df6825-22ff-4788-9951-21f3364509f6">


### Command: kill
##### This command is used terminate an unresponsive program manually. it will signal misbehaving applications and instruct them to close their processes. To kill a program, you must know its processs identification number PID. If you don't know the PID, If you don't know the PID, run the following command. command: ps ux after knowing what signal to use and the program 's PID, enter the kill signal.

<img width="751" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/cb5ff5b9-ce0f-47a5-8c8d-ae431850e0a4">

### Command:ping
##### This command is one of the most used basic Linux commands for checking whether a network or a server is reachable, it is used to troubleshoot various connectivity issues.
<img width="677" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/b3a826f9-9405-47f9-8a00-6998a07530eb">

### Command:wget
##### This command lets you download files from the internet using the wget command. it works in the background without hindering other running processes. The wget command retrieves files using HTTP,HTTPS and FTP protocols. It can perform recursive downloads, which transfer website parts by following directory structures and links, creating local versions of the web pages.
<img width="818" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/162fc408-d924-47e4-8869-8e6745c5cb9c">

### Command:uname
##### This command is used to print detailed information about your linux system and hardware. This includes the machine name, operating system, and kernel. 
<img width="415" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/cdcf46aa-c0e8-40e7-9822-175b3fc77a05">


### Command: top
##### This command is used to display all the running processes and a dynamic real-time view of the current system. its sums up the resource utilization, from CPU to memory usage. It can also help you identify and terminate a process that may use too many resources.

<img width="854" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/09e50ecd-ca1d-47bc-8afb-dbcc4898a796">


### Command: history
##### This command list up to 500 previously executed commands, allowing you to reuse them without re-entering the commands. Only users with sudo privileges can execute this command. 

<img width="538" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/cdaded26-e2ec-4add-8569-345afe556970">


### Command: man
##### This command provides a user manual of any command or utility you can run in the terminal, including the name, description and options. It  consists of nine sections: executable programs or shell commands System calls Library calls Games special files, File formats and conventions System administration commands Kernel routines Miscellaneous.
<img width="274" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/537bab94-89d9-4dfd-9f9a-364990d9b5e1">
<img width="752" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/d459241d-cce6-475a-aed4-71c6dabb6b3b">

### Command:echo
##### This command is a built-in utility that displays a line of text or string using the standard output.
<img width="414" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/e2c86cc6-6cd3-4030-9c3c-2c9a929f7b3c">

### Command: zip, unzip
##### The zip command is used to compress your files into ZIP file, a universal format commonly used on Linux.it can automatically choose the compression ratio. The zip command is also useful for achiving files and directories and reducing disk usage.

### Command: hostname
##### This command is used to know the system's hostname. It can be executed with or without an option.
<img width="436" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/4c83af24-531b-4a53-af39-b1d647fabe23">

### Command: useradd,userdel
##### The command useradd is used to create a new account, while the passwd command allows you to add a password. Only those with root privileges or sudo can run the useradd command.

### Command: apt-get
##### This command is used for Advanced Package Tool libraries. it lets you retrieve information and bundles from authenticated sources to manage, update,remove, and install software and its dependencies. Running the apt-get command requires you to use sudo or root privileges.


### Command: nano,vi,jed
##### Linuz allows users to edit and manages files via a text editor, such as nano, vi, or jed. nano and vi come with the operating system,while jed has to be installed.

### Command: alias, unalias
##### This command allows you to create a shortcut with the same functionality as a command, file name, or text. When executed, it instructs the shell to replace one string with another.

### Command: su
##### This command allows you to run a program as a different user. It changes the administrative account in the current log-in session. This command is especially beneficial for accessing the system through SSH or using the GUI display manager when the root user is unavailable.
<img width="329" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/c2672f68-e775-4033-b1e6-4cbf8309cff1">

### Command: htop
##### This is an interactive program that monitors system resources and server processes in real time. It is available on most Linux distributions, and you can install it using the default package manager. Compared to the top command, htop has many improvements and additional features, such as mouse operation and visual indicators.

<img width="466" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/42b7d991-701c-451e-a0a8-5c89bcf94578">
<img width="854" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/c97a4d00-285a-496c-bbd6-f06c145ebac6">

### Command: ps
##### This command produces a snapshot of all running processes in your system. The static results are taken from the virtual files in the /proc file system. Executing the ps command without an option or argument will list the running processes in the shell along with:

<img width="538" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/8b9f2ccc-d6cd-4a28-8ea9-5db7d912b09a">

##### The unique process ID the type of the terminal TTY The running time TIME The command that launches the process CMD.
