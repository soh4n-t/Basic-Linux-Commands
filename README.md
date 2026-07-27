## Basic-Linux-Commands
### 1. File & Folder/Directory Management
#### *Listing Files & Folders:*
```
● ls                : list files and folders 
● ls -la            : list all files and folders (including hidden ones)
```
#### *Navigating Directories:*
```
● cd directory_name : change directory to (directory_name)
● cd ..             : go back one directory
● cd ~              : go to home directory
● cd -              : go to previous directory
● cd /              : go to root directory
● pwd               : shows your current location (path/directory)
```
#### *Creating Files & Directories*
```
● touch file_name                   : creates a new file
● echo "Hello " > file_name.txt     : creates a file and writes the text Hello to it
● echo "World" >> file_name.txt     : appends World to the file content
● mkdir folder_name                 : creates a new directory(folder)
```
#### *Copying & Moving*
```
● cp file_name destination          : copies a file to the desired location (also for renaming a file)
● cp -r folder_name destination     : copies a folder and all its contents 
● mv *file/folder*_name destination : moves a file/folder to the desired location
```
#### *Removing Files & Folders*
```
● rm file_name                      : remove/delete a file
● rm -r folder_name                 : delete a folder and its contents 
```
### 2. File Viewing & Editing
#### *Viewing & Reading Files:* 
```
● cat filename                      : display the contents of a file
● less filename                     : view a large file one page at a time by scrolling through (press q to quit)
● head filename                     : display only the first 10 lines of a file
● tail filename                     : display only the last 10 lines of a file
```
#### *Editing Files*
```
● nano file_name                    : open a simple, easy-to-use text editor in terminal (beginner-friendly)
● vim file_name                     : open an advanced text editor in terminal
```
### 3. Permissions & Ownerships
#### **
```
● sudo                              : grant administrative or root permissions
● chmod 777 file_name.txt           : grant full access(read, write, execute) for owner, group & others
● chmod +x file_name.txt            : 
●
●
```
