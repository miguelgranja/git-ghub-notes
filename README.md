## A github repository dedicated to my git/github notes

### Authenticate yourself:
- git config --global user.email <"you@example.com">
- git config --global user.name <"Your Name">

### Create a local repo:
- git init <reponame>

### Add stuff to the commit you're gonna make:
- git add < . || <somefile.extention>>

### Commit changes:
- git commit -m <"Comment">

### Create main branch:
- git branch -M <main>

### Add repository to github:
- git remote add origin https://github.com/<github.username>/<name you want on the github repo>.git

### Push changes to github branch:
- git push -u origin <main>