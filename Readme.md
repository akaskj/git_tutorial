# Step by step guide to create a repository on Github and push your local project into the repository

1. Login into your github account
2. Navigate to your profile page and click on "Repository"
3. You will see a green button "New" click that and you will be taken to a page to create a repository
4. Give a name to your project and a small description(this will appear in repository lists) and click create
5. In your local machine if it is Windows download git bash and install from here https://git-scm.com/downloads
   (Use defaluts while installing, you don't have to change any settings while installing it)
6. Go to start type Git Bash and open it
7. Navigate to the folder where you have your project using Git Bash
8. Type "git init" -> this will initialize in the project
9. Then add all your files to commit using >> git add -A <<
10. Commit your files using >> git -m "initial commit" << (initial commit is a message you can replace it with anything
11. Add the remote repository using >> git remote add origin --your clone url-- << 
   --your clone url-- can be found on git hub by clicking on the repository you just created
12. Last step is to push the commit >> git push -u origin master << 


** If you want to add futher changes and push it the repository you will need following 3 commands in the same order **

    git add -A

    git commit -m "your commit message"

    git push -u origin master