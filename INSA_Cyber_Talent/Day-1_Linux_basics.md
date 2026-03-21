## File System in Linux

   * **/** - first of file structure!  
   * **/bin** - every command you run  
   * **/boot** - every file and folder that related to os(kernel).  
   * **/dev** - hardware components,   
   * **/etc** - configuration files,   
   * **/home** - which contains all users  
   * **/lib* - library essential for the binaries  
   * **/media** - temporary mount directory for removable device.  
   * **/mnt** - temporary mount directory manually placed  
   * **/opt** - optional application software packages  
   * **/sbin** - system binaries  
   * **/tmp** - temporary files,, files deleted after reboot  
   * **/usr** - user utilities   

### Test Editors for kaliLinux

   > **CLI** - vim,nano,emacs  
   > **GUI** - vscode,sublime  

   * vim -> command mode **":%!"**,, eg. **:%ls** - normal list  
          * save ":w"  
          * quit ":q"  
          * quit force "wq:"  
          * undo ":u"
 
###### Living of the land - attack method without using any aditional tool only with inbult cmd and tools like "vim"

## summery
 
 * **User** - an account that allows someone(program) ro access the system with specific permissions  
    ##### types of users:   

        *  **root User** - most powerfull, full controll, UID = 0  
        *  **Regular User** - for normal work, limit perm, cannot modify critical system files  
                 => to create: "sudo useradd username && sudo passwd username"  

        * ** system Users** -  used by services like: database, servers,, not for human login, UID = <1000
   
    => to access a "root"

        "su" for permanent
   	"sudo command" for temporary does
   
     * Package Installation In Linux    
            apt(Debian/Ubuntu based systems) stands for "Advanced package tool"  
            pacman(Arch based sys)  
           "dpkg -1 file.deb" for manually installed debian file
   	   
   * **Script** - a file containing commands executed automatically  
        - to create " nano script.sh" has "#!/bin/bash" header  
        - make it excutable "chmod +x script.sh"  
        - run " ./script.sh"  
  * **shell** - is a command-line interface that allows users to interact with the OS.  
  	=> types of shell:  
                * bash - Most common  
                * sh - Basic shell  
                * zsh - Advanced features  
                * fish - user-friendly  
  	=> to see which shell "echo $SHELL"
  
  * ** Script** Installation - preparing a script so it can be executed like a program
 
  * ** piping( | )** - sends output of one comomand to another  
  	**eg.**ls | grep file  
  * ** redirection(>,>>,<)**  
  	**echo "Hello" > file.txt => output to file** 
  	**echo "World" >> file.txt => append**  
  	**cat < file.txt => input**
