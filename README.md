# Notes

## Some common terminal commands

- cd: Change Directory
  - cd ~ : it gets us to home directory
    - cd .. : it helps us to go back a step
      - cd File/FolderName : to go to the file/folder
- touch FileName : it creates only files such as `cd index.html`
- mkdir FolderName : it creates a folder
- ls : List files and folders
  - ls **-a** : to view hidden files
- rm : to remove file or folder
  - rm -r Folder/FileName : it removes the file/folder
    - rm \* Folder/FileName : it removes all the files/folders
- start : to open the file
- code : to open the file in vs code
  - code `.` : to open the file your are right in now to vs code
    - code -r File/FolderName : it opens the file/folder right in the vs code you are working in

## Git-Bash Commands

- git clone url: Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.
- git init: to initialize git in a folder
- git add: to add the files inside the git repository
  - git add `.` or `-A`: adds all the files in the directory
- git commit -m"Your commitment": Adding commits keep track of our progress and changes as we work . Git considers each commits change point or save point.
    - git commit --amend: Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.
- git status: is used to show the status of the git repository
- git log: it is a record of the all the commits done in the repository
- git diff: shows change between the working tree and the previous tree
- git checkout: switch branches or restores working tree files
- git fetch: Fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.
- git config: A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.
- git merge: A powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.
- git pull: Pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.
- git rebase: Rebasing lets you move branches around, which helps you avoid unnecessary merge commits. The resulting linear history is often much easier to understand and explore.
    - git rebase -i: The -i flag is used to begin an interactive rebasing session. This provides all the benefits of a normal rebase, but gives you the opportunity to add, edit, or delete commits along the way.
- git reflog: Git keeps track of updates to the tip of branches using a mechanism called reflog. This allows you to go back to changesets even though they are not referenced by any branch or tag.
- git reset: Undoes changes to files in the working directory. Resetting lets you clean up or completely remove changes that have not been pushed to a public repository.
- git revert: Undoes a committed snapshot. When you discover a faulty commit, reverting is a safe and easy way to completely remove it from the code base.

`Git CheatSheet: `
[Git CheatSheet](https://education.github.com/git-cheat-sheet-education.pdf)
![Git Cheat-Sheet Image](/git-cheat-sheet.jpg)

### Git-Bash Commands to add files in repository

- git branch -M main: it helps us switch to main branch
- git remote add **origin** url: it helps us to add the repository link to the file. The bold text can be named anything but for developers to understand each others code we use **origin**
- git push **-u** origin main: it helps to push the file in repository
