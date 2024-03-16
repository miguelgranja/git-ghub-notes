## A github repository dedicated to my git/github notes

### Authenticate yourself:
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"

### Create a local repo:
- git init

### Create a .gitignore file:
- touch .gitignore

### Delete a local repo:
- rmdir .git -force

### Add stuff to the commit you're gonna make:
- git add . || somefile.extention

### Commit changes:
- git commit -m "Comment"

### Branch Commands:
- git status [Current branch's name]
- git branch -M main [create a branch]
- git branch -r [find existing remote branches]
- git branch -l [find existing local branches]
- git checkout [switches to a user specified branch]
- git merge [merges a user specified branch into the current one]

### Add repository to github:
- git remote add origin https://github.com/<github.username>/<github.repo>.git

### Push changes to github branch:
- git push -u origin main

### Pulls changes
- git fetch [pull the latest remote commits]
- git pull [pulls the latest remote commits]

### AsciiDoc Cheat sheet for github
- https://gist.github.com/powerman/d56b2675dfed38deb298