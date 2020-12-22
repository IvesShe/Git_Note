# Git Note

平常用sourceTree習慣了，指令漸漸陌生，寫一個筆記，記錄常用的指令，以應付不方便使用sourceTree時的環境

# GIT指令

```bash
# 初始化一個倉庫
git init

# 下載一個項目
git clone URL

# 顯示當前git配置
git config --list

# 添加當前目錄所有文件到暫存區
git add .

# 提交代碼
git commit -m "message"

# 提交工作區自上次commit之後的變化，直接到倉庫區
git commit -a

# 查看本地所有分支
git branch

# 查看遠程所有分支
git branch -r

# 新建一個分支，但仍停留在當前分支
git branch 分支名

# 新建一個分支，並切換到該分支
git checkout -b 分支名

# 在現有分支與指定的遠程分支之間，建立追蹤關係
git branch --ser-upstream 本地分支名 遠地分支名(origin/分支名)

# 合併指定分支到當前分支
git merge 分支名

# 刪除分支
git branch -d 分支名

# 刪除遠程分支(沒試過)
git push origin --delete 分支名
git branch -dr remote/分支名

# 顯示有變更的文件
git status

# 顯示暫存區和工作區差異
git diff

# 上傳本地指定分支到遠程倉庫
git push reomte/分支名

# 從遠程倉庫拉取
git pull remote/分支名
```
