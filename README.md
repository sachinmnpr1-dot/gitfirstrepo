# gitlearning-demo
This is my first git repository.
<br>
Author - Sachin Kumar
<br>
1. Install git bash
2. open cmd and run the command: git --version
3. after git bash installation, open git Bash and execute commands like: ls, ls -1, clear, pwd
4. configure git(global, local), since we are using for only 1 user so, we will execute below command in git Bash (~ means root directory, directory means folder):
    git config --global user.name "Sachin Kumar"
    git config --global user.email "sachin.kumar@gmail.com"
    git config --list
5. open VS Code -> create a folder in laptop at any place and use the folder (open folder) in VS Code. Open terminal and execute: git --version
6. PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        7. add new file index.html and add few content:- <p>hello team<p>
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
9. In order to commit changes for only 1 file:- git add index.html 
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
11. In order to get ready for commit for all the files(changes files):- git add .
PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git add .
PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   index.html
12. To commit the changes:- git commit -m "some message"
PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git commit -m "add new paragraph"
[main 54a4013] add new paragraph
 2 files changed, 2 insertions(+), 2 deletions(-)
 create mode 100644 index.html

13. PS C:\Users\Mohamed\Downloads\gitdemo\gitlearning-demo> git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

14. 
