# git-note
Help me remember some useful git commands


* remove file from staging area
`git rm file --cached`

Stashing
* save the current dirty state of working dictionary
`git stash save "msg"`
* get stash list
`git stash list`
* apply stash
`git stash apply id`
* apply the most recent stash
`git stash pop`
* drop stash
`git stash drop id`

* change file name or move file
`git mv file1 file2`, `git mv file dic/`

* add file to the most recent commit
`git commit --amend`

* set commit time
`git commit ... -date="data format"`

* move a file out of staging area
`git reset file`
* undo the last commit, while keep the index
`git reset HEAD~ --soft`

* revoke the modification of a file from last commit
`git checkout file`

* forward-port local commits to the updated upstream head
`git rebase branchname`

* find out motification
`git diff`

* show the author of modification
`git blame filename`

branch
* delete a branch
`git branch -d branchname`

merge
* get the changes without merging them with the local repository
`git fetch origin`




