# git
## Git Cheat Sheet

| Git Commands | Descriptions | 
| --- | --- | 
| $ **`git config --global user.name "*idrees*"`** | Before you get started you should set your name. |
| $ **`git config --global user.email "example@email.com"`** | Setting you email. | 
| $ **`git config --global color.ui auto`** | enabling coloring to pretty up command output. | 
| $ **`git init`** | init stands for **initialize**. It initializes a git repository to track changes. It creates a hidden folder with the name ".git" |
| $ **`ls`** | It shows the list of files in the current folder. | 
| $ **`ls -la`** |  | 
| $ **`git add -A`** | |
| $ **`git commit -m "initial commit"`** | | 
| $**`git clone https://github.com/idreesishaq/Books`** | To start working with an existing project and you are given a URL to the project's remote repository on a server. No matte what format the URL is, just pour it into the `git clone` command. URL can take many forms: <br>`ssh://user@server/git-repo.git` <br>`user@server:git-repo.git` <br>`http://example.com/git-repo.git` <br>`https://example.com/git-repo.git` <br>`git://example.com/git-repo.git` |
| $**`git status`** | We use `git status` to simply check out changes that we have made from the last commit. |
| $**`git add index.html`**  | Before we commit any changes to be tracked by git, we add the file. It is called **staging** |
| $**`git add --all`** | This command is used for staging more than one file. Simply it stages all the tracked and untracked, modified files. The shorthand command for `git add --all` is `git add -A` |
| $**`git rm error.html`** | By this command `git add --all` we add all the files in the staging area for commiting. what we have to do if we want all the files to be stages except *error.html* or any other file. In that case we simply remove that file to be staged by `git rm` command means **removal** preceding file name that we want to remove from staging.  |
| $**`git log`** | `git log` command is used to display all the commit's history of a project. It show the metadata about every commit, like <br> * Hash value <br> * Author <br> * Date <br> * commited message.|
| $**`git log -p`** | the flag "-p" following by `git log` command is used to display the detailed changes that happened in each commit. |
| $**`git branch contact-form`** | Branching is one of the most powerful feature of git. To create new branch we simply use the `git branch` command preceded by the branch name. for example in this case `git branch contact-form`. here we create a new branch of name "contact-form". |
| $**`git branch`** | `git branch` commands list all the branches. |
| $**`git branch -v`** | the "-v" flag provides us with a little more information than usual along listing branches. |
| $**`git stash`** | We do not use staging and commiting for temporary file saving or any half-done work. For these temporarily changes git has an special feature `git stash`. |
| $**`git stash list`** | To get overview at any stage of our current Stashes, the `git stash list ` command is used. |
| $**``** |  |
| $**``** |  |
|  |  |
|  |  |
|  |  |
|  |  |
|  |  |
