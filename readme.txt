使用当前目录作为Git仓库，我们只需使它初始化。
git init
该命令执行完后会在当前目录生成一个 .git 目录。
使用我们指定目录作为Git仓库。
git init newrepo
初始化后，会在 newrepo 目录下会出现一个名为 .git 的目录，所有 Git 需要的数据和资源都存放在这个目录中。
如果当前目录下有几个文件想要纳入版本控制，需要先用 git add 命令告诉 Git 开始对这些文件进行跟踪，然后提交：
$ git add *.c
$ git add README
$ git commit -m '初始化项目版本'
