# holiday_jeecg
## 下载IDEA，并且安装Lombok,Sonarlint,阿里规约等插件
## 安装git，并在github上创建个人工程，完成一次pull request记录
-  在本地文件夹下右键打开git bash

然后执行以下命令

`mkdir gitTest`

`cd gitTest`

`git init`

`git remote add origin git@github.com:Jii796/holiday_jeecg.git`#这里的仓库地址使用的是ssh地址，这样可以避免在push操作中输入密码和用户名

`git pull origin main:main`

`touch jeecg_run.md`

`git add jeecg_run.md`

`git commit -m "commit the information of jeecg"`

`git push -u origin main`

## jeecg框架的搭建以及本地运行
-  该部分的实现参考jeecg_run.md文档
