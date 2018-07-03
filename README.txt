git status // gets the status of the current git repository
git add -u  //adds updated files

git add -A // adds all the files

git commit -m "Message" // comits the files to the repository with a given message

git diff <commit_id>..<commit_id>  //gives the difference between the two version of the files

git diff HEAD~1..HEAD //gives the difference between the last but one commit and the current commit 

git log //gets all the commit made

git checkout <file_name> //fetches the laetst file from the repository

git reset --hard //resets all the code with the version in the repository

git reset --soft HEAD~1 //restes the code to the previous version