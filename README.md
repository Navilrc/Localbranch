<!-- Used commands 


--------------------------------------------------------------
Here are the commands mentioned in the video:

git --version: This command is used to check the installed Git version and verify if Git is set up correctly on your system (17:36, 19:53, 23:48).
ls: This is a basic terminal command used to list files and folders in the current directory (19:56, 26:56).
clear: This command is used to clear the terminal window (20:01, 26:46).
pwd: This command is used to print the working directory (current folder) (20:03).
git config --global user.name "Your Name": This command configures Git to associate a username (your name) with your commits globally across all Git repositories on your system (20:34).
git config --global user.email "your.email@example.com": This command configures Git to associate an email address with your commits globally across all Git repositories on your system (21:53).
git config --list: This command displays all the Git configurations set for the current user (22:12).
git clone: This command is used to copy (clone) a Git repository from a remote source (like GitHub) to your local machine (24:37).
cd: This is a basic terminal command used to change the current directory (folder) (25:52).
ls -a: This command is used to list all files, including hidden files, in the current directory (27:21).
git status: This command shows the status of your Git repository, including modified, staged, and untracked files (28:10).


Why is Git free?
How does Git ensure code integrity?
How does Git handle conflicts?
more commands are use mention them
Here are more commands mentioned in the video:

git add: This command is used to add changes from the working directory to the staging area, preparing them for a commit (30:29).
git add .: This command is used to add all changes in the current directory (and its subdirectories) to the staging area (31:01).
git restore --staged: This command is used to unstage a file, moving it back from the staging area to the modified state in the working directory (32:38).
git commit -m "Commit Message": This command is used to save the staged changes to the local repository. The -m flag allows you to add a concise commit message (34:39).
git log: This command displays the commit history, showing information about each commit like the author, date, and commit message (35:10).
git log --oneline: This command displays a condensed, single-line version of the commit history, showing a shortened commit hash and the commit message (35:36).
git reset: This command is used to undo commits. It can move the HEAD pointer to a previous commit, effectively removing subsequent commits from the history (38:09).
git reset --hard: This command forcefully resets the HEAD, index, and working directory to the specified commit, discarding all changes made after that commit (40:02).
git branch: This command lists all local branches in your repository and indicates the currently active branch (42:51).
git branch: This command creates a new branch with the specified name (43:08).
git checkout: This command is used to switch from the current branch to another existing branch (43:24).
git checkout -b: This command creates a new branch and immediately switches to it (44:03).
git merge: This command is used to integrate changes from one branch into the current branch (46:33).
git branch -d: This command deletes the specified local branch (47:49).
git remote -v: This command lists the remote repositories that your local repository is connected to (50:18).
git push origin: This command uploads your local branch commits to the specified remote repository (e.g., origin) (50:48).
git pull origin: This command fetches changes from the remote repository and merges them into your current local branch (52:13).
git pull origin main --allow-unrelated-histories: This command is used when pulling from a remote repository that has a completely separate history, often when initializing a new local repository from an existing remote one (54:02).
git remote add origin: This command connects your local repository to a remote Git repository, giving it a name (commonly origin) (55:00).
git init: This command initializes a new empty Git repository in the current directory, creating a .git subdirectory (55:25).


How to check Git version?
How to view hidden Git files?
How to stage changes?
more 
Here are even more commands mentioned in the video:

git remote rename: This command renames an existing remote connection (1:02:18).
git remote remove: This command removes a specified remote connection from your local repository (1:02:30).
git tag: This command lists all existing tags in the repository (1:02:44).
git tag -a -m "Tag Message": This command creates an annotated tag, which includes a message, committer information, and is generally recommended for releases (1:03:00).
git tag: This command creates a lightweight tag, which is just a pointer to a specific commit (1:03:26).
git push origin: This command pushes a specific tag to the remote repository (1:03:41).
git push origin --tags: This command pushes all local tags to the remote repository (1:03:55).
git tag -d: This command deletes a local tag (1:04:15).
git push origin --delete: This command deletes a tag from the remote repository (1:04:22).
git diff: This command shows the differences between your working directory and the staging area (1:06:56).
git diff --staged: This command shows the differences between the staging area and the last commit (1:07:22).
git diff: This command shows the differences between two specific commits (1:07:44).
git mv: This command is used to move or rename a file within the Git repository (1:08:18).
git rm: This command is used to remove a file from the working directory and stage the deletion (1:08:52).
git revert: This command creates a new commit that undoes the changes introduced in a specific previous commit, without rewriting history (1:09:29).
git cherry-pick: This command applies the changes from a specific commit on one branch to another branch (1:11:43).
git stash: This command temporarily saves changes that are not ready to be committed, allowing you to switch branches or perform other operations without committing incomplete work (1:12:44).
git stash list: This command lists all stashed changes (1:13:28).
git stash pop: This command reapplies the most recently stashed changes and then removes them from the stash list (1:13:46).
git stash apply: This command reapplies the most recently stashed changes but keeps them in the stash list (1:14:02).
git clean -f: This command removes untracked files from the working directory (1:14:52).
git clean -df: This command removes untracked files and untracked directories from the working directory (1:15:07).

-------------------------------------------------------------------------------
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> test-path .git
True
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo>
 *  History restored 

PS C:\Users\navee\Desktop\FOLDERS\Expense tracker> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)
        modified:   Martian-demo (modified content)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Local_Repo/

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker> cd .\Local_Repo\
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html
        new file:   style.css

PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git commit -m "add initial files"
[master (root-commit) fe8fba2] add initial files
 2 files changed, 5 insertions(+)
 create mode 100644 index.html
 create mode 100644 style.css
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git remote add origin https://github.com/Navilrc/Localbranch.git
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git branch
* master
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git branch -M main
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git branch
* main
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git puch origin main
git: 'puch' is not a git command. See 'git --help'.

The most similar command is
        push
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo> git push -u  origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 305 bytes | 305.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Navilrc/Localbranch.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\navee\Desktop\FOLDERS\Expense tracker\Local_Repo>  -->