1. we can check the stages of the files like commeted, modified, untracked, etc. by = git status -s/s

# this gives the result only if the file is not commited and modified after commited //

2. we can check and go to back by the AND SEE THE ALL COMMITED FILES = git log --oneline / --graph(branching)

<!-- BRANCHING -->

main branch and the copy of the branch (check = git branch)
make another branch = git branch feature/navbar
to go to another branch = git switch feature/navbar

to mearge branch we have to have in MAIN BRANCH = git merge feature/navbar

if there is the different text in the same line of different features then the conflict happens - either add first branches text or second or add both

<!-- MERGING TECHNIQUE -->

1. fast forward merging technique
2. three way merging technique

1.three way merge => when we have the another branch of the main after chenge and we also wrote the code in the main branch then we take the main branch and changed main branch and the feature branch

2. fast forward => we give the copy of the main branch and make changes in to it, and the point the head to changed feature branch we do not need to marge

<!-- HOW TO DELETE BRANCH -->

git branch -d feature/navbar (name of branch)

<!-- stash -->

if you created a branch and wrote some code in it and try to switch without commit , then the the branchs change will get deleted to prevent this , we do draft then the changes will not deleted nor commited

<!-- to go to that branch and create it for one line command -->

git switch -c feature/addpage

by doing git stash the changes will record the git -> after switching to the next branch , and back to the same branch then -> do [git stash apply]

<!-- steps to colobrate -->

1. main human -> 1. setup the files and folder 2.upload on github 3. add collarabator

2. everyoe wiill clone that project, -> create their own branch -> write code in that branch -> after completing commit and then push -> inform the teammate -> then main human will check the code and then merge it and re-push
