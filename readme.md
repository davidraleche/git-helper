git repack


### SETUP REMOTE GIT
```
 git init
 git add .
 git status
 git commit -m "First commit"
 git remote add origin git@github.com:davidraleche/david.raleche.com.git
 git remote -v
 git push -u origin master
```
 
 ### Add Key to github
```
cat ~/.ssh/authorized_keys 
cat ~/.ssh/known_hosts 
```

### SYNC GIT
`git remote update`

`git fetch`
Downloads the latest from remote without trying to merge or rebase anything.

`git fetch -- all`

### REMOVE untracked files
`git clean -f -d  `

### RESET BRANCH/FILE
`git reset --hard origin/master` 
 --  force discard local changes

`git reset --hard origin/<davidBranch_name>` 
--  force discard local changes

`git checkout -f <localfile>` 
-- force discard local changes

### COMMIT
`git commit -m ‘My commit David Raleche’`

### Amend a COMMIT
git commit --amend

### remove git add 
`git reset HEAD -file-`

### PUSH 
`git push origin <davidBranch>`

### CONFLICTED FILES
`git diff --name-only --diff-filter=U`
GIT ADD
`git add <file>`
git commit -m “message of your commit”
git push origin  <branch>

### GIT RESET ADD
`git reset <file>`
`git reset`
### (VERY DANGEROUS) REMOVING LAST COMMIT (VERY DANGEROUS)

`git reset --soft HEAD~1`

`git reset --hard HEAD^`

(VERY DANGEROUS)

### GIT CHECKOUT SOMEONE ELSE REPO
`git checkout --track origin/ECOM-307`



### Git Diff
`git diff –name-only –diff-filter=U`



### Git log HELPER

`git log –graph` 
`git log –oneline`


