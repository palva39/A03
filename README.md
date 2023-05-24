# A03
## Git and GitHub SetUp##
1. Getting Started with [Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
2. Follow the directions stated in the website above to make sure its a clean installation
3. Head over to [Download Git](https://git-scm.com/download/win)
4. After installing Git, you are able to create a "repository" using Git Bash
5. For a clearer explanation head over to [Git and GitHub Setup](https://www.codecademy.com/article/f1-u3-git-setup)
6. Opening up Git Bash which is a CLI where Git commands are used, type in ***git --version*** to make sure Git is installed
7. Making sure everything is installed correctly, make a GitHub account to be able to do this process
8. Navigate to GitHub’s articles on setting up your [Git username](https://docs.github.com/en/get-started/quickstart/set-up-git) and [email](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address) and follow the instructions for each using Git Bash.
9. Now that everything is set up, using the following commands in website in **STEP 5** to practice your Git skills on your local computer to initialize a Git repository which will be used later
10. After commiting your changes in the Git Bash command line, you are able to start the next process with GitHub and make sure your in the main Branch
11. Create a repository in GitHub and then link it to a local repository on your computer which allows to backup your work constanlty and safely.
12. On GitHub, create a new repository by clicking the New repository button on the home page.
13. After creating a repository, GitHub displays the repository page. At the top of the page, make sure ***“HTTPS”*** is selected.
14. Copy the Git commands on the GitHub page, under the title “…or push an existing repository from the command line”, and paste them into your Command Line Interface. Running these commands will add a remote repository, and then push your local repository to the remote repository.
15. Now your README.txt should be updated to the previous commands that were entered in **STEP 9** in your GitHub page README.txt file

## Webstorm SetUp ##
1. Download [Webstorm](https://www.jetbrains.com/webstorm/download/#section=windows) make sure you have a license to be able to use all tools
2. Follow the instructions in the installation wizard and make sure to enable the pathway
3. After installing Webstorm, open up the settings and click on manage licenses and make sure you are logged in with your jetbrains account to enable the license
4. Once that's complete, it's time to connect your GitHub account and Git together with Webstorm 
5. Press <kbd> CTRL + ALT + S</kbd> in the Webstorm application and head over to the GitHub section and connect your account. 
6. Git is already part of Webstorm through the version control which can be enabled when doing a project
7. Once you have opened a folder in WebStorm, the .idea subfolder is added to it where WebStorm stores its internal configuration settings, for example, for the project code style or the version control system.
8. On the Welcome Screen, click Open and then select the folder with your application in the dialog that opens.
9. Click Get from VCS on the Welcome screen and make sure its Git
10. Click Create New Project on the Welcome screen or select File | New | Project from the main menu. The New Project dialog opens.

<details>
  <summary><h3>References</h3></summary>
  <p>https://www.codecademy.com/article/f1-u3-git-setup</p>
  <p>https://docs.github.com/en/get-started/quickstart/set-up-git</p>
  <p>https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address</p>
  <p>https://git-scm.com/book/en/v2/Getting-Started-Installing-Git</p>
  <p>https://git-scm.com/download/win</p>
  <p>https://www.jetbrains.com/help/webstorm/github.html#register-account</p>
  <p>https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html#put-existing-project-under-Git</p>
  <p>https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html</p>
 </details>
  
<details>
  <summary><h3>Glossary<h3></summary>
  <p><strong>Branch</strong>: is a pointer to a specific snapshot of the project's changes. It represents an independent line of development.</p>
    <p><strong>Clone</strong>: to create a local copy of a remote repository on your own computer. This copy includes all of the repository's files, history, and branches.</p>
    <p><strong>Commit</strong>: a record of changes to a repository. Each commit has a unique ID (also called a hash), which allows you to keep track of specific changes.</p>
    <p><strong>Fetch</strong>: is a Git command used to get branches and/or tags from a remote repository, along with the objects necessary to complete their histories.</p>
    <p><strong>GIT</strong>: a free, open-source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.</p>
    <p><strong>GitHub</strong>: s a web-based hosting service for version control repositories, typically those using Git. It provides a platform for collaboration, allowing developers to contribute to projects, track issues, and manage changes.</p>
     <p><strong>Merge</strong>: is a command that integrates changes from one branch into another.</p>
     <p><strong>Merge Conflict</strong>: occurs when Git is unable to automatically resolve differences in code between two commits. This typically happens when two branches have made different changes to the same part of a file and then those branches are merged together.</p>
    <p><strong>Push</strong>: Git command used to upload local repository content to a remote repository. After making commits in your local repository, you would use 'push' to sync your changes with the remote repository.</p>
    <p><strong>Pull</strong>: Git command used to fetch and download content from a remote repository and immediately update the local repository to match that content.</p>
    <p><strong>Remote</strong>: In Git, a remote refers to another copy of the repository that is usually hosted on a remote server.</p>
    <p><strong>Repository</strong>: is a directory where Git has been initiated to track and store changes in files. Repositories can exist locally on a developer's machine or as a remote copy on another computer or a server.</p>
