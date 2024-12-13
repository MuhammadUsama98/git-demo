# Git demo

So what is Git?
================
Git is a free and open source distributed version control system.It is responsible for everything GitHub
related that happens locally on your computer. It helps to track the history of your project.
If you are new to Git then this is the guide for you.

### Installing Git
You can download Git from the official website: https://git-scm.com/downloads

### Version
To check the version of your Git:
*   `git --version`: This will give you the version of your Git.
*   `git --help`: This will give you the help menu of your Git.
### SETUP
Configuring user information used across all local repositories
*   `git config --global user.name "Your Name"`: This will setup your user name.
*   `git config --global user.email "your_email@example.com"`: This will setup your email.
  
**To check credentials are set:**

* `git config --global user.name`: This will give you the user name you have entered earlier.
        OR
*   `git config --list`: This lists the configurations for the current repository, including username and email.
*   `git config --global color.ui auto`: Set automatic command line coloring for Git for easy reviewing.

### Initialize Git repository
To initialize a Git repository in your current directory:
*   `git init`: This command will initialize a git repository.
*   `ls -a`: This will show all the files including .git.
*   `git clone [url]`: retrieve an entire repository from a hosted location via URL.
*   `git clone [url] [directory name]`: clone a repository into a new directory

### Stage and Snapshot
Working with snapshots and the Git staging area.
*   `git status`: This will show the status of your repository. Show modified files in working directory, staged for your next commit.
*   `git add [file]`: Add a file as it looks now to your next commit (stage).
*   `git add .`: Add all files in the current directory to the next commit (stage).
*   `git add -A`: Add all files in the current directory and subdirectories to the next.
*   `git diff`: diff of what is changed but not staged.
*   `git commit -m “[descriptive message]”`: Commit your staged content as a new commit snapshot.

### BRANCH & MERGE
Isolating work in branches, changing context, and integrating changes.
*   `git branch`: list your branches. a * will appear next to the currently active branch.
*   `git branch branch name`: This will create new branch.
*   `git branch -M branch name`: This command will rename the branch.
*   `git branch -d branch name`: This command will delete the branch.
*   `git checkout branch name`: This command is use to switch branch.
*   `git checkout -b branch name`: This command is use to create a new branch and switch.
*   