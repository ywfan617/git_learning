# git_learning

## 建立与检出分支

`git branch branch-name ------创建分支`  
`git checkout -b branch-name ------创建分支并检出出分支`  
`git branch ------查看本地分支`  
`git branch -a ------查看所有分支`  
`git checkout branch-name ------检出分支`  
`git merge branch-name------合并分支`  
`git branch -d branch-name ------删除分支`  
`git branch -v ------查看每一个分支的最后一次提交`  
`git branch --merged ------查看呢一个分支已经合并到当前分支`  
`git branch --no-merged ------查看所有包含未合并的分支`
## 查看提交日志

`git log ------查看日志`  
`git log --decorate --oneline ------查看各个分支的指向对象`  
`git log --decorate --oneline --graph --all ------查看分叉历史，输出提交历史，各个分支的指向以及项目的分叉情况`

## 回退版本  

`git reset --hard HEAD^ ------回退到上一个版本`  
`git reset --hard HEAD^^ ------回退到上两个版本`  
`git reset --hard HEAD～6 ------回退到上6个版本`  
`git reset --hard commit_id ------回退到某一提交`  

## 远程命令

`git remote ------列出你指定的每一个远程服务器的简写`  
`git remote v ------显示需要读写的远程仓库使用的Git保存的简写和对应的URL`  
`git branch -r ------查看远程仓库分支`  
`git clone [-o remote-name] <url> ------克隆分支`  
`git remote add <shortnam> <url> ------添加一个新的远程仓库到当前项目`  
`git fetch remote-name ------从服务器抓取本地没有的数据，并且更新本地数据库，不会合并` 
`git pull ` 
`git push [remote-name] [branch-name] ------推送到远程仓库`  
`git remote show [remote-name] ------查看远程仓库的信息`  
`git remote rename new-remote-name old-remote-name ------远程仓库的重命名`  
`git remote rm remote-name/branch-name------移除远程仓库`  
`git checkout --track remote-name/branch-name ------创建远程跟踪分支的本地跟踪分支`  
`git checkout -b branch-name remote-name/branch-name ------创建远程跟踪分支的本地跟踪分支`  
`git branch -vv ------查看设置的所有本地跟踪分支，会列出所有的本地分支并且包含更多的信息`  
`git push remote-name --delete branch-name ------删除远程服务器上的分支`  
