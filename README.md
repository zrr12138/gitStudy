# gitStudy

用于学习git

## 常用命令

首先在可视化的远程仓库上新建一个仓库

ssh-keygen -t rsa
cat ~/.ssh/id_rsa.pub
复制内容到仓库上添加ssh-key
git clone git@github.com:zrr12138/gitStudy.git  //选择ssh链接

git config --global user.name "zrr12138"
git config --global user.email "1520407273@qq.com"

git log --graph --decorate //图形化显示log

git remote -v //查看默认push fetch仓库

git status //查看当前git状态，有哪些未保存文件等等

git diff //查看当前工作树与暂存区的差别

git branch //显示分支一览表

git checkout -b //以当前分支为基础创建并切换新分支

git remote add origin https://github.com/zrr12138/gitStudy //添加远程仓库
