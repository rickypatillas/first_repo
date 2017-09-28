# This is our first repo

### Git is quite useful for version control and collaboration

#### The common workflow wiht git is:
*git init -> to create a enw local repository
* crate and/or modify file
* git add -> to stage them to your local git repositroy
* git add <files>  -> to stage them to your local git repository
* gti commit -m -> to commit your changes to your local repository
*create a reposiroty on Github if one doe snot exist
* git remote add <repo_name> <repo_url>
* git push -u origin master


### To create a branch
* from teh amster branch use "git branch <new_branch_name>"
* git checkout <new_branch_name> 
*EASIER METHOD  is to "git checkout -b <new_branch_name>" which creates the branch adn checks it out at the same time
* to push a branch to remote repo, "git push <remote> <branch_name>"     (remote stadns for origin, ricky, megan, etc)
*ie, git push ryan ryan_branch_1


#### To Merge a branch back onto the master:
*when you're done workng on your feature branch
*git check out master
*git merge <your_feature_branch_name>
*there will be a merge comment page that you'll have to save
*git push origin master (will psuh your merged changed to the master)


#### To add a scond remote repo:
* git remote add <name> <url>
* ie, git remote add ryan https:// github.com/ryandesmond/my_repo
* to push to second remote, "git push ?remote_name> <branch_name>"
* ie, git push ryan ryan_branch_1
