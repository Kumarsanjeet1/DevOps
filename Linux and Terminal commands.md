#  Terminal_Emulator
 - A Terminal Emulator is basically Program that will let us used the Terminal in graphical way. Using Terminal We can able to control our Operating system.
 Example- Command "mkdir demo"- From this command we can create a new demo folder.  
#  Shell
 - Shell is a Command line interface that will interpret our Commands and convert those and tell the Operating System, What to do.

#  Environment Variable
  - An environment variable is a "Dynamic-Named Value That Can Affect The Way Running Process Will behave On a Computer". Also we have set the Variable name before using it.

#  Linux & Terminal Command
 -  ![image](https://user-images.githubusercontent.com/89514486/156747336-bfda4884-e39d-4e4f-bed9-6069b6919ae6.png)
           
      Basically "where" Command is looking for that where the 'python3 file' is located"
 - ![image](https://user-images.githubusercontent.com/89514486/156747456-0759f75f-9153-42e5-a3de-1f6e17dec6c3.png)
           
      ls Command Stands for List (basically "ls" command is displaying all the folder and file in the paticular folder where will you run the command)
      
 - ![image](https://user-images.githubusercontent.com/89514486/156866629-9b80e303-9dd2-4cbe-bcec-2ad3a00b80af.png)
 
    It is for basically creating a new folder in home directory.
    
 - ![image](https://user-images.githubusercontent.com/89514486/156866670-2846c437-d8bd-4453-93fc-d2a2ed6d08d9.png)
 
    It is for changing the home directory to given folderName/path
 - ![image](https://user-images.githubusercontent.com/89514486/156866700-9bdf11b0-2d1a-4456-b018-ff08da1944e3.png)
 
    It is used to go one folder back from your current directory
 - ![image](https://user-images.githubusercontent.com/89514486/156867236-bdbdd37a-dd3e-42f8-8cf3-2cc338a8dc59.png)
 
    It is used to display what do you want to display.
    Example- ~echo $path
              This command is used to display all directories specified by path in the environment variable.
              
  - pwd
   
    Stands for "Print working directory", Basically pwd command is print/display the path directory,where are you working from.
 
 - ls (list directory contents)
    
        lists tags-
        • ls -a (It is display the all files including hidden files)
        • ls -l (It is display the file with long details)
        • ls -al (It is display the all the files including hidden files with long detatils)
        • ls -R ( It will display the all files also in sub-directory)
        •
        •
        • 
    
 - cd       (Change Directory)
              
            • cd .. ( Change path directory one step back)
             
 
 - cat     (Concatenate files to standard Output)
             
         • cat > name.txt    (creating a new file)
               Hi, My name is sanjeet,    (cntrl + c   to save the file)
         • cat name.txt       (display the information or data in it)
         • cat surname.txt    (creating a new file)
              Hi, My surname is kumar  (cntrl + c    to save the file)
         • cat name.txt surname.txt > fullname.txt    (Create a new file that is fullname.txt, 
              then Concatenation of name.txt or surname.txt will be assign in fullname.txt)
         • cat fullname.txt       (display the data of fullname.txt)
         • echo "halo" (It will display halo)
         • echo "halo" > greet.txt  (It will create a new file and "halo" will be assign in the file)
         • cat greet.txt    (It will display the data of greet.txt file)
         • cat greet.txt | tr a-z A-Z >upper.txt (
         
- df      (report file system disk space usage)

      •df -h (report file system disk space usage in human readable format)
- du      (estimate file space usage)
     
      •du -h ( display size in human readable format )
     
      
- mv      (move (rename) files)
- cp      (copy files and directores of existing files or directories)

      • cp -R   (cp will continue copy even if errors are detected)
      • cp -f   (cp      
- rm      (remove files or directories)
           
      Tags-
      •rm -d  (remove empty directories)
      •rm -R  (rm will continue remove even if errors are detected)
      •rm -f  (To remove files or directories forcefully)
      •
- rename  (renames files)
- sudo    (Super User do- execute a command as another user, for executing commands you have to enter User Account PASSWORD )
- vi (vim) (A programer text editor)
- head (output the first part of files)
  
        Tags-
           •head -n "files name"  (print n lines from start line of files)
           •
- tail (output the last part of files)
         
        Tags-
           •tail -n "files name"  (print n lines from last line of files)
           •
- diff (compare file line by line)
- locate (for Finding Files)
- find ( It is basically used to listing me the files or directories)

       Tags-
      • find .  (listing me files or directories in the current directory)

      • find .. (listing me files or directories in the previous directory)

      • find . -type d  (listing me only directories in the current directory)

      • find .. -type d  (listing me only directories in the previous directory)

      • find . -type f  (listing me only files in the current directory)

      • find . -type f -name "name.txt" (This command is finding the file through name "name.txt" in the current directory)

      • find . -type f -name "two*" (This command is finding the (* means can anything come over here) file using * name)

      • find . -type f -name "*.txt" (This command will listed only those file, whose file extension name will ".txt")

      • find . -type f -mmin -20 (This command is basically used to listing the all the files that were modified less than 20 minutes ago)

      • find . -type f -mmin +14 (This command is basically used to listing the all files that were modified more than 14 minutes ago)

      • find . -type f -mmin +2 -mmin -10 (This command is used to listing all files that were modified more than 2 minutes ago and under 10 minutes ago) 

      • find . -type f -mtime -10 (This command is used to listing all the files that were modified less than 10 days ago)
      •
      •
      •
      •
      •
      •
      •
      •
