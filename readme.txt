git reset --hard HEAD^ 回滚到上个版本
git reset --hard <版本id> 回滚到指定的版本
git reflog 查看每次的操作执行的命令
git add -A 把所有工作区的修改提交到暂存区
git commit -m 'note' 暂存区提交到分支（master）
git diff HEAD readme.txt 查看分支与本地代码的区别
git checkout -- readme.txt 从工作区撤销修改 记得加‘--’
git reset HEAD readme.txt 从暂存区撤销到工作区 
git checkout -b dev 创建dev分支 -b并切换到dev分支
git branch 查看分支
git checkout (分支名) 切换分支
git branch -d (分子名) 删除分支
git merge (分支名) 合并分支