
git merge --abort 终止合并

git stash 保存合并中间状态

git stash apply 恢复合并中间状态



**迁移项目**

git remote -v
git remote set-url origin https://****.git
git push --all origin
git push --tags origin 


**合并不同项目 ( 将A项目的master分支提交到B项目的tmp分支)**
git clone https://A.git
git remote add B-repo https://B.git
git push B-repo master:tmp 
