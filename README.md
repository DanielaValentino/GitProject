# **The Command line.** Git Basic Commands

- mkdir 
>This command creates a new directory. *Ex.* mkdir example.

- git rm -namefile-
>Is used to remove a file from the staging area and working directory. *Ex.* git rm example

- cd -namedirectory-
>With this command you can enter to a directory. *Ex.* cd example.

- cd ..
>Command to move the user up one directory. *Ex.* cd .. 

- ls 
>You can list current files and directories with this command.

- ls -a
>Command to show hidden files and folders.

- nano
>To create a new file. *Ex.* nano README.md

- git status
>To see what files are in which state. *Ex.* git status

- git cat 
>This command display the contents of a text file you created previously. *Ex.* git cat README.md

- pwd	
>It is used to show the current directory.

- clear	
>To clear the shell window.  

 

# **Git/github**

- git config --global user.name " "
>For personal configuration of username.  *Ex.* git config --global user.name "Example Name"

- git config --global user.email " "
>To configurate the personal email.  *Ex.*  git config --global user.email "example@gmail.com"

- git init
>Is used to initialize a repository in current directory. You can name the repository with git init -name-  *Ex.* git init examplename

- git clone
>Command to clone an existent repository. *Ex.* git clone - url -

- git diff -file-
>To see the changes between working directory and staging area.  *Ex.* git diff example

- git commit
>This command is used to commit chages added to the staging area.

- git checkout -- -file-
>Command to discard changes in the working directory.

- git log
>It lists the commits made in the repository in reverse chronological order.

- git rm -file-
>Is used to remove a file from the working directory and add deletion to staging area. *Ex.* git rm example

- git mv
>You can rename or move a file with this command.



### ***Basic workflow commands***

- git add -filename-
>Command to add a file to the staging area.  *Ex.* git add example.md

- git reset -namefile-
>You can get a file back from staging area to working directory.  *Ex.* git reset example

- git restore
>To unstage files you don´t want to commit.

- git commit -am ""
>To automatically stage files that have been modified and deleted.

- git fetch -remote-
>To fetch changes from the remote repository.

- git pull
>Command to automatically fetch and then merge that remote branch into your current branch.

- git push origin master
>To push your master branch to your origin server and push any commits done back up to the server.



### ***Branches***

- git branch -name-
>You use this command to create a new branch.  *Ex.* git branch test 

- git branch -d -branchname-
>With this command you can remove the selected branch. *Ex.* git branch-d test

- git branch -a
>It lists all branches in repository.

- git checkout -branchname-
>This changes working directory to the specified branch. *Ex.* git checkout test

- git merge -from name-
>Command to join a specified branch into the current branch.


### ***Gitflow***
- git flow init
>To initialize it inside an existing repository.

- git flow feature start MYFEATURE
>Command to creat a new feature branch.

- git flow feature finish MYFEATURE
>It removes the feature branch.

- git flow feature publish MYFEATURE
>It publishes a feature to the remote server.

- git flow feature pull origin MYFEATURE
>You use it to get a feature published by another user.
