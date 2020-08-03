## 本地分支

<!-- 初始化 -->

git init

<!-- 添加文件 -->

git add <file>

<!-- 删除添加文件 -->

git rm --cached <file>

<!-- 查看状态 -->

git status

<!-- 添加某一类文件 -->

git add \_.html

<!-- 添加全部文件 -->

git add . || git add \*

<!-- 提交文件 -->

git commit -m "xxx"

<!-- 配置忽略文件 -->

.gitignore

<!-- 创建并切换到新的分支yangwl -->

git checkout -b yangwl

<!-- 创建分支 -->

git branch yangwl

<!-- 切换分支 -->

git checkout yangwl
...

<!-- 切回主分支 -->

git checkout master

<!-- 合并代码 -->

git merge yangwl

<!-- 初次使用添加远程仓库地址 -->

git remote add origin https://github....

<!-- 推送代码 -->

git push -u origin master

<!-- 再次使用，直接推送即可 -->

git push

<!-- 把本地分支yangwl推送到远程 -->

git push --set-upstream origin yangwl
