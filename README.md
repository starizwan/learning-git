# Learn Git & GitHub Essentials
Based on the tutorial provided by amigoscode, [Git and GitHub Tutorial For Beginners](https://youtu.be/3fUbBnN_H2c).  
<br/>The aim of this documentation is to provide a basic understanding of Git & GitHub
## Table of contents
1. Installation & Setup
2. Basics of Git
3. SSH to GitHub
4. Push & Pull
5. Branch & Merge
6. Rebase
7. Git Desktop Clients
8. Further reading


### Installation & Setup
The following text contains a step by step guide to install git on your local machine
#### MacOS X
Installing with homebrew is the easiest option to install git
1. Install [Homebrew](https://brew.sh/) if not already installed
2. Install git by using: `brew install git`
3. Verify the installation: `git --version`
<br/><br/>**Setting up**
<br/><sub>Replace name and email with your own. These details will be associated with any commits that you create.</sub>
1. Configure your Git username : `git config --global user.name "John Doe"`
2. Configure your Git email : `git config --global user.email "johndoe@gmail.com"`

<br/>You can use `git help` command to view some of the common commands

### Basics of Git
  Before executing any command we first need to initialise the current directory: `git init`</br>
  <sub>This will create a folder called .git in the current directory. It initializes the current directory as a git repository. Use `ls -a` to see all the files & folders.</sub>
  </br>
![Screenshot_2021-05-17_at_12 36 23_PM](https://user-images.githubusercontent.com/34064583/119927834-df2a7280-bf97-11eb-8e58-0a906e5604ea.png)
</br>
#### git add 
Use `git add .` to add all of the files from current directory to the staging area.
</br>Use `git commit -m "commit message"` to commit the staged files in git repository.

## To be continued

