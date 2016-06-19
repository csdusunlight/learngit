Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.

Creating a new branch is quick and simple.


git reset --hard HEAD^
git reset HEAD file
git checkout -- file
git rm file
git remote add origin https://github.com/csdusunlight/learngit.git
git remote rm origin
git push -u origin master

git clone git@github.com:csdusunlight/gitskills.git
查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
git merge --no-ff -m "merge with no-ff" dev