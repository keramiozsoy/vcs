# vcs

master/main -> default branch 
origin -> default upstream
HEAD   -> current branch
HEAD^  -> parent of HEAD
HEAD-

| Command  	    			 | Info          			  |
| -------------------------- | -------------------------- |
| git help [command]		 | learn git command 		  |
| git init 					 | create an empty git repo   |
| git clone [project_url]	 | copy file from remote url  |
| git status				 | show the working tree status|
| git log 					 | show commit logs 		   |
| git blame 				 | show what revision and author last modified each line of a file |
| git show 					 | show various types of objects |
| git rev-parse	[object_name]| return commit id given object_name |
| git diff [old_commit_id new_commit_id] | show changes between commits |
| git reset HEAD			   | revert uncommitted changes |
| git reset --soft [commit_id] | given commit will be last commit and old files will be keep of your local repo. 
| git reset --hard [commit_id] | given commit will be last commit and old files will not be keep of your local repo. 
| git checkout | switch branches or restore working tree files |
| git revert   | revert existing commits |
| git pull | sync remote or local repository |
| git request-pull  | create pull-requests   |
| git fetch |  copy changes tree of remote repo ( not included files) |
| git fetch --all |  copy changes tree of remote repo ( not included files) |
| git merge       |  join two branch |
| git branch      | show your local branches |
| git branch -r   | show only remote branches |
| git branch -a   | show all branches |
| git commit -a    | create commit and put all changes into in.   |
| git commit --dry-run | dont create commit, only show. |
| git push         | send all commit to remote repo |

