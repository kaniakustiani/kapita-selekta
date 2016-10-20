Github is git repository server is most famous nowadays. With github we can drew up a public repository that could be seen by many people and is open source. Github is a web-based hosting service for projects software development using Git revision control system. Github offers personal repository for paid plans, and free accounts for open source projects. Github is the most popular source code repository site is open. Github is also the best place to share code with friends, coworkers, classmates, and foreigners. More than two million people use GitHub to build amazing things together. With collaborative features GitHub.com, desktop and mobile applications, and GitHub Enterprise, has never been easier for individuals and teams to write better code, faster.

The first step using Github:


1. Download the Git software at http://git-scm.com/downloads. After the download is completed, please install as usual until completed.


2. Next entry into the web page Github.com and login with your account, if not yet have an account can sign up.


3. Before you create the repository we must make-ssh key in advance because it is used to interact with the repository.


4. Afterwards enter the Account settings on the view menu of the top right corner. In the settings menu select SSH Keys and then click SSH Keys. SSH key is later used to interact with the repository.


Then how the steps get ssh key:


-Open the application git bash is installed last. Type the command ssh-keygen will appear a message where the files will be stored, keygen

-Press enter then by default be stored in the folder. ssh enter a folder stored in the id_rsa file folders. ssh, type ssh cd.

-After entering into a folder type the command cat < URid_rsa.pub Copy and paste the code into a web page on github.

-If the git bash can't do the copy, then we need to enter the code into a text file. By typing: cat URid_rsa.pub URrsa.txt touch URrsa.txt > Open explorer incoming folder.. \users\.ssh and open the file rsa. text and copy the key.

Next-enter key into your github as described above. Click Add Key and installing git is finished.


After you create a ssh key, now – we create a repository.


The following the steps:


1. create an account at github.com

2. download the git bash softwer

3. go to the directory where the PHP project you guys are, e.g. "C:/XAMPP/htdocs/Belajar". Source code available on this PHP Project folder which we will enter into the Git repository and we upload to Github

4. for Windows users right click in the folder and select the Git Bash


In Git Bash


1. Do the initialization by typing the following command in Git Bash last "git init" command will create a local repository for our projects

2. Logging into github and create a new repository by clicking the button located at the top right, beside my photos. Note the picture below

3. create a repository with the name "learned" misalnyaMembuat Gihub Repo

4. Now we can access the remote repository url https://github.com/xinmaxi/beljar.git for example.

5. Return to the Git Bash. Add a remote repository that just now we make so that we can project uploaded. Following his command "git remote add origin https://github.com/xinmaxi/beljar.git

6. Next we download first readme file exists by default when we create a repository on github by typing the command "git pull origin master"

7. the next step is to insert the file. Please create a new example, fle URmaxi.php yg want uploaded to github. After that in git bash type "ls" to see the contents of your directory, it will look URmaxi.php. For the memasukkna file it to github type "git add URmaxi.php"

8. After that save changes to repostiroy with peritah do "git commit-m" success "

9. Last is upload to Github with the command "git push origin master"

10. Check on github so ktia file already there

11. With this process of adding data to the github sdh finished, then what if we want to edit? Is it easy. staying open script yg mw edited via notepad, and type "git commit-am" edit "

12. the Last type "git push"