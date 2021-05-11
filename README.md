# test

#### 介绍

Learn Git
git 使用说明
1. 新建仓库
2. git clone xxx.git # 将远程仓库克隆到本地
3. 配置用户信息
   - git config --global user.name "你的名字或昵称"
   - git config --global user.email "你的邮箱"
4. 进入clone下来的仓库目录
5. git add . #将当前目录所有文件添加到git暂存区
6. git commit -m "my first commit" #提交并备注提交信息
7. git push origin master #将本地提交推送到远程仓库，master可替换位其他分支
8. 新建分支：
    - 进入git仓库所在的目录
    - git branch # 查看当前目录的分支
    - git branch test # 新建test分支
    - git push origin test # 将分支push到仓库
