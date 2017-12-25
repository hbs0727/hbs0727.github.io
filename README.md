# hbs0727.github.io
这是我的github网站

git命令记录

- 在 github 仓库(repository)
    仓库名称(Repository name)
    描述(Description)
    Public/Private
    Readme

(如:https://hbs0727.github.io/)

- 克隆仓库到本地
    git clone https://github.com/Owner/repository
    git clone https://github.com/hbs0727/hbs0727.github.io

- 进入 本地仓库
    cd repository
    cd hbs0727.github.io

- 添加文件到仓库
   git add 文件
   git add .

- 提交文件
    git commit -m "描述"

- 检测状态
    git status

- 修改内容
    git diff

- 设置 ssh
    ssh-keygen -t rsa -C "youremail@example.com"
    ssh-keygen -t rsa -C "hbs0727@163.com"
    (默认设置)

- 在 git 记录 ssh(公)
    C:\Users\Administrator\.ssh\id_rsa.pub
    https://github.com/settings/ssh/new

- 提交到远程
    git remote add origin git@github.com:hbs0727/hbs0727.github.io.git

- push
    git push -u origin master