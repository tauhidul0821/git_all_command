
<dl>
	<dt>Add and commit process in one line command </dt>
	<dd>git commit -am ‘adding more’</dd>
	
	<dt>Show all git tracking file </dt>
	<dd>git ls-file</dd>
	
	<dt>Create folder </dt>
	<dd>mkdir -p level1/level2/level3/level4</dd>
	
	<dt>Where i am </dt>
	<dd>pwd</dd>
	
	<dt>Create file </dt>
	<dd>mate level-file.txt</dd>
	
	<dt>Back to the directory</dt>
	<dd>cd ../../../.. </dd>
	
	<dt>Unstage modified file </dt>
	<dd>git reset HEAD file_name.txt</dd>
	
	<dt>Discard change in working directory</dt>
	<dd>git checkout -- file_name.txt</dd>
	
	<dt>Rename file name </dt>
	<dd>git mv file_3.txt file.txt </dd>
	
	<dt>File name change or Rename file without git </dt>
	<dd>mv file_name.txt file.txt</dd>
	
	<dt>Now you see one file deleted and untracked file </dt>
	<dd>git status</dd>
	
	<dt>Removing file from git ls-file </dt>
	<dd>git rm file_name.txt</dd>
	
	<dt>Removing folder from without git </dt>
	<dd>rm -rf folder_name</dd>
	
	<dt>Show git history</dt>
	<dd>git log</dd>
	
	<dt>Short commit id </dt>
	<dd>git log --abbrev-commit</dd>
	
	<dt>For one line graph and decorate show </dt>
	<dd>git log --oneline --graph --decorate</dd>
	
	<dt>Spacify commit list show </dt>
	<dd>git log commit_no ...commit_no</dd>
	
	<dt>Want to show 3 days ago commit or history commit </dt>
	<dd>git log --since=”3 days ago”</dd>
	
	<dt>Spacify git log a file, git return spacify file log </dt>
	<dd>git log -- file_name</dd>
	
	<dt>Git return what change in this commit </dt>
	<dd>git show commit_id</dd>
	
	<dt>Git all commit history </dt>
	<dd>git log --all --graph --decorate --oneline</dd>
	
	<dt>For create your own git command </dt>
	<dd>git config --global alias.hist ‘log --all --graph --decorate --oneline’</dd>
	<dd>git hist</dd>
	
	<dt>Git ignore pattern example </dt>
	<dd>specific file : myfile.txt</dd>
	<dd>file pattern : *.exe
	<dd>folder: my-folder/</dd>
</dl>
