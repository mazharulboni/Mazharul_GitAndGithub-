1. Create a git repository “YourName_GitAndGithub” to your GitHub account and make it public.
Ans:
    a. Go to Github and create a new repository as "Mazharul_GitAndGitHUb"
    b. Make sure to check "Public" button while creating the repo.


2. Clone this repository to your local machine.
Ans:
    a. Copy the HTTPS from local GitHub repo
    b. command: cd guthubquiz, to go inside the repo, from local machine
    c. command: git clone "https://github.com/mazharulboni/Mazharul_GitAndGithub-.git", enter, file should be cloned

3. Check which branch you are in now. Is it the “Master” branch?
Ans: Yes

4. Add two text files in this “Master” branch. 1. Git. text 2. GitHub.text
Ans.
    Command: touch git.txt github.txt

5. Write something about git and GitHub (at least 100 words) in the respective .text file.
Ans:
    Command: nano git.txt, Write 100 words about git, ctrl+x, y, enter
    Command: nano github.txt, Write 100 words about github, ctrl+x, y, enter
    
6. Add a README.md file. write the uses git commands, usage, and answers which you have finished.
Ans:
    Command: README.md
    Command: nano README.md, save the answer, ctrl+x, y, enter

7. See the changes by the respective git command.
Ans:
    Command: git log

8. Now Push your Changes to remote. and check the remote changes.
Ans:
       command: git init, if git not found in the repo
       command: git status, to see if the file ready/need to be add
       command: git add ., to add the files to git
       command: git commit -m "any message", to commit the file
       Command: git remote add origin https://github.com/mazharulboni/Mazharul_GitAndGithub-.git
       command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git

9. Add a “temp” folder in the local directory. and some files(image, video) to that folder.
Ans:
    command: mkdir temp
    Command: cp Pictures/image temp/
    Command: cp Videos/video temp/

10. Add a “.gitignore” file to your local directory.
Ans:
    command: touch .gitignore, from the temp directory

11. Declare the “temp” folder in the “.gitignore” file because you don’t want to store these files in the remote repository.
Ans:
    Command: nano .gitignore
            Declare in the text editor to ignore this file

12. See the local changes by the respective git command.
Ans:
    Command: git init
    Command: git status


13. Now-Again push all the changes to the remote repository.
Ans:
    Command: git add .
    command: git commit -m "any message", to commit the file
    command: git remote add practiceFile https://github.com/mazharulboni/Mazharul_GitAndGithub-.git
    command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git

14. Add a feature branch “differences” to your repository. Check how many branches you have now. then set your current branch as the “differences” branch.
Ans:
    Go to github repo, click Branches, New Branches, enter branch name as ""differences"
    I have two branches now, Master branch and differences branch
    to make differences as current or default branch, go to setting > branches > switch the branch to differences as default branch, update

15. Update the text files (1. Git. text 2. GitHub.text) by writing the features of git and GitHub
Ans:
    Open git.txt from feature branch, make necessary changes, commit the changes.
    Open github.txt from feature branch, make necessary changes, commit the changes.


16. Adds one more file “difference. text”. write differences between git and GitHub on that file.
Ans:
    From feature branch > click Add file > Create New File
    Enter file name as "differences.txt" > write differences between git and GitHub on that file
    Click Commit new file, file should be added
Updated
