# vcs

- master/main -> default branch 
- origin -> default upstream
- HEAD   -> current branch
- HEAD^  -> parent of HEAD

| Command  	    			 | Info          			  | Example
| -------------------------- | -------------------------- | -------------------------- |
| git help [command]		 | learn git command 		  |
| git init 					 | create an empty git repo   |
| git clone [project_url]	 | copy file from remote url  |
| git status				 | show the working tree status|
| git log 					 | show commit logs 		   |
| git log --merge            | 								|
| git log master..[branch_name] --oneline pipe tail -1 |  find commitid of created branch   |
| git log --first-parent     | branch where come from |
| git blame 				 | show what revision and author last modified each line of a file |
| git show 					 | show various types of objects |
| git rev-parse	[object_name]| return commit id given object_name |
| git diff [old_commit_id new_commit_id] | show changes between commits |
| git diff --ours | |
| git diff --theirs | | 
| git reset HEAD			   | revert uncommitted changes |
| git reset --soft [commit_id] | given commit will be last commit and old files will be keep of your local repo. 
| git reset --hard [commit_id] | given commit will be last commit and old files will not be keep of your local repo. 
| git checkout | switch branches or restore working tree files |
| git checkout -b [branch_name] | current branch will copy with given name |
| git revert   | revert existing commits | 
commit 8f937c683929b08379097828c8a04350b9b8e183
Merge: 8989ee0 7c6b236

git revert commit_id -m 1 -> 8989ee0
git revert commit_id -m 2 -> 7c6b236
|
| git pull | sync remote or local repository |
| git request-pull  | create pull-requests   |
| git fetch |  copy changes tree of remote repo ( not included files) |
| git fetch --all | copy changes tree of remote repo ( not included files) |
| git fetch --prune |  Before fetching, remove any remote-tracking references that no longer exist on the remote.|
| git stash       | save files to temporary LIFO structure |
| git stash --pop | delete files to temporary   LIFO structure|
| git merge       | join two branch |
| git rebase 	  | copy remote file to local and move to top your un-pushed commits. |
| git branch      | show your local branches |
| git branch -r   | show only remote branches |
| git branch -a   | show all branches |
| git branch -M [branch_name] | change main branch of your project | git branch -M main| 
| git add -A 	  | mark all file changes as ready to commit |
| git clone -df   | remove untracked local files|
| git mv [old_file new_file] | replace file,directory
| git rm  [files]	| remove files from  the working directory and from the index|
| git rm  --cached [files] | stop tracking but keep files in working dir. | 
| git commit -a    | create commit and put all changes into in. | 
| git commit --dry-run | dont create commit, only show. | 
| git push         | send all commit to remote repo | 
| git push --set-upstream [remote] [branch] | you choose where you will send your local branch |
| git archive | create release tarball | 
| git bisect  | binary search for defects | 
| git cherry-pick [commit_id] | take single commit from elsewhere|
| git fsck | check tree |
| git gc |   compress metadata for performance| 
| git tag -l | list all tags |
| git tag| list all tags |
| git tag | tagging branch | git tag -a v0.0.1 -m "v0.0.1"  &&  git push --tags |
| git tag -d [tag_name]| delete a local tag | 
| git push --delete origin [tag_name] | delete pushed tag on remote | 
| gitk|
| git remote -v | get remote repo of your project |
| git remote add | change remote repo url|

-
	how to undo pushed file?

	git reset --soft COMMIT_ID
	git restore --staged FILE_NAME
	git restore FILE_NAME

	git add -A
	git commit -m "MESSAGE"
	git push -f 
- 






