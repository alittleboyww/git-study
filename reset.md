git reset --hard HEAD^
git reset --hard HEAD

git checkout -b v1.0
git branch -a // 展示所有分支
git branch --set-upstream-to=origin/v1.0 v1.0 // 将本地分支与远程分支进行绑定
