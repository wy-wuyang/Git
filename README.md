# Git
## git 基本命令
```
<pre>
|- git init  初始化一个仓库
|- git status  查看当前某些文件的状态
|- git add  跟踪文件
|   |-- git add . 跟踪全部
|   |-- git add <具体文件> 跟踪某个具体的
|- git commit -m 'name'   存一个历史版本
|- git log  查看历史提交记录

|- git remote -v  查看当前仓库绑定的远程仓库

|- git branch 查看本地存在的分支 
   git branch <分支名>  创建新分支
   git branch -d <分支名> 删除某个分支

|- git checkout <分支名> 切换分支
|- git checkout -b <分支名> 创建新分支并切换到新分支上

|- git tag  查看当前已有的tag标签
| |-git tag <标签名>  创建本地tag
| |-git push origin <标签名>  推送到远程仓库
| |-git show <标签名> 查看某个标签详细信息

|-git tag -d <tagName>  删除本地标签
|-git tag -l | xargs git tag -d  删除本地所有标签
|-git push origin :refs/tags/<tagName>  删除远程标签

</pre>
```