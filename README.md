## Basic-Linux-Commands
### 1. File & Folder/Directory Management
#### *Listing Files & Folders:*
```
● ls                                : list files and folders 
● ls -la                            : list all files and folders (including hidden ones)
```
#### *Navigating Directories:*
```
● cd directory_name                 : change directory to (directory_name)
● cd ..                             : go back one directory
● cd ~                              : go to home directory
● cd -                              : go to previous directory
● cd /                              : go to root directory
● pwd                               : shows your current location (path/directory)
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
● wc file_name                      : display count of lines, words & characters in the file
```
#### *Editing Files*
```
● nano file_name                    : open a simple, easy-to-use text editor in terminal (beginner-friendly)
● vim file_name                     : open an advanced text editor in terminal
```
### 3. File Permissions & Ownerships 
```
● sudo                              : grant administrative or root permissions
● chmod 777 file_name.txt           : grant full access(read, write, execute) of the file for owner, group & others (chmod 644 is recommended)
● chmod +x file_name.txt            : makes a file executable
● chmod u+x file_name.txt           : grant execute permission for owner
● chmod g+x file_name.txt           : grant execute permission for group
● chmod o+x file_name.txt           : grant execute permission for others
● sudo chown username file_name.txt : change owner of the file
```
### 4. File Searching
```
● grep "word" file_name             : search for a word in a file and displays the line
● grep -i "word" file_name          : ignore whether the word is capitalized or lowercase
● locate file_name.txt              : search for the file (fast)
● find ~ -name file_name.txt        : search for the file in the home directory and its subfolders
● find / -name file_name.txt        : search for the file in the root directory and its subfolders
● find . -name file_name.txt        : search for the file in the current directory and its subfolders
```
### 5. File Information
```
● file file_name                    : show file type
● stat file_name                    : shows detailed file information
● strings file_name                 : displays all human-readable text hidden inside the file
```

### 6. File Downloading
```
● wget url                          : downloads files directly from the internet to the system
● curl url                          : prints the downloaded content directly to the terminal
```
### 7. Process Management
```
● ps                                : displays processes running in the current terminal
● ps aux                            : displays all processes running in the system
● top                               : opens task manager (displays running processes, CPU/RAM usage)
● htop                              : replacement for top (user-friendly)
● kill pid                          : kill a specific process (provide the pid number)
● killall program                   : close all running windows/processes related to the program (provide the specific program)
```
### 8. Network Management
```
● ping ip                           : check network connectivity for the provided ip address
● traceroute ip                     : shows the full path packets cross to reach the destination
● ip a                              : displays all network interfaces with their assigned IP addresses, MAC addresses, and connection status
● dig/nslookup domain_name          : resolve domain names to ip(s)
● netstat/ss -tuln                  : show active network connections and ports
```
