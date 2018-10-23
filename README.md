# GitHub Tutorial

_by <GillespieSeshimey>_

---
## Git vs. GitHub
Git is a workspace for code where you can edit your code to any time interval you want. Mainly used for code projects that invole multiple people to produce or just to show different projects that other people might want to use and try for themselves.
Github is a just a programming institution for code with multiple syntaxes of coding languages such as Javascript,Java,Lua,Python,etc...


---
## Initial Setup

For this task we'll be using a development environment called cloud9 which uses most programming languages, This will get our code connected to github services.

Phase 1: 

To make a cloud9 account first you would have to sign up with your email and a password. After click on the gear icon and click "connected services" press the green connect button and it should say that your cloud9 and github are linked.

Phase 2: 

To make a github account you would obviously need to Sign up by putting your email address and a secure password, Verify it with your email and you should be done with your github account

Phase 3:

Establishing a SSH key which requires you to go into your settings tab in github and click on SSH and GPG keys then click "New SSH Key" the section where it says title type in "cloud9" ('Since Cloud9 Supports most programming languages we will put that as our title') When you're done go into your cloud9 browser and go to the gear icon and click "SSH keys" copy and paste the 2nd paragraph of syntax and paste it into the Key section on your github browser

End of Initial Setup
---
## Repository Setup
It's' time to make your first repo but first you probably to know what a repo is in short repo means "repository" this is where your future projects will be stored and saved for eternity compare this to a attic where you place your necessities to store.

Important Notes - git status is a necessary part for this section this will allow you to see all the files that were made onto the staging area. If the file name is green then the file you edited was correctly added into the staging are if red read steps 8 - 9 to fix

Let's Start!

Step 1: Type "cd ~/workspace" in your command interface 
/workspace is like your hardware a place where all units are connected to use this to direct to any other directory you want

Step 2: Type "mkdir first-repo" 
Your directory name doesn't have to be "first-repo" name it anything you like.

Step 3: Type "cd first-repo"
This will change your directory to the one you just made

Step 4: Type "git init"
Git init is a command that connects to cloud9, typing "git init" will establish a link between the directories you made from git to cloud9 (More explantion will be given further onto the steps.) Primarily you would be using this command a lot for future projects

Step 5: Type touch README.md
"Touch" is a command that allows you to make files to directories. In light terms its like putting files in a folder.

Step 6: Open README.md and type in anything you want
(Theres no command for this just double click it on the left tab)

Step 7: Press "Ctrl+S" on your keyboard
Pressing Ctrl+S on your keyboard will save the comments you made on your README.md file usually cloud9 just autosaves so you probably won't have to worry about this step

Step 8: Type in "git add README.md"
This will add README.md to the staging area to view it (Look at important notes if extra guidance)

Step 9: Type in "git commit -m "created README.md"
This command is like a notepad of what you did so you aren't confused on what changes or things you made.

Step 10: Go into github and click the plus icon and select new respitories. Input the data that they give to you.
The respitory name should be the same as what your directory is called.

Step 11: Press the SSH button and copy the link given to you.

Step 12:
Type in "git remote add origin git@github.com:<YourgithubUsername>/first-repo.git"
Don't add the < > when your using this command.

Step 13: Type in "git push -u origin master"
This is like a link between cloud9 and github, github will be where you can access your first repo.

Congratulations you made your first repo!!
---
## Workflow & Commands



---
## Rolling Back Changes