### 操作文件内容
	进入vim界面按insert键进行修改，然后esc退出修改，然后shift+:进行wq保存退出。
	vim界面 鼠标中键复制粘贴。
| 设置用户基本信息 | `1.git config --global user.name 名称 `<br>`2.git config --global user.email "邮箱"`| 
| :-----| :---- |
| 初始化本地库 | `git init` |
| 查看本地库状态 | `git status` |
| 查看版本详细信息 | `git log` |
| 查看历史版本信息 | `git reflog` |
| 版本穿梭 | `git reset --hard 版本号` |
| 把代码加入到缓存区 | `git add 文件名` |
| 提交缓存区内容且加入留言注释 | `git commit -m "日志信息" 文件名` |
| 克隆远程仓库代码到本地 | `git clone 远程地址` |
| 起别名 | `git remote add 别名 远程地址` |
| 查看当前所有远程仓库别名 | `git remote -v` |
| 上传代码至远程库进行合并 | `git push 别名 master` |
| 从远程库下载代码合并本地代码版本 | `git pull 远程库地址别名 远程分支名` |
| 创建本地分支 | `git branch 分支名` |
| 查看远程分支 | `git branch -a` |
| 查看本地分支 | `git branch` |
| 切换分支 | `git checkout 分支名` |
| 把指定的分支合并到当前分支 | `git merge 分支名` |
