## 使用Git建立本地仓库并上传代码到GitHub
+ 在本地建立项目文件夹，右键选择git bash here，打开git命令行操作界面。
+ 在GitHub上新建repository，获取远程仓库地址。
1. 输入个人信息(代码提交者)
	git config --global user.name "xxxx"
	git config --global user.email xxxxx@qq.com
2. 初始化本地仓库
	git init
3. 将需要上传的代码复制粘贴到本地仓库，并提交到本地仓库。
	git add .
	git commit -m "this is first commit"
4. 关联本地仓库
	git remote add origin https://github.com/lusky0216/notes.git
5. 远程库和本地库合并
	git pull --rebase origin master
6. 推送代码到主分支
	git push origin master
