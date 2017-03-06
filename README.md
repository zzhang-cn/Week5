# Week5

Instruction to clone the files to your local machine. 

1. Fork the repo to your account using the fork option found on the top right corner. 
   ![Forking](http://i.imgur.com/M0zwgi4.jpg) 
   ![Forking](http://i.imgur.com/G3OSi7S.jpg)

2. Clone the repo using the URL in the right sidebar by the following command on git-bash.
   ```
   git clone https://github.com/Introtocs/Week5.git
   ```
   ![Cloning](http://i.imgur.com/ODRMn3m.jpg)
   ![Cloning](http://i.imgur.com/0RcOulB.jpg)
   Copy the URL given in the URL box in the Download/Clone option. 
   
3. Step 3: Adding the Upstream Remote
   Change into the cloned directory and then at this point, you can add the upstream remote:
   ``` 
   1. cd Week5
   
   2. git remote add upstream <URL of the forked repository in your account>
   ``` 
   This will now allow you to pull in changes from the source locally and merge them, like so:
   ```
   1. git fetch upstream
   
   2. git merge upstream/master
   ```
   
4. Checking Out a Topic Branch
   However, before you make your own changes, checkout a topic branch:
   ```
   git checkout -b name_of_branch
   ```
   The Name of the branch can be any name that you want to keep. 
   
5. Committing
   Now, you can make your changes, and create a commit that tracks just those changes.
   ``` 
   git commit -am "My Changes"
   ```
6. Pushing
   Next, you'll push this topic branch to your own fork of the project.
   
   ```
   git push origin name_of_branch
   ```
   
These steps would keep the repo on your github account synced with the changes you make to the files on your local machine. 

7. Creating a Pull Request
   Finally, you will create a pull request. First, go to your fork of the repo. 
   You might see a "your recently pushed branches", and if so, you can choose "Compare and Pull Request". 
   Otherwise, you can select your branch from the dropdown, and subsequently click "Pull Request" or "Compare" at the top right of the repo section.
