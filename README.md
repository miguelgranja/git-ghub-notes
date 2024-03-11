## A github repository dedicated to my git/github notes

### Authenticate yourself:
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"

### Create a local repo:
- git init

### Delete a local repo:
- rmdir .git -force

### Add stuff to the commit you're gonna make:
- git add . || somefile.extention

### Commit changes:
- git commit -m "Comment"

### Branch Commands:
- git branch -M main [create a branch]
- git branch -r [find existing remote branches]
- git branch -l [find existing local branches]

### Add repository to github:
- git remote add origin https://github.com/<github.username>/<github.repo>.git

### Push changes to github branch:
- git push -u origin main
