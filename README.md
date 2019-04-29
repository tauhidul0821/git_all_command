<dl>
	<dt>Add and commit process in one line command </dt>
	<dd><code>git commit -am ‘adding more’</code></dd>
	<dt>Show all git tracking file </dt>
	<dd><code>git ls-file</code></dd>
	<dt>Create folder </dt>
	<dd><code>mkdir -p level1/level2/level3/level4</code></dd>
	<dt>Where i am </dt>
	<dd><code>pwd</code></dd>
	<dt>Create file </dt>
	<dd><code>mate level-file.txt</code></dd>
	<dt>Back to the directory</dt>
	<dd><code>cd ../../../..</code></dd>
	<dt>Unstage modified file </dt>
	<dd><code>git reset HEAD file_name.txt</code></dd>
	<dt>Discard change in working directory</dt>
	<dd><code>git checkout -- file_name.txt</code></dd>
	<dt>Rename file name </dt>
	<dd><code>git mv file_3.txt file.txt</code></dd>
	<dt>File name change or Rename file without git </dt>
	<dd><code>mv file_name.txt file.txt</code></dd>
	<dt>Now you see one file deleted and untracked file </dt>
	<dd><code>git status</code></dd>
	<dt>Removing file from git ls-file </dt>
	<dd><code>git rm file_name.txt</code></dd>
	<dt>Removing folder from without git </dt>
	<dd><code>rm -rf folder_name</code></dd>
	<dt>Show git history</dt>
	<dd><code>git log</code></dd>
	<dt>Short commit id </dt>
	<dd><code>git log --abbrev-commit</code></dd>
	<dt>For one line graph and decorate show </dt>
	<dd><code>git log --oneline --graph --decorate</code></dd>
	<dt>Spacify commit list show </dt>
	<dd><code>git log commit_no ...commit_no</code></dd>
	<dt>Want to show 3 days ago commit or history commit </dt>
	<dd><code>git log --since=”3 days ago”</code></dd>
	<dt>Spacify git log a file, git return spacify file log </dt>
	<dd><code>git log -- file_name</code></dd>
	<dt>Git return what change in this commit </dt>
	<dd><code>git show commit_id</code></dd>
	<dt>Git all commit history </dt>
	<dd><code>git log --all --graph --decorate --oneline</code></dd>
	<dt>For create your own git command </dt>
	<dd><code>git config --global alias.hist ‘log --all --graph --decorate --oneline’</code></dd>
	<dd><code>git hist</code></dd>
	<dt>Git ignore pattern example </dt>
	<dd>specific file : myfile.txt</dd>
	<dd>file pattern : *.exe
	<dd>folder: my-folder/</dd>
</dl>
