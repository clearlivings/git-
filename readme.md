`touch .gitignore 生成 .gitignore文件`

`npm cache clean --force 解决莫名其妙的错误`

### 查看用户名密码

`git config user.name`

`git config user.emil`

### 修改用户名和邮箱地址

`git config --global user.email "zhangkexu@yunquna.com"`

`git config --global user.name "zhangkexu"</code>`


### 查看配置

`git config --list`

### 从master分支拉新分支

`git checkout -b dev`

### push到远端

`git push origin dev`

### 拉取远端分支

`git pull`

### 关联

`git branch --set-upstream-to=origin/dev`

### 再次拉取 验证

`git pull`

### 当正在开发的时候，又要到别的分支搞事情（比如改bug）,又不想放弃当前分支的修改，那么

`git stash ----储藏，但默认不会储藏未跟踪的文件和被忽略的文件，比如新建了一个文件`

### 开发完了，想恢复之前分支的改动，那么

`git stash pop ----恢复存储并删除`
`git stash apply ----恢复存储不删除`

### 展示存储
 
`git stash show`

### 删除存储

`git stash clear`

### 修改commit信息（单次提交）

`git commit --amend`

### 退出shell

`Esc下 大写Z Z 下就退出了(windows)Mac下不知道,因为没机器`
