#Create Git Repository
#git init
#Add Name and email into git
#git config --global user.name 'Wahib Naseem'
#git config --global user.email 'wahib1900@gmail.com'
#To check the status
#git status
#To unstage the file 
#git rm --cached filename
#To add the specific files whose extentsion are same
#git add *.html   --> it will add .html files 
#To  add all the files
#git add .
#To commit there are various ways
#git commit , 
#press (i) for insert
#give the commit name 
#press esc key to come out from intsert mode
#the type :wq to commit 

#To commit we can do this way 
# git commit -m "message for the git"
#we can have .gitignore file  in this file we simply name those file and folder(/folder) which we don't want to commit
# and *.txt file it will ignore all files whose extension is txt

#we can also create the branch
#git branch login 
#To Change the branch 
# git checkout nameofthebranch
#To merge with branch i mean into the master branch first we need to checkout master branch
#git checkout master  ..... then merge
#git merge nameofbranch