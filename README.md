# git-source 

github basic commands

to install git in a folder on your computer

create a folder and target the folder using cd command in terminal
 
 once you have done the process starts

 git init | if you want to branch main(default is master) | git init -b main
 git status

 to commit

git add filename.type
git log
git commit -m "message"
git commit -a -m "message"  <!--to add and commit in one command , only do it when file is edited not created or rename new on -->
git diff <!-- to show the changes from now to previous commit>
git diff -- staged <!-- to show diff btw previous and new file>
git add . <!-- to add all >
git rm -- cached file_name <!--to delete file from git>

remote repository 
<!-- github -->
git clone link-add
https -- as pass each and every time
ssh -- as at once
mkdir file_name
cd file_name
echo "#git-source demo">>README.md
cat README.md
<!-- to see the file -->
git init
git status
git add README.md
git commit -m "message"
git branch -M MAIN
ssh-keygen- o
cd id-rsa.pub
git push -u origin main
user:
pass:
git tag-a v01 -m "message"
git show v
git push origin v
git switch -c origin
git branch
git log
git branch -d branch_name
<!-- to delete the branch -->
git switch branchname
git push origin branch_name
git pull origin branchname
<!-- to get all files in remote repo -->
git merge orginname
