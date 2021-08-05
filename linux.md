# Linux History

  <p align ="center"/><img src ="images/linux history.PNG" width ="230%" />

#  Linux Command 

| Command   |      Syntax     |  Description |
|----------|-------------|------|
| ls  |  ls "directory name" | List the directory folder.|
|     |  ls -l               | It will list all file in the discriptive way.|
|     |   ls -l -h           | Human readable. |
|     |  ls -l -h -t         |In Ascending order it will display the files.  |
|     |ls -l -h -t -r        | In Descending order it will display the  files.    |
| cd  | cd "directory name"  |  Change directory form one to other directory.    |
|     | cd -                 | Back to previous directory.   |
|     | cd ..                |  It will take you one step back.  |
|     |  cd ~                | It will take you home directory. |
| pwd |  pwd                 | Print working directory.      |
| ipconfig(Window)/ifconfig(MAC) |  ifconfig/ipconfig                | Give system ip address and other network information.  |
| cp  | cp "source file" "destination file"   | It is used copy form one location to other location.  |
| mv  |  mv "source file" "destination file"    | Moves one file to another file.     |
|     | mv "source directory" "destination directory"   | Moves one directory to another directory.      |
|touch | touch "filename.ext"    | To create a new file.|
|mkdir| mkdir "directory name"| Create a new directory.    |
| | mkdir "directory1"/"directory2" -p| Create a recursive directory.|
|  cat |  cat filename       | It is used to read data form file|
|      |  cat > filename     | It is used to write data in file|
|      |  cat >> filename    | It is used write data in file but it will not delete previous data.|
| rm | rm "filename"         | It remove the file.      |
|    | rm -r                  | It  removes file.     |
|    | rm -rf                | It  removes directory file.      |
|    | rm -rf*               | It will remove both directory  and file.     |
| history | history          | Lists all the previous commands run by the user.|
| clear   | clear,cltr+l     | Clear the terminal.|
| exit   |   exit            | Exit the terminal.|
| top  | top                 | Give system information.|
| ps    | ps                 | It will list out all application  running in the system.|
| who|  who                  |  Shows how many users are logged-in to the system.|
| whoami|  whoami            |  Shows the current logged-in user.|


# Linux File System and Directory Structure

* In linux file system start form root(/) file system and everything comes under this root file system.
* Inside root directory there are couple of more directory.
* In linux everything is considered as a file. 

<p align ="center"/><img src ="images/root directory.jpg" width ="100%" />




|  Directory |   Description  |   
|----------|-------------|
| /  |  Root file system.|
| /boot  |  System kernel is stored                 |
| /bin   | Binary file  and  commands are stored.                 |
| /sbin   |  It is used by system admin and all commands  used by system are stored here and not used for normal user.                 |
|/home    | All user data are stored.                  |
|/var   | System level variables are store log files and other files which is not critical system.                 |
|/usr  | All the software install in the user folder.                  |
|/root    | Only system admin is created here. The root user is denoted using # .               |
|/tmp | The system is used when the system wants to store  the temporary data.                  |
|/etc    | System configuration stored.                  |
|/lib   |  System library stored.                 |
|/mnt    | Mount temporary for CD ROM.                   |
|/dev       | dev is basically kind memory  all the external hardware keyboard,mouse,usb get attach to this. it is kind of memory but in linux everything is consider file.           |  
|/proc         | Give system level information.             | 

