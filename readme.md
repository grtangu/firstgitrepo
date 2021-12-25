========================= Git commands ==============
If you want to check/see what are the current git configurations use the below command
git config --list

If you want to override git configurations globally i.e switch the git user use the below 2 commands
git config --global user.name "your_username"
git config --global user.email "your_email_address@example.com"

If you want to know the current branch name use the below command
git branch

Lets assume , you made some changes like add/update any files in the current repository via pointed branch would like to know the changes you made then use the below command
git status

If you want to add/update your changes from local to staging use the below command
The below command for single file
git add "added or updated file name"

if want to add/update all the files then use the below command
git add .

if you want to move the changes from "staging" to "comitted" status then use the below command
git commit -m "comit comment name"

----------------------------- undo changes -------
Before Stage undo the changes in "filename:
git checkout "filename"

After Stage undo the changes in "filename:
git reset head "filename"
git checkout "filename"

If you want to create new branch use the below command, it acutally create new branch from current pointed branch
git branch "branch-name"

If you want to switch from current branch to other branch use the below command
git checkout "branch-name"

If you want to see what are the commits happens recently use the below command
git log

If you want to see the difference between two comitted ids use the below command
git diff "commitid1" "commitid2"

If you want to see the latest top one commit details use the below command
git log --oneline
