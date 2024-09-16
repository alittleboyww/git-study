git reset --hard HEAD^
git reset --hard HEAD

git rebase <branch> 将当前分支变基为branch分支，
git rebase --abort 中断此次变基
git rebase --continue 修改冲突后继续执行变基

git merge <branch> 将branch分支合并到当前分支