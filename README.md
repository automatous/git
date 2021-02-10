# git
git使用指南：
1. 首先在github官网上创建远程仓库
2. 在本地非目标目录的临时目录中（建议专门搞个临时目录），执行git clone 刚创建的远程仓库地址
3. 进入刚才拉下的目录中，将.git及其他文件copy到目标目录（.git目录默认隐藏，可设置显示）
4. git status 显示要添加的文件（最好添加.gitignore文件）；在git add需要添加的文件；最后 git commit -m 'xxxx'，git push
5. 本地文件即可提交至远程仓库
