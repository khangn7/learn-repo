# made from my laptop

for learning

## steps to make local git repo:

1. create folder

2. point cmd to folder

3. git init
-next cmd directory should have (master) or whatever next to it
-can use ls -la in cmd to check for .git file in folder

then to connect to remote repository on github:

1. go on github and create new repo

2. get link and do "git remote add origin (github link)"

3. push local files with "git push origin master"

to set default push destination do "git push --set-upstream orgin master"

## steps to create branch

1. point cmd to folder

2. do "git checkout -b (branch name)" to create branch
-usualy branch name specifies "feature" or "fix" and then "-file-details"
-ex. "git checkout -b feature-readme-steps"

3. to get list of branches, do "git branch", asterisk indicates what branch your on
-to switch between branches, do "git checkout (branchname)"

4. to create the branch on github, after doing "git add" and "commit", do
-"git push -set--upstream origin (branchname)"

5. it's conventional to merge on github with a pull request

