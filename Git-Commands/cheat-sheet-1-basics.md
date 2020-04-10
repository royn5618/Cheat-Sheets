# CHEAT-SHEET I

## **Initialising/Cloning a GIT repository**

**To create a NEW LOCAL GIT repository**

`git init`

**To copy from a LOCAL GIT repository**

`git clone /path/to/repository`

**To copy from a LOCAL GIT repository**

`git clone username@host:/path/to/repository`

## **Branching**

**To create a new branch and switch**

`git checkout -b <branchname>`

**To switch to an existing branch**

`git checkout <branchname>`

**To view working branch**

`git branch`

**To delete a branch**

`git branch -d <branchname>`

## **Adding a change to the local repository**

1. Make changes to the file.
2. Verify that the file list of changed files together with the files that are yet to be staged or committed

`git status`

3. Add the file to staging/index

`git add <filename>`

4. Commit the staged changes to head

`git commit -m "Your message about the commit"`

To commit any change that has been added to staging and also the files changed thereafter but not yet in staging:

`git commit -a "Your message about the commit"`

5. To push changes to the branch

`git push origin <branchname>`

To push changes to master

`git push origin master`

Ideally, in collaborative software development environment pull requests are used to approve changes made to master. So, we should push our changes to our WORKING BRANCH and open a pull-request to merge the changes.
