STEPS TO CREATE A PULL REQUEST(PR) AND ASK FOR A REVIEW

Step 1 - Go to the folder where your have saved the project.
![](.png)

Step 2 - Click on the Location bar.

Step 3 - Type 'cmd'

Step 4 - Press 'Enter'
Command Prompt(cmd) will open.

Step 5 - Type 'git status'
To check if any chanegs have been commited or not.

Step 6 - Creating a separate branch.
Type 'git branch branch_name'
You can give any name to the branch.

Step 7 - Moving to the created branch.
Type 'git checkout branch_name'

Step 8 - Check if you are working in the same branch which you have created.
Type 'git branch'

Step 9 - Now make the required changes in the file, save it and come back to the command prompt.

Step 10 - Type 'git status'
The changes have not been commited and it shows what are the modifictaion you have made in red text.

Step 11 - Let's save the changes here.
Type 'git add .'

Step 12 - Let's commit the changes we have made to the branch we are working on.
Type 'git commit -m "Added steps to create PR"'
Inside double quotes you specify the changes you have made in one line.
It shows the number of files in which you have made the changes and number of insertions and deletions performed in the file.

Step 13 - Let's check the status again.
Type 'git status'
Yeah, nothing to commit, working tree clean.

Step 14 - Let's push it to the branch.
Type 'git push -u origin branch_name'

Step 15 - Now go to the GitHub, open the repository where you want you want the PR.

Step 16 - Click on button which says 'Compare and Pull Request'.

Step 17 - Now check the guidelines for Pull Request in the README.md file of the repository(repo) in a new tab. And type the description according to the guidlines (if mentioned).

Step 18 - Click on 'Pull Request'.

Tada.. You have created your first PR and you will be notified once it is accepted by the maintainers of the repo.