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
## 查看本地库状态
~~~bash
$ git status
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
### .gitignore 文件通常不需要推送到远程 GitHub 仓库中，因为它是本地的配置文件，不会影响其他用户，并且 GitHub 默认会忽略它。推送 .gitignore 文件通常不必要，其他开发者可以根据需要在本地创建自己的规则。
~~~bash
# 忽略.gitignore
.gitignore
# 忽略所有 .log 文件
*.log
# 忽略 node_modules 文件夹
node_modules/
# 忽略一个特定的文件
config.json
~~~
