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

###### before switching branches make sure the branch is clear working tree is clean

###### git checkout develop will switch to this develop branch

###### do your work run git add . and git commit -m "" and then git push origin develop

###### now the master branch is one commit behind

##### any files or work made on the develop branch wont be on the master branch yet

##### git checkout feature1 will switch to the feature1 branch
