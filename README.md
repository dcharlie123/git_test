# git 基础命令

- `git init` 初始化git仓库
- `git add ./filename` 将**工作区**全部文件/xx文件存入**暂存区**
- `git log` 查看commit历史
- `git commit -m '...'` 将**暂存区**提交到**版本库**中
- `git status` 查看工作区和暂存区的状态
- `git diff` 比较**暂存区**和**工作区**的差别
- `git diff HEAD`比较**工作区**和**版本库**的差别
- `git diff --cached(===staged)`比较**暂存区**和**版本库**的差别
- `git show commit码`查看commit改动
- `git branch 新分支名` 新建分支
- `git checkout 分支名` 切换分支
- `git checkout -b 分支名`新建分支并切换到该新分支
- `git merge` 合并分支
-`git merge --abort`撤销合并
- `git rebase 分支`
## tip：git rebase和git merge的区别

---------- 
- `git clone`克隆远程仓库到本地
- `git remote add origin 'https://github.com/***.git'` 本地仓库与远程仓库相关联
- `git push -u origin master/<branchname>`==`git push --set-upstream origin master/<branch-name>`第一次提交到远程仓库
----------
# 概念：

- **origin**表示远程仓库
- HEAD 指向当前所在的commit
- 
