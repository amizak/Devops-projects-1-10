# LINUX PRACTICE PROJECTS
## Introduction to Linux and Basic Commands 
## Pre-requisites: I spinned up an Ec2 instance and my virtual server is Ubuntu
## A Linux command is a program or utility that runs on the command line interface - a console that interacts with the system via texts and processes.
## Note: All Linux commands are case-sensitive.
## File manipulation
##### Command: sudo apt update.
###### I ran this command to update the local package database on my system. this help enable information about the latest versions of packages available and that can be upgraded.
<img width="776" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/eba8a17a-40d5-43bd-b384-ea8cd55d4c3f">

##### Command: apt list --upgradable
###### I ran this command to list the upgradable packages on my system. it shows the packages for which updated versions are available in the repositories that has been configured.
<img width="573" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/f6064949-042e-43b6-a101-cd6e7dd9ee10">


##### Command: sudo apt upgrade. 
###### I ran this command to upgrade the installed packages on my Ubuntu Linux server. This was done to ensure that my system has the latest bugs fixed, security updates and feature improvements of the software.

<img width="457" alt="One" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/1d8a190d-b1f4-4330-b093-b1279407c2ca">

##### Command: ls
###### The ls command lists files and directories within a system. Running it without a flag will show the current working directory's content. To see other directories' content, i used ls followed by the desired path.
<img width="350" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/c2f378a8-7999-4b9a-89a1-dc2e1f99ae1f">


###### Using ls with the option -R lists all the files in the subdirectories.
<img width="722" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/a57b8b57-e5c7-4808-bd9e-42700f0f590b">

###### Using ls with  the option -a shows hidden files in addition to the visible ones.
<img width="851" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/32283451-8bad-47cc-88fa-a07939124821">


###### Using ls with the option -lh shows the file size in easily readable formats, such as KB,MB,GB and TB.
<img width="436" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/f95fcebb-6901-4d22-a16f-68d7b098aabe">


##### Command: cd
###### This command was used to change into a directory. To navigate through the linux files and directories, the command cd is used. Depending on your current working directory, it requires either a full path or the directory name. However running this command without an option will take you to the home directory of the current working user and this is equivalent to just running the cd command alone, using the cd - moves to your previous directory and cd .. moves you to the parent directory of the current working directory.
<img width="414" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/1f9d5fba-49c7-4f7c-a851-4bda3c005a63">


##### Command: pwd.
###### Meaning print current working directory, this command was ran to find the path of the current/present working directory.
<img width="359" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/451c6846-d2b6-4470-ab2c-7b476d73b08c">

##### Command: cat
###### The Concatenate command is used to list combine or merge and write file content to the standard output. i ran this command followed by the file i wanted to display on the screen.
<img width="742" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/e3a530ac-54ee-4de6-843f-8e8ede69c5c4">

###### I ran it as tac to display the content of the file in reverse order.
<img width="730" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/d0dc8bf4-52b6-4e16-9e02-bda96150e0a0">

###### I ran it to merge two files and store the output in another file.
<img width="854" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/dd2ea284-3037-4f54-a796-ccf13f73b760">





##### Command: cp
###### The cp command is used to copy files or directories and their contents. I ran the cp command followed by the destination directory to copy the file to the directory.
<img width="791" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/07952897-4572-4eab-b59a-0ff520324b2e">

###### I ran it to copy the content of one file to another in the same directory.
<img width="467" alt="image" src="https://github.com/amizak/Devops-projects-1-10/assets/139656919/31fb5ea6-2aaa-4bf0-9d27-7216e3a014ee">


###### I ran it to copy an entire directory using the -R flag before typing the source directory, followed by the destination directory.

##### Command: mv
###### The primary use of the mv command is to move and rename files and directories. Additionally, it doesn't produce an output upon execution. The mv command can also be used to rename a file.
###### I ran it followed by the file name and destination directory.

###### I ran it to rename a file by running th ecommand followed by the old_file_name and the new_file_name.

##### Command: mkdir
###### This command is used to create one or multiple directories at once and set permissions for each of them. The user executing this command must have priviledge to make a new folder in the parent directory, or they may recieve a permission denied error.
###### I ran the command mkdir followed by the name of the new directory i created.

###### To create a new directory inside the one that is already created. I ran the mkdir with the old_directory/new_directory.

###### To create a directory between two existing folders. I ran the mkdir command followed by the option -p in the format mkdir -p Dir_1/Dir_2/Dir_3.

###### To create a directory with full read,write, and execute permissions for all users. I ran the mkdir command followed by the option -m in the format mkdir -m777 Directory_name.

##### Command: rmdir
###### This command is used to permanently delete an empty directory. However, the user running this command should have sudo priviledges in the parent directory.
###### To delete an empty directory, i ran the rmdir command rmdir followed by the name of the empty directory.

###### To Delete an empty directory and sub_directory. I ran the rmdir command followed by the option -p in the format rmdir -p directory/sub_directory.

##### Command: rm
###### This command is used to delete files within a directory. However the user running this command has to have write permissions.
###### To remove a file i ran the rm command followed by the name of the file.

###### To remove multiple files. I ran the rm command followed by the file names.
