# Collaborative-Repository
Repository for the new story.

# The next lines will contain a report with the commands used by each group member.

## Carlos Colmenero Gómez-Cambronero (Collaborator 1 - Leader)
* First of all, I created a repository using the web application, with the README file included.
* (Note that the username and email was already configured in my machine with: 'git config --global').
* 'git clone https://github.com/colme99/Collaborative-Repository.git' : to clone the repository to my local machine.
* Create "new story.txt" (the group story file) and edit the file with the same text as shown in the practice.
* 'git status' : to check the changes.
* 'git add new story.txt' : to add the group story file that was created.
* 'git commit -m "First commit"'.
* 'git push origin main' : to push the file in the main repository.
(Note that the combination of the push related commands ('git status' + 'git add' + 'git commit -m' + 'git push origin') will be summarized the following times.
* 'git checkout -b carlos_colmenero_gomez' : to create a the new branch and change to that branch (my personal branch, which corresponds to collaborator 1).
* Create colaborator001_sory.txt file (empty).
* Push the file ('git status' + 'git add colaborator001_story.txt' + 'git commit -m "Create colaborator001_story.txt"' + 'git push origin carlos_colmenero_gomez').
* Edit collaborator001_sory.txt file with personal information (some things I did that day).
* Push the edited file ('git status' + 'git add colaborator001_story.txt' + 'git commit -m "Added collaborator 001 today's activity"' + 'git push origin carlos_colmenero_gomez').
* (Note that a git pull command could have been used at this point to check for changes in the group file, but was not used in order to strictly follow the steps).
* Add my personal story (collaborator 1 story) to the group file (new story.txt) in my personal branch.
* Push the edited group file ('git status' + 'git add "new story.txt"' + 'git commit -m "Collaborator 1 story added to new story"' + 'git push origin carlos_colmenero_gomez').
* Make a pull request to the main branch using the web application.
* Resolve the conflicts (just so as not to override the collaborator 2 story), also in the web application. It was just solved with the enter key. It could also be done with the 'git diff' command (just to check the file which is changed) + editing the file.
* Merge the main branch and my personal branch (carlos_colmenero_gomez), also in the web application. It could also be done with 'git checkout main' + 'git merge carlos_colmenero_gomez'.
* Edit the README file in the main branch in order to indicate the commands, also in the web application.
* Create the 'authors.txt' file with the collaborator names.

## Iria Pérez Varela (Collaborator 2)
* 'git clone' + HTTPS link : it was used to clone the repository. Because of this, adding the username and PAT was also required.
* 'git config user.name' + username : this was required to be able to commit changes to the different repository branches.
* 'git checkout iria_perez_varela' : used to ensure that the changes commited will be performed on the correct collaborator branch. The branch is not created in this command because it was already created using the webpage.
* The file 'collaborator_002 story' was created using the local files and the information was filled.
* 'git status' : to see the modified files.
* 'git add .' : to consider the changes in all files on future commits.
* 'git commit -m "Added today's activity"' : to commit the creation and changes done on the collaborator story specific file.
* 'git push origin iria_perez_varela' : to upload these changes to the remote repository.
* The general file was modified as indicated on the document followed in the local files on the VM.
* 'git status' : to see the modified files again.
* 'git add .' : to consider the changes in all files on future commits again.
* 'git commit -m "Collaborator 2 info added to new story"' : to create a commit with the modifications on the general file and a brief description.
* 'git push origin iria_perez_varela' : to upload these changes.
* Then, the readme file was also modified locally to include the commands used during the task.
* 'git add .' : to consider the changes in all files on future commits again.
* 'git commit -m "Iria Pérez command history added to readme file"' : to store the command history.
* 'git push origin iria_perez_varela' : to upload readme changes.
* The readme file was later modified on the webpage to change some minor errors and format characteristics. Also, other local changes were added to include history from following commands but the process was the same as shown before.
* 'git checkout main' : to merge from there.
* 'git merge iria_perez_varela' : to add collaborator changes into common main branch.

## Sergio Rodríguez Llana (Collaborator 3)

* **git clone + repository link** To make a local copy of the contents of the repository.
* **git log** To see the commit logs in the terminal in order to see the activity/history of the repository.
* **git checkout sergio_rodriguez_llana** To switch between the 'main' branch to my collaborator branch one in my working directory. This was done to commit changes to my colaborator branch intead of the 'main' one.
* **git pull** To update my working directory with new changes from the remote repository.
* **git status** To keep track of the modified files of my working directory.
* **git branch** To ensure my colaborator branch was active before commiting any changes.
* **git add** To add a created or modified file to the next commit. For example, I used this when I modified my colaborator story using the terminal.
* **git rm** To remove a file from the repository in the next commit (I did this to delete a file I introduced by mistake).
* **git commit -m 'comment'**: To commit the changes done localy and add an explanatory comment.
* **git push** To submit the new changes and update the remote repository with my local changes.
* **git checkout main** with **git merge sergio_rodriguez_llana** to update the 'main' branch with my colaborator branch changes. 
* I edited the README file using the web application.
* **Note**: some of the commands like *git commit -m* or *git pull* were done several times during this Lab.

