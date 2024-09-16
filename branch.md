// 推送分支
git push origin master
// 从远程获取分支
git checkout -b dev origin/dev
// 将远程分支与当前分支进行绑定
git branch --set-upstream-to=origin/v1.0 v1.0 // 将本地分支与远程分支进行绑定
git branch --set-upstream branch-name origin/branch-name

git branch -d v1.0 //删除本地分支
    
git branch  //展示本地分支列表

git branch -a // 展示所有分支

git branch --set-upstream-to=origin/v1.0 v1.0 // 将本地分支与远程分支进行绑定
git branch --set-upstream branch-name origin/branch-name