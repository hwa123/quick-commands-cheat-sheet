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
git merge origin/master --allow-unreleted-histories | force unrelated histories branches to merge
git rebase -i `<earlier-commit-sha>` | interactive rebase off of a point earlier in the history than the commit you need to modify. In the list of commits being rebased, change the text from `pick` to `edit` next to the hash of the one you want to modify, then save and quit. To change the 1st commit message, use `git rebase -i --root`
git rebase --continue | continue rebase to the next commit which marked as `edit` in previous step, the next nearest commit following chronological order
git commit --amend --reset-author --no-edit | remove committer info from commit message
gut push -f | push changes to remote git branch in fast-forwarding fashion




