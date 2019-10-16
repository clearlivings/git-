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
