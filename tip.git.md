git config --global user.name "mc"
git config --global user.email "your_email@example.com" 
用户名和邮件作为全局唯一标识
git init 把目录变成git管理仓库
cd 进入
mkdir 生成目录
pwd 显示当前目录路径
rd 删除文件 
git add "xxx.txt" 将文件加入到缓存区
git commit -m "备注" 确认签入
git diff readme.txt 查看差异
git status 查看状态
git log 查看签入日志
git log --pretty=oneline 查看简写日志
git reset --hard head^ 回滚上一次
git reset --hard head^^ 回滚上两次
git reset --hard head~100 回滚上100次
git relog 查看版本号
git reset --hard 6fcfc89 回滚至特定版本号
git checkout -- readme.txt 丢弃工作区的修改
cat readme.txt 查看文件内容
touch README.md 创建文件


ls -al ~/.ssh 查看所有ssh key
ssh-keygen -t rsa -b 4096 -C "your_email@example.com" 生成SSH
eval "$(ssh-agent -s)" 启动ssh Agent
ssh-add ~/.ssh/id_rsa 加到ssh Agent
git remote add origin https://github.com/xxx/xxx.git
git push -u origin master
git clone https://github.com/rickxie/mctest.gt 克隆远程库
git checkout -b dev 创建dev分支 git branch dev/ git checkout dev
git branch 查看当前的分支
git merge dev 将dev merge到当前分支
  
查看分支：git branch

创建分支：git branch name

切换分支：git checkout name

创建+切换分支：git checkout –b name

合并某分支到当前分支：git merge name

将当前工作隐藏起来 git stash
查看工作现场  git stash list
恢复工作现场 git stash apply
删除工作现场 git stash pop

查看远程库信息 git remote
详细信息 git remote -v

把远程origin dev分支到本地来 git checkout  –b dev origin/dev
将本地dev分支推送到远程去 git push origin dev
拉去代码 git pull
设置本地分支与远程的链接 git branch --set-upstream dev origin/dev

删除分支：git branch –d name
删除远程关联:  git remote rm origin
记住账号密码: git config --global credential.helper store
