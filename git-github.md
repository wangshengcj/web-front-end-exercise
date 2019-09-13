 #git github

 - 下载安装

 - 配置 git config --global user.name "yourname"

 - 初始化 git init  （在本地建一个文件夹，然后把你的文件夹/目前变成一个本地仓）

 - 添加需要进行版本控制的文件 git add 文件名

 - 提交到版本控制仓库 git commit -m "备注信息"

 - 查看 git status

 - 关联到远程仓库 git remote add origin https://github.com/wangshengcj/web-front-end-exercise.git (远程库地址)

 - 推送更新 git push -u origin master

 - 退出 :q 回车

 #Windows下新建文件夹命令 mkdir

 - git diff 查看修改部分

 - 同步github上的项目到本地，使用fetch指令 git fetch origin

 - 和当前分支合并 git merge origin/master

 - 和当前分支合并更简单的方式  git pull origin master