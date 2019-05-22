# git
## 流程
- mkdir 文件夹（创建一个文件夹）
- cd 文件夹（切换到文件夹里）
- touch 文件.md（创建一个类型为 md的文件）
- git init（初始化 git仓库）
- git add 文件.md（将文件提交到缓存）
- git commit -m "提交信息"（执行一次提交，-m代表提交信息，windows上用双引号，）
- git log（查看提交日志)
- git log --oneline（查看提交日志的id）
- git branch（查看当前分支情况）
- git branch 分支1（创建一条名为“分支1”的分支）
- git checkout 分支1（切换到分支1）
- git checkout-b 分支2（创建并切换到分支2）
- git merge 分支1（将分支1上的代码合并到主分支master上，注意在执行此命令前先切换到主分支master上）
- git branch -d 分支1（删除分支1，可能会失败）
- git branch -D 分支2（删除分支2，不论分支上的代码有没有和进master上）
- git tag 版本号 提交id（给对应的提交id打上版本号，轻量级标签）
- git tag -a 版本号 -m “标签说明”（提交一个版本号，注释标签）
- git tag （查看标签，默认按照字母排序，不是时间顺序）
- git show 标签名（查看标签信息）
- git tag -d 标签名（删除标签名）
- git push origin <tagname>（推送标签到服务器上）
- git push origin --tags（一次性推送本地尚未推送的本地标签）
  [执行git命令报错时处理](https://blog.csdn.net/niuzhucedenglu/article/details/52255019“WARNING: terminal is not fully functional”)
  [使用Guthrie基本操作](https://www.jianshu.com/p/68b9e463333f"基本操作")
  [github基本操作](https://www.jianshu.com/p/68b9e463333f)
  C:\Documents and Settings\Administrator\.ssh
