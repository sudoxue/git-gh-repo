#install brew
check if brew is installed
#install gh and git. to understand computer world, first thing is to personalize things. 
Think about git and gh as two person. They perform different roles to help you. 

#1. to create your project folder. If you already have a project folder, cd into it.

mkdir git-gh-project;cd git-gh-project

#2. run git init, basically, the command is telling your computer, I want to create a remote repo for this project

git init
gh repo create git-gh-repo --public --source=. --remote=upstreams

Now you can open your github webbrowser to see if repo is created. 

