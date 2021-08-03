# 本地仓库操作

1 初始化本地仓库

`git init`

2 将本地文件推送到缓冲区

`git add .`

3 将文件从缓冲区推送到本地版本仓库 .git

`git commit -m "说明推送（一般如更新1 2等）"`

4 创建一个主分区
`git branch -M main"`

# 远程仓库建立

在github上新建一个仓库时，会有将本地仓库推送到远程仓库的操作指令

1 将本地仓库与远程仓库连接

`git remote add origin git@github.com:MGLF/repo1.git`

git@github.com:MGLF/repo1.git 是远程仓库的地址，一般本地仓库的名称与远程仓库名称都设为一致的

2 将本地仓库推送到远程仓库中

` git push -u origin main`

注意：每一次更新本地的内容时，都要将本地文件推送到缓冲区，再从缓冲区推送到本地仓库，然后再从本地仓库推送到远程仓库



