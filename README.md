# hello-git
First bash git test

This readme shall be pulled via the command line, muhaha

1. use 'git add *.*' to add files to the staging area
2. use 'git commit -m "commit message"' to commit the staged files
3. use 'git push' to add the committed files to the github.com repository
4. use 'git pull origin master' to collect the latest version of the repository.
5. use 'git diff' to check for changes between your changed (uncommitted) files & latest version.
	a. First make a change. This will show up with 'git diff'.
	b. Secondly add the files to staging area. This will show up with ' git diff HEAD'
	c. Third commit the files. Now you cannot see changes anymore with 'git diff HEAD' since you are uptodate.
	d. use 'git diff --staged' to see your latest staged diff.
6. use 'git reset *.*' to unstage files
7. undo all changes and revert back to latest commit with 'git checkout -- file.txt'
8. create a new branch with 'git branch branch_name'