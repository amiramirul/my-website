How to access website
Link : https://amiramirul.github.io/my-website

How to update web git
1. git add .
2. git commit -m "Yada Yada"
3. got push origin main

what if the errror is about 
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

--- if use Window
ssh -t git@github.com
eval $(ssh-agent)
ssh-add ~/.ssh/github-Amir

Check status of the git folder with github.com
git status
git remote -v
ssh -t git@github.com