Working with Local Git Repo
---------------------------------------------------------
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

git clean -n //would warn you about the files which is going to be cleaned

git clean -f //would clean the files

files whoch you want to ignore commiting should be added as part of .gitignore file in the roor directory

----------------------------------------------------------
Working with Remote Git Repo
----------------------------------------------------------

git clone https://github.com/jquery/jquery.git

git log --oneline| wc -l
git log --oneline| graph
git shortlog -sne  

git show HEAD~1

git protocols:

https/http - 80/443 - Read-write
git - 9418 - read only Anonymous only
ssh - 22 - read-write SSH keys for auth
file - n/a - read write local only

git remote add origin https://github.com/senth542002/GitFundamentals.git

git fetch; git merge origin/master -----------> git pull

git push

git tag <tag name>

git tag -a <tag_name> -m <message>

git tag -s --sign

git tag -v //(verifies signature)

git push --tags //pushes the tags to the remote repository