# github-demo
Learner demo  
by shreyas
setup github acc. create a repo and commit in github. assign the email id of github and username in the locAal git bash
git config --global user.name "hshshs"
git config --global user.email "hshshs@gmail.com"
git config --list ,lists the mail and username
ls - list of directories insiide
ls -a . shows the hidden files
git status . status of the current folder
github directly commit 
git(loaclly) add and commit
git clone Repo_link
git status (display the status of the changes)
4 kinds of status untracked ,modified,unmodified,staged=ready to be comitted
add and commit command
git add filename . each file that u change that u need to add
git add . (add all the modified files)
git commit -m "message"
git push origin main (push local repo to github) origin-> name of the repo that we cloned, we kept it as origin. and the main branch
git init (used for initializing git inside a folder)

git remote add origin link (copies the repo that is of the link) this is for copying the newly created repo (ie connecting the remote to the local 
where in local i have contents to upload) into local machine.  
storyline is- we have made a repo inside local machine and need to push to remote. now we creatre a repo in remote , add it to local by the 
above command . this repo is now set as origin
git remote -v (verify the remote thst has been added)
git branch . see the name of the branch.
git branch -M main (main is the name of the new branch can be anything else)(we need to go to main branch. when git branch if the name is other than main then this becomes useful)used for rename
add and commit
now do git push origin main to push the locally created new repo to remote repo
git push -u origin main (for a long time it considers the origin main and pushes to origin main itself when u put the command git push)
git push
note :better to create repos in remote first and then clone in local
git checkout branch_name (navigate to a different branch)
git checkout -b new_branch_name (navigate/create to a new branch)checkout- leave from one place.
git checkout -d branch_name(delete a branch)