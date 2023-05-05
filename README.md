# git
## Git Cheat Sheet

| Git Commands | Descriptions | 
| --- | --- | 
| $ **`git config --global user.name "*idrees*"`** | Before you get started you should set your name. |
| $ **`git config --global user.email "example@email.com"`** | Setting you email. | 
| $ **`git config --global color.ui auto`** | enabling coloring to pretty up command output. | 
| $ **`git init`** | init stands for **initialize**. It initializes a git repository to track changes. It creates a hidden folder with the name ".git" |
| $ **`ls`** | It shows the list of files in the current folder. | 
| $ **`ls -la`** | `ls` command in git lists the files in the current repository and by the flag **-a** and **-la** following the the `ls` command lists the all content of the current repository including any hidden files.| 
| $ **`git add -A`** | `git add -A` is a short hand form for the command `git add --all` which is used for staging all the files before to be commited.  |
| $ **`git commit -m "initial commit"`** | By the `git commit` command we record changes (as version controlling) also giving a meaningful messages which is a discription about changes. whoever read the message any time future will understand about the changes or works.  | 
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
| $**`git checkout master`** | We switch anytime form one brach to another branch. We are working now at branch **contact-form**. Now want to switch to out main **master** branch. So, we have a git command `git checkout` and then name the branch-name into which you want to go.  |
| $**`git merge contact-form`** | Now We have switched to our main **master** branch. we wanna merge our work done in **contact-form** branch into **master** branch. We have a command for this task `git merge contact-form`. |
| $**`git remote add URL`** | By this command we can add a github repository to pull and push remotely. We simply write the command `git remote add` succeeded by the URL name (by naming convention it is **origin** but you can set any name, and the enter url. for example <br> `$ git remote add origin https://github.com/idreesishaq/git.git` |
| $**`git remote -v`** | By this `git remote -v` command we can check the list of repository's url, that we have been add by the command `git remote add URL` for the puspose of pushing and pulling remotely. |
| $**`git branch -va`** |  |
| $**`git fetch <repository name> From <URL>`** |  |
| $**`git push`** | The upload our all commit history from a project or sub project, form a local repository, We use `git push`. <br> The command `git push` requires two thing, one is the "the remote repostiory's url name" that we already have been set, and the second the "branch name" (master branch). <br> for example: ``` git push origin master ```|
| $**`git fetch origin`** |  |
| $**`git log origin/master`** |  |
| $**`git pull`** |  |
| $**`git push -u origin contact-form`** |  |
| $**`git branch -vva`** |  |
| $**`git branch -d contact-form`** |  |
| $**`git branch -dr origin/contact-form`** |  |
| $**`git commit --amend -m "This is the correct message"`** |  |
| $**`git checkout HEAD`** |  |
| $**`git reset  c7770d2`** | Here c7770d2 is the seven digit hash value of one of my commit, and By this code we want the repository at that particulary point back. |
| $**`git reset --hard HEAD`** |  |
| $**`git revert 2b504be`** |  |
| $**`git reset --hard 2be18d9`** |  |
| $**`git diff`** |  |
| $**`git submodule add URL`** | git submodule add https://github.com/djyde/ToProgress |
| $**`git log --oneline`** |  |
| $**`git log --oneline --decorate`** |  |
| $**`git submodule status`** |  |
| $**`git pull`** |  |
| $**`git submodule status`** |  |
| $**`git fetch`** |  |
| $**`git pull origin master`** |  |
| $**`git flow init`** |  |

