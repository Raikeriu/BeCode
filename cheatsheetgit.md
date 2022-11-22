# **Git Cheatsheet**

## Configure

#### Sets the name you want attached to your commit
````
git config --global user.name name
````

#### Sets the email you want attached to your commit
````
git config --global user.email email@email.com
````

## Repositories

#### Turn an existing directory into a git repository
````
git init
````

#### Clone/download a repository from Github with all the files, branches and commits
````
git clone
````

## Branches

#### Creates a new branch
````
git branch branchName
````

#### Switches to the specified branch and updates the working directory
````
git checkout BranchName
````

#### Combines the specified branch's history into the current branch
````
git merge branch
````

#### Deletes the specified branch
````
git branch -d BranchName
````

## Sync changes

#### Download all history from the remote tracking branches
````
git fetch
````

#### Combines remote tracking branch into current local branch
````
git merge
````

#### Uploads all local branch commits to Github
````
git push
````

#### Updates your current local working branch with all new commits from the corresponding remote branch on GitHub. It's a combination of git fetch and git merge
````
git pull
````

## Makes changes

#### Lists version history for the current branch
````
git log
````

#### Lists version history for a file, including renames
````
git log --follow "file"
````

#### Shows content differences between two branches
````
git diff 1branch...2branch
````

#### Show the status of the repository if any changes has been made
````
git status
````

#### Add a change in the working directory to the staging area
````
git add
````

#### Add all changes in the working directory to the staging area
````
git add -A
````

#### Put a commit(a checkpoint) with a message
````
git commit -m
````

#### Puts a tag on the directory
````
git tag TagName
````

#### Push a tag on github
````
git push --tag
````
