git reset --hard HEAD^
git reset --hard HEAD

git rebase <branch> 将当前分支变基为branch分支，
git rebase --abort 中断此次变基
git rebase --continue 修改冲突后继续执行变基

git merge <branch> 将branch分支合并到当前分支
git checkout -b v1.0
git branch -a // 展示所有分支
git branch --set-upstream-to=origin/v1.0 v1.0 // 将本地分支与远程分支进行绑定
