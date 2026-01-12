<!-- Used commands 

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