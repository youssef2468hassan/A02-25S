# A02-s25

#Github Tutorial:

Step 1:
  The first step is to set up your github account - first visit the offcial github page here https://github.com/

Step 2: 
  Click the sign Up button and then enter the following:
     Email Address
     Username and Password 
     Finally complete the verification code by going to your email and copy and pasting it when asked by github. 
     
Step 3:
 Sign into your github by going to the offcial page and then clicking the "Login" button.
 
Step 4:
  Click New button on the left hand side of the screen on your main page - it will bring you to a new page

Step 5:
in the "Repository name" enter the desired name for your repository

Step 6:
Cutomize your github repository:
     you can choose to make it public or private depending on your needs, for publinc anyone can see it for private only invited people/contribtuers can have access to the repository

Step 7:
Add/Open a README file:
   The readME file should contain essential details about the repository like:
     Your name
     Course section and class (if student) 
     a little about yourself
     and also what is the intended purpose/reason for creating this repository

Step 8:
  Double Check/ Finally commit your changes:
    On the top right of the README file editor you can see an option to either cancel or commit chnages:
      choose the "Commit Changes" to make sure your changes are saved 


#Git Tutorial:

Step 1: 
Go to the official git page and download based on your operating system - the page can be found here https://git-scm.com/

Step 2:
 After downloading git and opening it in your terminal on VS code, enter the following commands:
 git config --global user.name "Your Name"
 git config --global user.email "your_email@example.com" 
 and to confirm  it's configuration
 git config --list

Step 3: 
Make a new folder on your computer for example lets call it "A02": 
mkdir A02 - creates the directory 
cd A02 - chages into the directory 

Initialize Git in the folder
git init 

Step 4: 
Open your project folder and edit or add files (like README.md). Check which files were changed: 
git status
Stage the changes 
git add 
commit the changes
git commit -m "Task: Added Git tutorial to README.md"

Step 5:
Push your changes to remote repository
  Use the command:
   git push origin "Branch name" - to push your chnages to the branch you want to.

 Step 6:
 Check your changes on github:
    Congratulations if everything went smoothly you should now see your changes on github







Definitions:

Branch - A separate version of a project where someone can work on new ideas without changing the main code.
Clone - A copy of a project from GitHub that someone can download to your computer and  work on.
Commit - Saving your work with a short message explaining the changes you made to it.
Fetch - Checking for updates from GitHub without adding them to your work yet.
GIT - A tool that helps you track changes in code and work with other people without messing things up, it allows you to save it on your device locally.
Github - A website where you can store, share, and work on code with others using Git.
Merge - Combining changes from one branch into another branch to keep everything up to date.
Merge Conflict -  A problem that happens when two people change the same part of the code and Git doesn’t know which change to keep.
Push - Sending your saved changes from your computer to GitHub. 
Pull - Bringing the latest updates from GitHub to your computer.
Remote - The online version of your project usually stored on GitHub.
Repository - A folder on GitHub that stores your project’s files and tracks all changes.


References: 

github official  page : https://github.com/
freecodecamp Page: https://www.freecodecamp.org/news/guide-to-git-github-for-beginners-and-experienced-devs/
official git page: https://git-scm.com/



