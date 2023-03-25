Project-0-22BIT0395-
An overview of git commands.

Git supports many command-line tools and graphical user interfaces. The Git command line is the only place where you can run all the Git commands.

1. Git config command.
This command configures the user. The Git config command is the first and necessary command used on the Git command line.

Syntax:
$ git config --global user.name "Gaurav-Dadhich" $ git config --global user.email "kryptogaurav@gmail.com"

2. Git Init command.
This command is used to create a local repository.

syntax:
$ git init [Repositry name]

3. Git clone command.
This command is used to make a copy of a repository from an existing URL. This command allows creating a local copy of that repository on your local directory from the repository URL.

syntax:
$ git clone https://github.com/Gaurav-Dadhich/Project-0-22BIT0395-

4. Git add command.
This command is used to add one or more files to staging (Index) area.

syntax:
$ git add Project 101

5. Git commit command.
Commit command is used in two scenarios.

Git commit-m
This command changes the head. It records or snapshots the file permanently in the version history with a message.

syntax:
$ git commit -m " Commit Message"

Git commit-a
This command commits any files added in the repository with git add and also commits any files you've changed since then.

syntax:
$ git commit -a

6. Git status command.
The status command is used to display the state of the working directory and the staging area. It allows you to see which changes have been staged, which haven't, and which files aren?t being tracked by Git.

syntax:
$ git status

7. Git push command.
It is used to upload local repository content to a remote repository.

syntax:
$ git push

8. Git pull command.
Pull command is used to receive data from GitHub. It fetches and merges changes on the remote server to your working directory.

syntax:
$ git pull [URL]

9. Git branch command.
This command lists all the branches available in the repository.

syntax:
$ git branch

10. Git merge command.
This command is used to merge the specified branch's history into the current branch.

syntax:
$ git merge

11. Git log command.
This command is used to check the commit history.

syntax:
$ git log

12. Git remote command.
Git Remote command is used to connect your local repository to the remote server. This command allows you to create, view, and delete connections to other repositories.

syntax:
$ git remote / $ fit remote add

13. Git fetch command.
It downloads objects to the local machine without overwriting existing local code in the current branch.

syntax:
$ git fatch

14. Git checkout command.
This command creates branches and helps you to navigate between them.

syntax:
$ git checkout [branch name]

15. Git diff command.
This command lists down conflicts. In order to view conflicts against the base file.

syntax:
$ git diff

16. Git reset command.
This command will reset the index and the working directory to the last git commit’s state.

syntax:
$ git reset

17. Git rm command.
It can be used to remove files from the index and the working directory.

syntax:
$ git rm

18. Git stash command.
This command stashes changes for later use.

syntax:
$ git stash

19. Git tag command.
This command creats a tsg for specific commit in the repository.

syntax:
$ git tag

20. Git mv command.
It renames a file in the repository.

syntax:
$ git mv
