# PLPBasicGitAssignment
# documentation


 # Create a New Repository


Go to https://github.com/.
Sign in to your GitHub account.
In the top right corner, click the plus sign (+) and select "New repository".
Enter a name for your repository. This will be the name of the folder that your repository is stored in on GitHub.
Optionally, add a description for your repository. This will help other people understand what your repository is for.
Select whether your repository should be public or private. Public repositories can be seen by anyone on the internet. Private repositories can only be seen by people who you have invited to collaborate on the repository.
Click "Create repository".


 # Initialize a Local Repository


Open a terminal window.

Navigate to the directory where you want to store your local copy of your repository.

Run the following command:


git init



This will create a new directory called .git in your current directory. This directory will contain all of the Git metadata for your repository.



 # Add Files to Your Repository


Add the files that you want to include in your repository to your local directory.



Run the following command:



git add .



This will add all of the files in your current directory to the staging area.



 # ommit Your Changes


Run the following command:



git commit -m "Add initial files"



This will create a new commit in your local repository. The commit message is a brief description of what you changed in this commit.



 Push Your Repository to GitHub


Run the following command:



git remote add origin https://github.com/<your-username>/<your-repository-name>.git



This will add a new remote repository called origin that points to your GitHub repository.

# push to remote repository

Run the following command:



git push -u origin main



This will push your local repository to your GitHub repository. 