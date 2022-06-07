## jeecg框架的搭建和本地运行
### 环境搭建
-  在官网下载源码
[下载链接](http://www.jeecg.com/download)
-  下载工具以及工具配置环境
由于IDEA先前已经成功下载，这里不再进行赘述。

下载node.js并配置环境

下载yarn

下载redis压缩包

下载maven（也可以使用IDEA中自带的maven插件）

下载mysql

-  开始配置前后端环境
打开下载文件夹“jeecgboot-vue3-master”，在控制台输入“yarn install”下载项目执行所需要的依赖，下载成功会有一个名为“node_modules”的新文件夹。

之后通过IDEA打开文件夹“jeecg-boot”,打开db文件夹下的“jeecgboot-mysql-5.7.sql”文件，点击右侧的database，连接到本地数据库，然后开始运行该文件，之后会成功建立一个新的数据库“jeecg-boot”。
### 本地运行
-  在命令行中输入：redis-server.exe打开redis。

![redis打开页面](https://images.gitee.com/uploads/images/2022/0607/164040_88a787f9_5361430.png "redis-server.png")
-  在命令行中输入命令：npm run serve

![输入图片说明](https://images.gitee.com/uploads/images/2022/0607/164054_afb8413e_5361430.png "npm run dev 2022_6_7 16_27_43.png")
![npm成功运行界面](https://images.gitee.com/uploads/images/2022/0607/164105_2f7884c7_5361430.png "npm run dev 2022_6_7 16_28_43.png")
-  打开前端

在IDEA中运行JeecgSystemApplication.java
![IDEA运行界面](https://images.gitee.com/uploads/images/2022/0607/164149_238a0b7b_5361430.png "jeecg-boot-parent – JeecgSystemApplication.java [jeecg-boot-module-system] Administrator 2022_6_7 16_27_22.png")
-  之后打开网址：

http://192.168.248.1:3100/或http://192.168.198.1:3100/或http://10.21.202.126:3100/来打开前端。
-  打开前端之后，执行页面如下：

![系统登录界面](https://images.gitee.com/uploads/images/2022/0607/164328_3b116b27_5361430.png "登录 - JeecgBoot 企业级低代码平台 - Google Chrome 2022_6_7 16_31_54.png")
-  其中验证码可以正常显示，表示后端也已经成功打开。

输入验证码之后，点击登录，进入该系统。
![成功进入系统](https://images.gitee.com/uploads/images/2022/0607/164438_b0fbf3c2_5361430.png "登录 - JeecgBoot 企业级低代码平台 - Google Chrome 2022_6_7 16_32_08.png")
![成功进入系统](https://images.gitee.com/uploads/images/2022/0607/164450_80ab8e50_5361430.png "登录 - JeecgBoot 企业级低代码平台 - Google Chrome 2022_6_7 16_32_30.png")
