### Set Credential Store (Stop typing credential for git push)
* git config credential.helper store
</br>

### Configure Commit Editor as VS Code
* git config --global core.editor "code --wait"
</br>

### Git Cheat Sheet
* git status
* git add **_filename_**
* git rm --cached **_filename_** (descrption: remove file from commit, will show deleted in git status)
* git commit
* git push
* git remote get-url origin
* git log (description: show commit/branch history)
* git log --oneline --color --graph --all --decorate
* git status
* git merge (description: merge branch to current)
* git merge --no-ff **_branch-name_**
* git reset **_filename_** (descrption: remove file from commit, will not show deleted in git status)
* git reset --hard (description: remove changes at staging)
* git reset --soft HEAD~1 (description: go back to previous 1 commit)
</br> 

### Git Branch Steps
1. git branch **_feature-or-function-name_**
2. git checkout **_feature-or-function-name_**
3. git push origin **_feature-or-function-name_**
4. git push HEAD
5. git push -u origin **_feature-or-function-name_**
6. git checkout -b **_feature-or-function-name_**
7. git push -u **_feature-or-function-name_**

