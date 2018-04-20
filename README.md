# test1
克隆代码
git clone  https://github.com/ccname/one.git

ctrl + insert  复制
shift + insert  粘贴
git branch 查看分支
git branch -D 删除分支
git checkout -b 分支名   创建分支
git commit -m 添加注释
git status  查看状态
git checkout 分支名    切换分支
git add .  添加修改的数据到缓存区
git add 修改的文件名
git push origin  分支名   提交本地分支到远程分支上
git config --global user.email "sss@qq.com"
git config --global user.name  "69"

git commit -am ''     添加和提交
ssh-keygen -t rsa -C +账号     创建秘钥
cd /
git diff 分支1  分支2   比较分支之间的不同
git tag -a 版本号 -m 注解       打tag标签
git merge   分支
git push origin  版本号     提交本地版本号到远程分支上 
git tag   查看分支
git tag -d 版本号   删除版本号
push origin --delete tag 版本号    删除远程版本号
git merge  合并分支
push origin --delete 分支名    删除远程分支


git merge 分支名 在当前分支上合并目标分支
git pull origin 分支名   将远程拉到本地 
git stash
git stash list 查看当前缓存
还原缓存 
git stash apply stash@{x} x –> 缓存号
清除缓存 
git stash clear 清除所有缓存
查看提交日志 
git log
查看某次提交内容 
git show 版本id
返回历史版本 
git reset –hard 版本ID
