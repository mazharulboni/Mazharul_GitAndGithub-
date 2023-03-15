1. Create a git repository “YourName_GitAndGithub” to your GitHub account and make it public.
Ans:
    a. Go to Github and create a new repository as "Mazharul_GitAndGitHUb"
    b. Make sure to check "Public" button while creating the repo
    c. Open a terminal or Git Bash/intelleji terminal from local machine.
    d. Create a directory as "guthubquiz" where my local repository.
    e. command: cd guthubquiz
    f. Create a file as "practiceFile", write something or edit the file
    g. command: git status, to check the git status of the repo
    h. command: git init, if git not found in the repo
    i. command: git status, to see if the file ready/need to be add
    j. command: git add ., to add the files to git
    k. command: git commit -m "any message", to commit the file
    l. command: git remote add practiceFile https://github.com/mazharulboni/Mazharul_GitAndGithub-.git
    m. command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git


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
    command: git remote add filename https://github.com/mazharulboni/Mazharul_GitAndGithub-.git
    command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git

14. Add a feature branch “differences” to your repository. Check how many branches you have now. then set your current branch as the “differences” branch.
Ans:
    command: git branch differences
    Two branches now, main and differences


15. Update the text files (1. Git. text 2. GitHub.text) by writing the features of git and GitHub
Ans:
    Open git.txt, make necessary changes, save the changes.
    Open github.txt, make necessary changes, save the changes.


16. Adds one more file “difference. text”. write differences between git and GitHub on that file.
Ans:
    touch differences.txt
    nano differences.txt, edit and save the change


17. Update the README.md file. write the uses git commands, usage, and answers which you have finished.
Ans:
    nano README.md
    Copy and paste te answer


18. See the changes by the respective git command.
Ans:
    git status

19. Push all the changes to the remote.
    Command: git add .
    command: git commit -m "any message", to commit the file
    command: git remote add filename https://github.com/mazharulboni/Mazharul_GitAndGithub-.git
    command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git

20. Do you see any changes between your two branches?
Ans:
    Yes I do

21. Set your current branch as the “Master” Branch. and merge with the feature branch (“differences”).  (After this step it's little advance for you at this stage of the course, but you can try.)
Ans:
    I switched the Master branch as default branch
    Merge the changes

22. Do you see any changes between your two branches?
Ans:
    I see no changes as feature and main branches are merged

23. Push all the changes to the remote.
Ans:
        Command: git add .
        command: git commit -m "any message", to commit the file
        command: git remote add filename https://github.com/mazharulboni/Mazharul_GitAndGithub-.git
        command: git push -u origin main https://github.com/mazharulboni/Mazharul_GitAndGithub-.git

24. Update the README.md file. write the uses git commands, usage, and answers which you have finished.
Ans:
    Update the README.md file in master branch

25. Invite a Contributor to your repository. Give him the feature branch “differences” clone link. So that he only clones the “differences” branch.
Ans:
Go to the repository page on GitHub.
Click on the "Settings" tab.
Click on the "Manage access" option in the left sidebar.
Click on the "Invite a collaborator" button.
Enter the username I want to invite.
Click on the "Add [username/email address]" button to send the invitation.


26. Tell him to update 1. Git. text 2. GitHub.text files by adding more details about git and GitHub.
Ans:
    Switch back to my second github account. accept the invitation.
    Open the repository
    Open git.txt, make changes, propose changes, in the “master” branch
    Open github.txt, make changes, propose changes, in the “master” branch

27. Update the 1. Git. text file by adding or removing some lines in the “master” branch.
Ans: done

28. Tell your contributor to push his changes.
Ans:
    from contributor account:
    Compare and Pull the changes
    Create Pull request on git.txt
    Create Pull request on github.txt


29. Merge Your contributor changes to your “master” branch. Is there any error or warning you have faced?
Ans:
    From my main github account:
    In my inbox two files are ready to merge
    Open the file ony by one
    Merge pull request
    Confirm merge

30. If there are no conflicts? “if No”, You can continue at 24.

“if No”, solve the conflict.

Ans: No conflict
