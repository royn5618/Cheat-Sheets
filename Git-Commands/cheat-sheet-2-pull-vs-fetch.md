# CHEAT-SHEET II

## **Updating local repository FROM remote repository**

**To effect (merge) changes from remote to local repository**

`git pull`

or

`git fetch`

`git merge <branchname>`

**NB:** git pull is nothing but git fetch and merge branch under the hood with automatic branching strategies applied.

**Difference between git pull and git fetch:**

git pull | git fetch
------------ | -------------
Only downloads new data or meta-data information from the remote repository but it doesn't integrate any of the updates into the working files | update the current HEAD branch with the latest changes from the remote server. This means that pull not only downloads updates but it also directly integrates them into your current working copy files
Might cause merge conflicts because it tries to merge remote changes to local repository  | Does not cause merge conflicts. It never attempts to change the state of the local repository
Should be executed on clean working copy to avoid merge conflicts | Can be execute anytime to view changes in the remote repository


