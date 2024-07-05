# GITHUB COMMANDS PIO

## CLONING
git clone <https url>

SINGINING IN
git config --global user.<EMAIL>
git config --global user.<username>

PUSH
git fetch
git add .
git commit -m "first commit"
git push -u origin main

COMMIT IN NEW REPO
git init
<if meron> git add README.md
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/uShire/microsoft2022.git
git push -u origin main


MASTER
git checkout aranza
git fetch
git checkout main
git merge aranza 
git pull
git add .
git commi -m "first commit"
hit push -u origin master
