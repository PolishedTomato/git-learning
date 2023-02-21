 git-learning

Two ways to initialize git repo

1, create a repo in git.com and use git clone <http url> in the command line
it will create a new folder in currently directory ( recommanded)

2, create a remote repo in local then connect to github exising repo
	1, git init()
	2, git add <remote> <http url>
	3, git checkout -b <remote> <new branch name>

The second one also set the repo on your current directory, so make sure you do it in a new directory

For http url clone, push, pull, etc, github now request new way of authentification. They will promote the user with 
Username:
password:

The Username is the same, but the password need to be personal access code(PAC)
which could be set up in setting->developer setting-> access code

Way to delete remote:
git remote remove <remote name>

Check remotes:
git remote
