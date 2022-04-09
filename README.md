<h1>Basic Git Commands</h1>

# git config
$ git config –global user.name “[name]” <br>
$ git config –global user.email “[email address]”

<p> This command sets the author name and email address respectively to be used with your commits. </p>

# git init
$ git init [repository name] 
<p>This command is used to start a new repository. </p>

# git add
$ git add [file_name] <br>
$ git add *  
<p> This command adds a file to the staging area. </p>

# git commit
$ git commit -m “[commit message]”  

<p> This command records or snapshots the file permanently in the version history. </p>
 
# git status
$ git status  
<p>This command lists all the files that have to be committed.</p>

# git rm
$ git rm [file_name]  
<p>This command deletes the file from your working directory and stages the deletion. </p>

# git branch
$ git branch  
This command lists all the local branches in the current repository.

$ git branch [branch_name]  
This command creates a new branch.

$ git branch -d [branch_name]  
This command deletes the feature branch.

# git checkout
$git checkout [branch name]  
This command is used to switch from one branch to another.

$git checkout -b [branch name]  
This command creates a new branch and also switches to it.

# git merge
$ git merge [branch name]  
<p>This command merges the specified branch’s history into the current branch.</p>

# git push
$ git push [variable name] master  
This command sends the committed changes of master branch to your remote repository.

$ git push [variable name] branch  
This command sends the branch commits to your remote repository.

$ git push –all [variable name]  
This command pushes all branches to your remote repository.

$ git push [variable name] :[branch name]  
This command deletes a branch on your remote repository.

# git pull
$ git pull [Repository Link]  
<p>This command fetches and merges changes on the remote server to your working directory.</p>

# git remote
$ git remote add [variable name] [Remote Server Link]  
<p>This command is used to connect your local repository to the remote server.</p>

# git stash
$ git stash save  
This command temporarily stores all the modified tracked files.

$ git stash pop  
This command restores the most recently stashed files.

$ git stash list  
This command lists all stashed changesets.

$ git stash drop  
This command discards the most recently stashed changeset.






