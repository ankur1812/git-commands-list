## Git commands List ##


### 1.Create a new repository on the command line / Push to remote repo

```
echo "# git-commands-list" >> README.md 
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:<USER>/<REPO>.git
git push -u origin main
```
