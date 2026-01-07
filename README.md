# Devops Learning journey
 Day 2 - Git & GitHub\n
Linux Basics Completed.
created a local dir using ubuntu
created a readme.md file into it using command touch README.md
added text into the readme.md: using command nano readme.md
created another branch using command git -b checkout branch_name
again added anonther readme.md file and added text into it.
 then made add the readme.md file to branch using command git add .
and then commited using git commit -m "initial commit"

then merged the created branch with primary branch using command git merge branch_name by change the pwd to primary branch

deleted the secondary branch using command git branch -d branch_name

after this I have created a remote repo in github - with name practic-notes
then I copied the URL of the repo: https://github.com/Indra1806/practice-notes

Now the task is to add the mix the local repo and remote repo

for that i used the command: git remote add origin https://github.com/Indra1806/practice-notes

as well as used git branch -M main command to push

after this I used the command git push -u origin main


along after completion of this i created a .gitignore using the command nano .gitignore

and added the major required to ignore while commit: those are as 

*.log
*.tmp
.env
__pycache__/

and as usally added & commited the file

using the command git add .gitignore, git commit -m "Add .gitignore", git push


## Git is a distributed version control system. GitHub acts as the remote source of truth.
## CI/CD pipelines are triggered by Git events like push or pull requests.

