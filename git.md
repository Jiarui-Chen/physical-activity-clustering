# Git Scripts

### Initial Setup
```
git init
git add .
git commit -m "Initial commit with project structure"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```


### Create, Switch to and Push Branch
```
git checkout -b eda
git push -u origin eda
```


### Branch Sync
```
git fetch origin
git checkout -b eda origin/eda
```


### Commit Tasks
```
git add eda_notebook.ipynb
git commit -m "feat: Perform initial exploratory data analysis"
```


### Push Changes
```
git push origin eda
```


### Pull Changes
```
git checkout -b eda
git pull origin eda
```


### Stash Changes
```
git stash

git stash save "Your stash message"

git stash apply

git stash list

git stash pop

git stash apply stash@{n}

git stash drop stash@{n}
```


### On GitHub or GitLab, create a pull request to merge the branch into main


### Merge the branch into main after PR approval
```
git checkout main
git merge eda
git push origin main
```