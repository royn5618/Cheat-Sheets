# CHEAT-SHEET III

## **Working with Git Stash**

Usage: To record the current state of the working directory and the index and to go back to a clean working directory.

`git stash save "your_message"`

The "your_message" makes it easier to locate the stash state in the stash list.

`git stash list` - gets the list of stashed working directories numbered like stash@{0}, stash@{1} and so on.

`git stash clear` - clears ALL the stash states

`git stash drop stash@{1}` - drops the selected stash tree, in this case,the second last stashed state. *Default - Last stashed state*

`git stash apply stash@{1}` - removes the selected stashed state from the stash list and apply on top of the current working tree state. *Default - Last stashed state*

`git stash pop stash@{1}` - removes the selected stashed state from the stash list and apply on top of the current working tree state. Additionally, it deletes the popped stash state. *Default - Last stashed state*
