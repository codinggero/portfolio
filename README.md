#

create a new repository on the command line

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/codinggero/portfolio.git
git push -u origin main

#

…or push an existing repository from the command line
git add .
git commit -m "first commit"
git branch -M main
git push -u -f origin main
