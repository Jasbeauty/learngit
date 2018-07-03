# learngit
> Git is a distributed version control system  
Git is free software distributed under the GPL  
Git has a mutable index called stage  
Creating a new branch is quick

### 上传本地项目到GitHub
#### 创建一个本地项目
* `git init`
> 执行git init，初始化成功后你会发现项目里多了一个隐藏文件夹.git 

* `git add .`
> 将所有文件添加到仓库  

* `git commit -m "....."`
> 双引号内是提交注释  

#### 关联GitHub仓库
* `git remote add origin git@github.com:Jasbeauty/route.git`
> 根据仓库地址，连接你的GitHub仓库  

* `git pull --rebase origin master`
> 进行代码合并(pull = fetch + merge)  

#### 上传本地代码
* `git push -u origin master`  
> git是不能管理空的文件夹的，文件夹里必须有文件才能上传
