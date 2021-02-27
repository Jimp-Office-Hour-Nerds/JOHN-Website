# JOHN-Website

$ git clone https://github.com/Jimp-Office-Hour-Nerds/JOHN-Website.git

Create a new branch
$ git checkout -b [name_of_your_new_branch]

Push the branch on github :
$ git push origin [name_of_your_new_branch]

When you want to commit something in your branch, be sure to be in your branch.

You can see all branches created by using :

$ git branch

Which will show :

approval_messages master master_clean Add a new remote for your branch :
$ git remote add [name_of_your_remote]

Push changes from your commit into your branch :

$ git push origin [name_of_your_remote]

Update your branch when the original branch from official repository has been updated :

$ git fetch [name_of_your_remote]

Then you need to apply to merge changes, if your branch is derivated from develop you need to do :

$ git merge [name_of_your_remote]/develop

Delete a branch on your local filesystem :

$ git branch -d [name_of_your_new_branch]

To force the deletion of local branch on your filesystem :

$ git branch -D [name_of_your_new_branch]

Delete the branch on github :

$ git push origin :[name_of_your_new_branch]
