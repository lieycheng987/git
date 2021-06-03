# git 
## 拉取远程代码到本地
1.在本地新建一个文件夹，文件夹名称可以跟远程的

2.将本地的文件夹初始化为一个git仓库：git init

3.与远程仓库建立连接; git remote add origin http://xxxx/.git(远程仓库的地址)

4.把远程分支拉取到本地：git fetch origin dev(远程分支名)

5.本地建立一个分支，分支名与远程的一样 ：git checkout -b dev(分支名)

6.把远程指定的分支拉取到本地：git pull origin dev(远程分支名)
