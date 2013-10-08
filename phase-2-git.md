##Phase 2 Git Workflow
### Creating a team repository in the github phase 2 organization
* 


### Working on an existing repository
* Clone the repository to your local machine.  If you have already cloned, then use   
`git pull origin master`  
 to make sure you have the most current master. 
* Make a **SMALL** change.
* Add the files to your git staging  
 `git add file-name`
* Commit your changes.  
 `git commit -v `  
 **Note:** the `-v` is for verbose which opens a diff file in your default editor where you can view your changes. To setup sublime as your default editor,  Add the following to your `.gitconfig` file:  
    `[core]`  
    `editor = subl -w`  
    `excludesfile = ~/.gitignore_global`
  * Add your [descriptive commit message]() to the top of the diff file and save it.
  * Commit **early and often**
  * When you have finished your branch, you need to merge master into it locally to make sure you have no merge conflicts, push the branch to github and submit a **pull request** on github.  
  `git merge master`  
  `git push origin my-branch`


###Spiking
* Make a branch:   
  `git co -b spike-question`  
  where **question** is your current question like _heroku-and-sinatra_
* Throw out the branch - it was a spike, DON'T merge it.  

###Things that should be in all code before submitting a pull request:
* Has tests
* Working code
* Clean code
