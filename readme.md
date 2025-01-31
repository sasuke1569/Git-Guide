# Git Guide

### 1. Config user
```
git config --global user.name "Your Full Name"
git config --global user.email "your-email-address"
git config --list
```

### 2. Init git
```
mkdir "Git Guide"
cd ".\Git Guide"
git init
dir -hidden
```

### 3. First Commit
```
git status
git add .\file.ext
git status
git commit -m "Commit message: brief description"
git status
```


### 4. Create Branch
```
git branch dir/readme/steps-4-to-6
git branch

```

### 5. Checkout Branch
```

git checkout dir/branch-name
git status

```

### 6. Merge to master
```

git checkout master
git status
git merge dir/branch-name
git status
```

### 7. Create Stash
```
git status
git stash
git status
```

### 8.Apply stash
```

git stash list
git stash apply
git status
```

### 9.Delete stash
```

git stash list
git stash drop 1
git stash list

```

### 10.Pop stash
```

git stash list
git stash pop
git stash list

```

### 11. Revert Commit
```
git log --online
git revert [COMMIT_TD]

``` 

### 12. Cherry Pick
```

git log --online
git cherry-pick [COMMIT ID]

```

### 13. Reset Commit
```

git log --online
git reset --soft HEAD~1


git add --patch
git reset --mixed HEAD~1

```

### 14. Create Patch
```

git diff HEAD > diff.patch
git diff --cached > diff.patch

```

### 15. Apply Patch
```
git aplly > diff.patch

```

### 16. Init GitHub
```
git remote add origin [REMOTE-URL]
git push -u origin master 
git push origin --all

```

