# git_all_command
<h1>Add and commit process in one line command </h1>
Git commit -am ‘adding more’
Show all git tracking file 
Git ls-file
Create folder 
Mkdir -p level1/level2/level3/level4
Where i am 
pwd
Create file 
Mate level-file.txt
Back to the directory
Cd ../../../.. 
Unstage modified file 
Git reset HEAD file_name.txt
Discard change in working directory
Git checkout -- file_name.txt
Rename file name 
Git mv file_3.txt file.txt 
File name change or Rename file without git 
Mv file_name.txt file.txt
Now you see one file deleted and untracked file 
Git status
Removing file from git ls-file 
Git rm file_name.txt
Removing folder from without git 
 Rm -rf folder_name
Show git history
Git log
Short commit id 
Git log --abbrev-commit
For one line graph and decorate show 
Git log --oneline --graph --decorate
Spacify commit list show 
Git log commit_no ...commit_no
Want to show 3 days ago commit or history commit 
Git log --since=”3 days ago”
Spacify git log a file, git return spacify file log 
Git log -- file_name
Git return what change in this commit 
Git show commit_id
Git all commit history 
Git log --all --graph --decorate --oneline

For create your own git command 
Git config --global alias.hist ‘log --all --graph --decorate --oneline’
Git hist
Git ignore pattern example 
Specific file : myfile.txt
File pattern : *.exe
Folder: my-folder/

