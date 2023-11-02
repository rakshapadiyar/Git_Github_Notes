# Git_Github_Notes


--------------- local implementation -----------------------
1) git init   
 after cd into the folder that contains the project   


2) git status   
 Shows untracked files in red insidide working directory.
 Shows tracked files/ files in staging area in green.   

3) git add <file_name>   
 Adds the file to the staging area i.e. the file is being tracked.   

 git add *    
 adds all the files/folders into the staging area   

4) git commit -m "Commit message"   
 Creates a (last working) save point.   

5) git log   
 All versions, author, date   

6) git checkout < file_name >   
 revert to last working version   

----------------------- remote implementation ----------------------   

1) git remote add origin <repo_url_from_github>   
Associates a remote repository at the url with the local repository. (can be done via ssh too. but, https is recommended_)
'Origin' is the alias that we assign to the url.

if origin of prev remote exists,   
git remote remove origin

2) git push -u origin master   
pushes local repo to remote repo   

here remote repi -> origin
branch of local repo that we wish to upload -> master

remote repo = origin   
branch =master ( default/main branch)   





-------------------------------------------------   
…or create a new repository on the command line   
echo "# js1" >> README.md   
git init   
git add README.md   
git commit -m "first commit"   
git branch -M main   
git remote add origin https://github.com/rakshapadiyar/js1.git   
git push -u origin main   
…or push an existing repository from the command line   
git remote add origin https://github.com/rakshapadiyar/js1.git   
git branch -M main   
git push -u origin main   
