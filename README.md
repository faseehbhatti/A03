# A03

**Step 1.** First you need to create an account with GITHUB. 
        
**Step 2.** After you create a GITHUB account, you should create a Webstorm account and download the program. 
        
**Step 3.** After downloading and installing Webstorm, you must install GIT as a local program. 
      
**Step 4.** Next we are going to connect GITHUB with Webstorm.
        Press (ctrl+alt+shift) for system preferences and navigate to Version Control.
        In version control, select GIT as the verion control and enter the path to git.exe.
        Next, navigate to Appearance and Behavior -> System Settings -> Passwords and enter your GITHUB password.
        
**Step 5.** Now that we have GITHUB connected to Webstorm, it's time to create our first repository.
        A repository is a central location where data is stored and managed.
        To create your repository, click the "+" sign in the upper right corner of GITHUB and choose "Create new repository".
        Make sure your repository is public and add the readme file.
        Complete this step by clicking "create".
        (You can also create a repository from Webstorm by clicking VCS -> Import into version control)
        
**Step 6.** Next, we will import a repository from GITHUB into Webstorm.
        From the main page of Webstorm, we will select "Checkout from version control" -> GIT.
        Enter the repository URL and specify the local path.
        
**Step 7.** Afterwards, we will create a file in Webstorm.
        choose File -> HTML -> HTML5 to create an HTML file.
        (After editing the file, you may add the file to GIT. This adds it to the local file system.)
        
**Step 8.** The next step is to commit your changes.
                
**Step 9.** When doing a project in Webstorm, the project is not automatically saved or uploaded to GITHUB.
        In order to get your project uploaded to GITHUB, you have to push the project with VCS -> GIT -> Push.
        
**Step 10.** Congrats! Your file is now on GITHUB! 
         You may change the repository name and tinker with the settings.
         When choosing the GITHUB page location, select "Master Branch".
         
**Definitions**

    **GIT is a version control software that keeps track of the changes to source code.**     
   
    **Webstorm is a Javascript integrated development environment (IDE) that can connect to your GITHUB account.**

    **GITHUB is a version control system that keeps track of changes to a source code and allows multiple people to work on it at the same time.**

    **A commit is a record of change for yourself and your collaborators to see when looking for changes to the file.**

    **A push is a sending of your project to a remote repository (i.e. GITHUB).**
        
    **Likewise, A pull is the requesting of a project from a remote repository.**
    
    **A branch is used to isolate development work without affecting other parts of the repository.**

    **The "clone" command downloads an existing GITHUB repository onto your local computer.**

    **A "merge" is GIT's way of putting a split history back together again.**

    **A "merge conflict" is when you erge branches that have conflicting commits and GIT need you to decide which one to keep.**

    **A "fetch" command downloads files from a remote repository into your local repository.**

    **A "remote" is a common repository in GITHUB that all team members if a project use in order to exchange changes.**
    

Sources:

https://www.git-tower.com/learn/git/glossary/remote

https://help.github.com/en/articles/about-merge-conflicts

https://www.git-tower.com/learn/git/commands/git-clone

https://www.atlassian.com/git/tutorials/using-branches/git-merge

https://help.github.com/en/articles/about-branches

https://www.merriam-webster.com/dictionary/repository

https://stackoverflow.com/questions/13321556/difference-between-git-and-github

https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html
