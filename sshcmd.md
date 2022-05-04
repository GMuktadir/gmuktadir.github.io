>#### Notes by Golam Muktadir ❤️

>## How to add repository to github using ssh
### Check ssh key exist or not  
ssh-add -l
### ssh key add this repository
ssh-add
### When ask passphrase
passphrase: gm
### Check connection to github
ssh -T git@github.com

### if mistakes in add remote url

git remote remove origin

>## Add new local repository
```
git init
git commit -m "first commit"
git branch -M master
```
>## local repository to connect remote repository(github)
```
git remote add origin git@github.com:GMuktadir/jekyllsite.git
git push -u origin master
```

>## when a normal repository to publish as github pages always change branch or create gh-pages branch
```
git remote add origin git@github.com:GMuktadir/jekyllsite.git
```

### Create Branch
```
git checkout -M gh-pages
```
### Change Branch
```
git branch -M master
```


