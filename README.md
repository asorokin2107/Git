# GIT AND BASH COMMAND

В разделе шпаргалка команд, которые я использовал при создании своего портфолио на GitHub.

## Навигация

- [Git command](#Git)
- [Bash command](#Bash)

## Git

##### Creating, cloning, pushing and pulling repositories
```git
git init                                                    
git clone https://github.com/asorokin2107/asorokin2107.git  
cd                                                
git push 
git commit -m "commited change description"                 
git push 

```
## Bash

##### Working with files and directories
```bash
~                                     # Home directory 
pwd                                   # Show current directory path
mkdir test1                           # Create a directory named test1
cd test1                              # Go to directory test1 (also possible to write the path to needed directory)
touch file{1,2,3}.txt.                # Create file 1,2 and 3 inside directory test1
ls                                    # Check directory test1 content (ls -la if there are any hidden files) 
cd                                    # Go home directory 
mkdir test2                           # Create directory test2 inside home directory
rmdir test2                           # Delete directory test2 
cd mv ~/test1                         # Go back to directory test1
rm file2.txt                          # Delete file 2 
mkdir test3                           # Create directory test3
touch file{4,5}.txt                   # Add two files to directory test3
cd ..                                 # Go back to parent directory
rmdir -rf test3                       # Delete directory test3  
ls                                    # Make sure directory test3 was deleted
mkdir test4                           # Create directory test4
mv ~/test1/file{1,3}.txt ~/test4      # Move file1.txt and file3.txt from directory test1 to directory test4
echo line11 >> file1.txt              # Add 3 lines to file1.txt
echo line12 >> file1.txt            
echo line13 >> file1.txt
cat file1.txt                         # Check content of file1.txt
echo line31 >> file3.txt              # Add 3 lines to file3.txt
echo line32 >> file3.txt
echo line33 >> file3.txt
cat file1.txt file3.txt               # Check contents of file1.txt and file3.txt at once
nano file1.txt + manual replacement   # Using one of the editors, replace all lines in file1.txt and file3.txt
nano file3.txt + manual replacement 
```
