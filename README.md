## Learning Github through this repository.
git clone URL [localname] this clones a repo that is created in github.com. Usually we need to provide a name (localname) for the folder that is being created. Not providing one will make the directory have the name of the repo.
git status - to see the current status of the local repo. To check what files are untracked, what are in staged area etc.
git branch -m [branch name] - will change the branch name that you are working on. Need to check how to create a branch. Is it only created in github.com?
git add - to add the newly created files or edits to tell that the file/files belong to this repo and move it to tracked state.
git commit -m [commit message] - will commit the changes to the repo. This doesn't mean that the changes are pushed to the remote repo in github.com.
git diff - will show the changes made or edited, but not yet added or comitted
git add -u .     # updated files in the current directory (and below)
git add -u :/    # updated files in the whole repository

-u is short for --update
