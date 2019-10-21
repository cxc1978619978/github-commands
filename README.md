# github常用命令


## 目录

### 一、连接github
#### 1.目录改为git管理仓库
$ git init

#### 2.设置名字和邮箱
$ git config --global user.name "Your Name"

$ git config --global user.email "email@example.com"

#### 3.本地创建版本库
$ git add .

$ git commit -m "wrote a readme file"

#### 4.添加远程库
$ git remote add origin ssh

#### 5.同步远程库
$ git push （-u） origin master