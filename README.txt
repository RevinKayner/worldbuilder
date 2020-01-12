To set up Git repo on the command line, right click in the desired directory and select "Git Bash Here." Then in the window that pops up, type the following commands:

git init
git config --global http.postBuffer 1048576000
git add .
git commit -m "first commit"
git remote add origin https://github.com/RevinKayner/worldbuilder.git
git push -u origin master

