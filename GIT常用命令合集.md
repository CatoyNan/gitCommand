# GIT常用命令合集

## 一、常用指令合集



| 功能                                           | 指令                       |
| :--------------------------------------------- | -------------------------- |
| 新建仓库                                       | git init                   |
| 添加文件到暂存区                               | git add  文件名            |
| 将文件从暂存区提交到仓库                       | git commit -m '提交的注释' |
| 显示工作目录和暂存区的状态                     | git status                 |
| 比较工作区和暂存区的内容                       | git diff 文件名            |
| 查看历史版本                                   | git log                    |
| 查看历史版本（一行显示）                       | git log --pretty=oneline   |
| 回退版本号（**回退前记得commit暂存区的文件**） | git reset --hard 版本号    |
| 查看引用日志                                   | git reflog                 |
| 撤销工作区文件的修改                           | git checkout   --   file-name |
| 撤销已经提交到暂存区中的修改                   | git reset  HEAD  file-name |
| 添加一个远程git仓库                            | git remote add  remote-name(远程主机名)  url |
| 将代码推送到git仓库                            | git push remote-name  branch-name(本地分支名) :remote-branch-name(远程分支名) |
| 创建一个分支                                   | git branch name            |
| 删除一个分支                                   | git branch -d name         |
| 切换分支                                       | git checkout name          |
| 创建并切换到该分支                             | git checkout -b name       |
| 将某分支合并到当前分支                         | git merge name             |
| pull远程git仓库的文件 | git pull <远程主机名> <远程分支名>:<本地分支名> |
| 在本地仓库删除文件 | git rm 我的文件 |
| 在本地仓库 删除目录 | git rm -r 我的文件夹 |
| 将本地分支关联远程从库的某个分支 | git branch --set-upstream-to=origin/远程分支名  本地分支名 |
| 查看本地分支与远程分支的追踪关系 | git branch -vv |



####  git reset 三个参数

![lADPDh0cQOo3QJrNEPXNEjQ_4660_4341](asserts/lADPDh0cQOo3QJrNEPXNEjQ_4660_4341.jpg)

 

 





## 二、附录：

### 1、log详细选项

![log相关指令](GIT常用命令合集.assets/log.jpg)