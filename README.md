# git
git 命令使用说明
## 本地建库: 在本地创建Git库命令
~~~bash
$ git init
~~~
## 服务器库拉到本地库
~~~bash
$ git pull origin main
~~~
## 增删文件到比较库
~~~bash
$ git add a.txt
$ git rm a.txt
~~~
## 比较库commit到本地库
~~~bash
$ git commit -m "add/rmove a.txt"
~~~
## 本地库推到服务器库
~~~bash
$ git push origin
~~~
## 查看本地库log
~~~bash
$ git log
~~~
## .gitignore文件规则
~~~bash
# 忽略所有 .log 文件
*.log
# 忽略 node_modules 文件夹
node_modules/
# 忽略一个特定的文件
config.json
~~~
