# git笔记

1. git init
	> 初始化git

2. git add file
	> 添加到暂存区,可以一次添加多个文件 比如 git add file file  / git add.(只会把改动的提交)
3. git status
	> 查看状态：红色状态是在本地,未托管到本地仓库,绿色是暂存区

4. git commit -m "message"
	> 提交到本地仓库

5. git remote add origin url
	> 链接远程仓库

6. git push -u origin master
	> 推送到远程端(gitHub),如果不是第一次就不使用-u(update)

7. git add -u
	> 只能上传改动后的文件到暂存区
	
<!-- 8. git -->