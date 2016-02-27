#stash功能：将当前工作现场“储藏”起来，等恢复现场以后继续工作：
git stash     这样当前工作区就是干净的了，可以放心的创建分支先进行其他的工作。
git stash list 查看当前储存起来的工作
git stash pop  直接取出储存的工作并删除stash内容。
git stash apply 需要用git stash drop删除。

#git merge --no-ff -m "merge with no-ff" ‘branchname' 用非Fast forward模式合并，就是创建一个新的commit，所以需要-m描述信息，这样删除这个分支后分支信息不回丢失。
#"git remote add origin git@github.com:one'saccountname/path"添加远程仓库
#git push -u origin master  由于远程库是空的，我们第一次推送master分支时，加上了-u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。
#"git log --graph --pretty=oneline --abbrev-commit"查看commit提交以图像形式。
#entering "git --no-pager log" instead of "git log" to avoid entering page mode.
#creating a new branch is quick and simple.
#Created on my own pc.
#I then add a new line.
#Add GPL.






















