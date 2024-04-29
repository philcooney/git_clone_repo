# Hello GitHub

#Firstly navigate to the directory you want to clone the repository too
 cd ..

#Then git clone and copy the SSH or HTTPS URL from the remote repo
git clone git@github.com:philcooney/git_clone_repo.git

#Then navigate in to the locally cloned repo
cd /git_clone_repo

#Make changes to the files within
touch md

#Once changed, stage the recent changes
git add md

#Then commit the file 
git commit -m "enter changes"

#Once done, push to remote repository
git push -u origin main
