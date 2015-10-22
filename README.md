# GitHub Tutorial

by *Gabriel Charriez*

---
## Git vs. GitHub
**Git**: is Version Control which lets you see and keep track of the changes  
  you made to your files
  
**Github**: the same as Git but you can collaborate with others and they can also make changes to your code  
  if you allow them to.  
    Github needs Git but Git doesnt need Github
  
    




---
## Initial Setup
1. Go to the [Github Website](http://www.github.com) and click signup. 
2. Make sure to click the free plan when you see it.  
3. After you sign in you click on the profile icon on the top right
4. Click settings then click SSH Keys
5. Click add SSH key and then go to your nitrous
6. Click your username then go to dashbaord
7. Click the SSH keys tab then copy the SSH key to Github
8. Add SSH Key
9. Go to your nitrous tab then type ssh -T git@github.com then type yes
10.  type in git config in nitrous 
11. Type in global user.name and in quotes type in you name
12. Type in global user.email and in quotes type in your email address

What git config does is that it makes you type in your user name and email so that it can use that information when you 
make commits. If its your first time using git it will make you do this.






---
## Repository Setup
First you make a directory called first repo then cd into it. Then create a README.md file.
To start using git commands besides git commit you must type git init. What this does is that it
creates a repository and whatever directory you are in. To set up your repo you must go to github and
in the top-right click the plus and click new repository. The name of the repo must **ALWAYS**
match the name of your repo on c9. Click on the ssh button and then copy and paste the lines of code that you 
see under "... or push an existing repository from the command line". Make sure to paste them one at a time in
the command line.  

To check if the repository is working do the git add, commit and push commands. These commands
will be explained in the next section.



---
## Workflow & Commands
