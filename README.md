clover
======

blishopeful


## github 环境搭建

* 1.在 https://github.com上创建一个仓库,如名字为clover
* 2.生成公钥: 
```
   $ ssh-keygen -t rsa -C "pecksrh@gmail.com"
   cat /home/peck/.ssh/id_rsa.pub
```
* 3.本地terminal:
```
   a. $mkdir clover
   b. $cd clover
   c. $git init
   d. $touch README.md
   e. $git add README.md
   f. $git remote add origin https://github.com/pecksrh/clover.git  //让本地仓库的当前分支(origin)去关联远程的clover仓库
   g. $git push -u origin master  //把本地仓库当前分支的所有数据提交到已经创建关联的远程仓库的master分支
```
* 4.安装jekyll
```
   a. $sudo apt-get install ruby1.9.1-dev
   b. sudo gem install jekyll
```
* 5.安装Rdiscount，这个用来解析Markdown标记的包
```
   $ gem install rdiscount
```
