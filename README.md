# A03
   <br>
   
## Account and install tutorials
### How to install Git on Mac:
To install git in mac, click the launchpad icon on the dock. When the dock is open, locate and open "Terminal". After Terminal is opened, simply type and enter "Git". If xcode is not already installed, you will then be promted to install xcode. Otherwise, git will install and setup- where you then follow the on screen instructions to accept the eula. After the eula is accepted, git is installed and ready to use.

<!-- no citation, learned from own work-->


### How to install Git on Windows:
To install git on windows, click the search bar and type "Terminal". When Terminal is open, type and enter "winget install --id Git.Git -e --source winget". Git will then start to download onto your machine. When the download is complete, a setep by step installer window will open where you can finish your install of git. (https://git-scm.com/download/win)

### How to verify git installation:
In order to verify git is intalled on mac or windows, reopen your terminal, then type and enter "git version". If your git verison is displayed your git install was successful.

<!-- no citation, learned from own work-->

### How to make a Github account:
To make a github account, start at the account creation page [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home). At this page you will be prompted to enter an email, a password, and a username. After creating an account, as a student you can then sign up for the student developer pack [here](https://education.github.com/pack) where you will be prompted to verify your school enrollment information.

<!-- no citation, learned from own work-->

### How to make a student Jetbrains (Webstorm) account:
To make a Jetbrains student account, visit the link [here](https://www.jetbrains.com/shop/eform/students). You will then have to make an account using your personal and enrollment information, along with a possiblity of having to upload supporting documents that may take up to 2 weeks to verify. 

<!-- no citation, learned from own work-->

### How to install and activate Webstorm:
After your student jetbrains account is verified, you can download webstorm by using [this link](https://www.jetbrains.com/webstorm/download/) and hitting download. Once complete, you can launch the installer where you will be directed on a step by step process on how to finish the install. After installation, launch webstorm, and you will be prompted with a welcome screen where you can select to register using your jetbrains account. This selection will take you to your web browser to sign in link your account, completing your webstorm install and acivation.

<!-- no citation, learned from own work-->

### How to verify git repo in webstorm:
Webstorm should detect your git install be default. To verify your git is connected to webstorm, open webstorm and enter your settings by pressing Ctrl+Alt+S. From this point move towards your navigation menu on the left and press version control. Under version control, press git. When the git menu is opened, you should see a button titled "Test" at the top of the right hand side that you can press to see your installed git version. If an error a occurs try changing your git install path and trying again, or consult webstorm offical documentation [here](https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html). (https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html)
     <br>
     <br>
     <br>
## Glossary 
* **Branch**: A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
* **Clone**: A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
* **Commit**: A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
* **Fetch**: When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.
* **GIT**: Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
* **Github**: GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
* **Merge**: Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
* **Merge Conflict**: A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
* **Push**: To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
* **Pull**: Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
* **Remote**: This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
* **Repository**: A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

## References used:
https://docs.github.com/en/get-started/quickstart/github-glossary  
https://docs.github.com/en/get-started/quickstart/hello-world  
https://git-scm.com/download/win  
https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html  
