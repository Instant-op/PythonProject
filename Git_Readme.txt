git init 创建仓库
git add 添加到暂存区
git commit -m '' 提交文件信息
git checkout -- 文件名  撤销修改
git log -pretty=oneline  查看版本日志
git reflog 查看版本号
git status  查看当前状态
git reset --hard 版本号  回退到某版本号
git reset --hard HEAD^/^^/~100   回退到上一个/上上个/上100个版本号
git branch 
git branch -d <branchname>   查看本地分支/删除本地分支
git remote add origin 远程地址   连接远程仓库
git push -u origin master        提交项目到远程项目
git pull --rebase origin master  将项目文件从远程仓库下载到本地仓库
