Command | Description
--------|------------
git config --global http.sslVerify false | To avoid SSL certificate problem: Unable to get local issuer certificate
git commit -a --allow-empty-message -m '' | To do an empty commit message
git branch -m new-name | Rename your local branch
git branch -m old-name new-name | Rename your local branch when on a different branch
git push origin :old-name new-name | Delete the old-name remote branch and push the new-name local branch
git push --delete origin tag-name | Remove remote tag
git tag -d tag-name | Remove local tag
git fetch origin && git rebase origin/master | Rebase local branch with remote master
git commit --amend | Edit commit message if needed
git branch --track branch-name remote-git/branch | use local branch to track remote git branch
