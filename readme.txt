Git is a version control system.
Git is free software.+modified

git config --global user.name 'name'
git config --global user.email 'email@e.com'
mddir learngit
cd learngit
pwd
git init
git add readme.txt
git commit -m 'wrote a readme.txt'
git status
git diff readme.txt
git log
git log --pretty=oneline
git reset --hard head^
git log
git reset --hard 196198(log id前几位)
git commit -m ''	#-m''，空格不会添加到log记录中？
cat readme.txt
git log
git reflog
 change1
 change2
git diff head -- readme.txt	#-- 后带空格





