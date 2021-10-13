<h1>STEPS TO CREATE A PULL REQUEST(PR) AND ASK FOR A REVIEW</h1>

STEP 1 - Go to the folder where your have saved the project.
![Step1](images/Step1.png)<br><br>

STEP 2 - Click on the Location bar.
![Step2](images/Step2.png)<br><br>

STEP 3 - Type <strong>cmd</strong>
![Step3](images/Step3.png)<br><br>

STEP 4 - Press <strong>Enter</strong><br>
Command Prompt(cmd) will open.
![Step4](images/Step4.png)<br><br>

STEP 5 - Run, <strong>git status</strong><br>
To check if any chanegs have been commited or not.
![Step5](images/Step5.png)<br><br>

STEP 6 - Creating a separate branch.<br>
Run, <strong>git branch branch_name</strong><br>
You can give any name to the branch.
![Step6](images/Step6.png)<br><br>

STEP 7 - Moving to the created branch.<br>
Run, <strong>git checkout branch_name</strong>
![Step7](images/Step7.png)<br><br>

STEP 8 - Check if you are working in the same branch which you have created.<br>
Run, <strong>git branch</strong>
![Step8](images/Step8.png)<br><br>

STEP 9 - Now make the required changes in the file, save it and come back to the command prompt.<br><br>

STEP 10 - Run, <strong>git status</strong><br>
The changes have not been commited and it shows what are the modifictaion you have made in red text.
![Step10](images/Step10.png)<br><br>

STEP 11 - Let's save the changes here.<br>
Run, <strong>git add .</strong>
![Step11](images/Step11.png)<br><br>

STEP 12 - Let's commit the changes we have made to the branch we are working on.<br>
Run, <strong>git commit -m "Added steps to create PR"</strong><br>
Inside double quotes you specify the changes you have made in one line.
![Step12](images/Step12.png)
It shows the number of files in which you have made the changes and number of insertions and deletions performed in the file.<br><br>


STEP 13 - Let's check the status again.<br>
Run, <strong>git status</strong><br>
![Step13](images/Step13.png)
Yeah, nothing to commit, working tree clean.<br><br>


STEP 14 - Let's push it to the branch. <br>
Run, <strong>git push -u origin branch_name</strong>
![Step14](images/Step14.png)<br><br>


STEP 15 - Now go to the GitHub, open the repository where you want you want the PR. Click on button which says <strong>Compare and Pull Request</strong>.
![Step15](images/Step15.png)<br><br>


STEP 16 - Now check the guidelines for Pull Request in the README.md file of the repository(repo) in a new tab. And type the description according to the guidlines (if mentioned).<br><br>

STEP 17 - Click on <strong>Create Pull Request</strong>.
![Step17](images/Step17.png)<br><br>


<i>Tada.. You have created your first PR and you will be notified once it is accepted by the maintainers of the repo.</i>