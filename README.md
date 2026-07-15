# Guvi-task-vcs-
vcs task
cd ~/Desktop
mkdir Git_Task
cd Git_Task

touch script1.sh
touch script2.sh
touch script3.sh

nano script1.sh
nano script2.sh
nano script3.sh

git init
git status
git add .
git commit -m "Initial commit"

git remote add origin <repository-url>
git branch -M main
git push -u origin main

git checkout -b feature
git merge feature

git checkout -b rebase-demo
git rebase main

git stash
git stash list
git stash apply

git add .
git commit -m "Applied stashed changes"
git push
