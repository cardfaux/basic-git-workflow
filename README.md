## This Repository Is To Help With A Git Workflow

#### To Tag A Release As A Production Release

##### git tag -a v1.0 -m "added first tag" will tag the most recent commit, git show v1.0 will show this tag, git tag will show the tag by version

###### git push --tags origin master will push it to the repository

##### To Create Different Branches Like Master, Development, Feature, ect.....

##### git branch develop will create a branch called develop

##### git log will print a whole log of everything

##### git log --oneline --decorate --graph --all will print a line for each commit decorate it and graph it all branches

###### in the print out you will have commit message on the right, commit hash on the left

###### git branch will show all your branches, with the branch you are on highlighted

# <<<<<<< HEAD

###### before switching branches make sure the branch is clear working tree is clean

###### git checkout develop will switch to this develop branch

###### do your work run git add . and git commit -m "" and then git push origin develop

###### now the master branch is one commit behind

##### any files or work made on the develop branch wont be on the master branch yet

##### git checkout feature1 will switch to the feature1 branch

##### Two Different Commits on 2 different branches can have 2 different snap shots of code.

###### if we want the feature1 branch to merge into the develop branch as long as the files to conflict they can merge easily

###### run git checkout develop, then git merge feature1

###### After feature1 branch is merged we need to delete it with git branch -d feature1

##### after merging files from feature1 to develop, merge from develop to master

> > > > > > > develop

###### switch to the master branch and run git merge develop

###### tag the most recent commit on the master branch git tag -a v1.1 -m "added second release tag"
