# 1.配置
- git config
  * git config --global user.name < Your name >
  * git config --global user.email < Your email >
  * git config --global user.credential.helper store
# 初始化/创建仓库
- git init < repo >
# 从网站上下载
- git clone < url > < dir >
  * git clone git://github.com/xxx/yyy.git
- git status
- git add
- git diff
- git commit
  git commit -m "xxxxx"

- git log
  * git log --oneline
  * git log --reflog

- git reset
  *  git reset --soft 保留工作区、暂存区
  *  git reset --hard 丢弃工作区、暂存区
  *  git reset --mixed 保留工作区、丢弃暂存区（默认）
  *  git reset --hard HEAD^ 回退上个版本
  *  git reset --hard 版本号 回退上个版本
  *
- git rm
- git reflog
- git branch name
- git switch -c branch
- git branch -d xxx
- git merge xxx
-  git merge --no-ff
-  git remote add origin git@github.com:michaelliao/learngit.git
-  git push origin master