# gitlearning-demo
This is my first git repository.
<br>
Author - Sachin Kumar
<br>
1. Install git bash <br><br>
2. open cmd and run the command: git --version <br><br>
3. after git bash installation, open git Bash and execute commands like: ls, ls -1, clear, pwd <br><br>
4. configure git(global, local), since we are using for only 1 user so, we will execute below command in git Bash (~ means root directory, directory means folder):
    git config --global user.name "Sachin Kumar"
    git config --global user.email "sachin.kumar@gmail.com"
    git config --list
    <br><br>
5. open VS Code -> create a folder in laptop at any place and use the folder (open folder) in VS Code. Open terminal and execute: git --version 
<br><br>
6. PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
<br><br>
7. add new file index.html and add few content:- <p>hello team<p> <br><br>
8. PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

git status:
   untracked  - new files that git doesn't yet track
   modified   - changed
   staged     - file is ready to be committed
   unmodified - unchanged
<br><br>
9. In order to commit changes for only 1 file:- git add index.html  
<br><br>
10. PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
<br><br>
11. In order to get ready for commit for all the files(changes files):- git add .
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\gitfirstrepo> git add .
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\gitfirstrepo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html
<br><br>
12. To commit the changes:- git commit -m "some message"
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\gitfirstrepo> git commit -m "add new paragraph"
[main 54a4013] add new paragraph
 2 files changed, 2 insertions(+), 2 deletions(-)
 create mode 100644 index.html
<br><br>
13. PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
<br><br>
14. In order to push the changes in branch(main): git push origin main 
PS C:\Users\Mohamed\Downloads\sachinmnpr1-dot\gitfirstrepo> git push origin main
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 355 bytes | 39.00 KiB/s, done.
Total 4 (delta 1), reused 1 (delta 1), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/sachinmnpr1-dot/gitfirstrepo.git
   a7f531b..62a30a6  main -> main
<br><br>
15. Now we can see the changes in the file, directly open the git file
