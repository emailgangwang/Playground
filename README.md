# Playground
Steps on setup a new reporitory (using this "Playground" as an example):

Create a new reporitory, it will show instructions on how to add the new files on commandline.
For example: 

…or create a new repository on the command line
echo "# Playground" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:emailgangwang/Playground.git
git push -u origin main

…or push an existing repository from the command line
git remote add origin git@github.com:emailgangwang/Playground.git
git branch -M main
git push -u origin main


-------------------------
Two setup an SSH connection. Following the instructions on this
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh 