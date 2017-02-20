# git-tricks

```sh
# Création d'une branche locale qui est la copie de la branche distante
# --track is shorthand for git checkout -b [branch] [remotename]/[branch]
git checkout --track origin/remote_branch

# Stages deleted + modified files (not new files) and commit 
git commit -a -m "commit message"

```
# return to the previous commit
git reset --hard HEAD~1

# push commit and delete commit after Head1
git push origin HEAD --force
