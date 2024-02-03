# Git & Terminal Cheatsheet

## Git

1. ```git init``` :
Create empty Git repo in specified directory. Run with no arguments to initialise the current directory as a git repository.

2. ```git add ...```:
Stage all changes in directory for the next commit. Replace directory with a file to change a specific file.

3. ```git commit -m "<message>"```:
Commit the staged snapshot, but instead of launching a text editor, use message as the commit message.

4. ```git status```:
List which files are staged, unstaged, and untracked.

5. ```git push origin main```:
Push the branch to origin, along with necessary commits and objects. Creates named branch in the remote repo if it doesn’t exist.

6. ```git pull origin main```:
Fetch the specified remote’s copy of current branch and immediately merge it into the local copy.

## Terminal Command Line

1. ```pwd```:
Display path of current working directory

2. ```cd <directory>```:
Change directory to "directory"

3. ```cd ..```:
Navigate to parent directory

4. ```ls``` :
List directory contents

5. ```ls -al``` :
List detailed directory contents, including
hidden files

6. ```mkdir <directory>```:
Create new directory named directory

7. ```clear```:
Clear the command line

8. ```rm <file>```:
Delete file

9. ```rm -r <directory>```:
Delete directory

10. ```my <file-old> <file-new>```:
Rename file-old to file-new

11. ```mv <file> <directory>```:
Move file to directory (possibly overwriting an existing file)

12. ```touch <file>```:
Update file access & modification time (and create file if it doesn't exist)




