# git-related

### delete .git from folder
```
 rmdir -Force -Recurse .git
```
```
 rm -rf .git
```
### Check which branch

```
git checkout b_name
```

### new branch
```
git checkout -b b_name
```

### clone n pull
```
git clone [link]

git pull 

git pull origin [branch]

```

### update individual branch with main
```
 git checkout main
 git pull
 git checkout validator
 git merge main
 git push
```

### Make a new repo n push new code.
```
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/bharatpaliwal-169/publish-a-package-on-npm.git
git push -u origin main
```
