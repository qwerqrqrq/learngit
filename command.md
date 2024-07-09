#1. 配置
- git config
  - *git config --global user.name < Your name >
  -  *git config --global user.email < Your email >
  -  *git config --global user.credential.helper store
-  初始化/创建仓库
- git init
  -* git init < repo >
- git clone < url > < dir >
    * git clone git://github.com/xxx/yyy.git

- git add
- git status
- git diff
- git commit
  - * git commit -m "xxxxx"
- git reset
    * git reset --hard HEAD^
- git rm
- git reflog
- git branch name
- git switch -c branch
- git branch -d xxx
- git merge xxx
-  git merge --no-ff
-  git remote add origin git@github.com:michaelliao/learngit.git
-  git push origin master