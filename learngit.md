learn git.

https://www.cnblogs.com/jinzhaozhao/p/10012504.html

生成 SSH 公钥
ssh-keygen

cat ~/.ssh/id_rsa.pub


连接远程仓库
git remote add origin git@github.com:591342534/BasicLib.git
git pull --rebase origin master

将本地仓库文件推送到远程仓库
git push -u origin master
git push origin master
git push -f origin master

新建一个空的仓库
git init

查看git配置信息
git config --list

查看git用户名
git config user.name
全局配置用户名
git config --global user.name "xxxxx"

查看邮箱配置
git config user.email
全局配置邮箱
git config --global user.email "xxxxx@qq.com"


提交(文件名字read.txt)
git add read.txt
git add .

查看状态
git status

提交.提交添加的文件并备注说明
git commit
git commit -a
git commit -m 'fix bug'

查看变更日志
git log

版本号前六位 回归到指定版本
git reset --hard 

查看分支
git branch

创建一个叫newname的分支
git branch newname

切换到叫newname的分支上
git checkout newname

把newname分支合并到当前分支上
git merge newname

将master分支上的内容拉到本地上
git pull origin master













d
