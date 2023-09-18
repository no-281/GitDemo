1.安装git
2.在文件夹内右键点击 git bash here
3.在弹出的命令栏内输入 git init 生成一个.git隐藏文件夹，里面包含git管理该文件夹内文件的各项配置和版本信息
4.输入 git status 检查文件夹内文件状态，红色名字的文件代表文件未被git管理，绿色名字代表被管理文件
5.输入 git add 文件名 让git管理某个文件， 输入 git add .  让git管理文件夹内所有文件
6.输入 	git config --global user.email "邮箱"
		git config --global user.name "名称"
		注意：git config命令的–global参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。
7.输入 git config -l 查看你的配置信息

8.输入 git status 时
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ReadMe.txt

no changes added to commit (use "git add" and/or "git commit -a")


