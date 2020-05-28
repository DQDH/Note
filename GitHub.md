linux上传代码至Github
=====
安装git
----
参考https://blog.csdn.net/top_code/article/details/50241999

配置git
----
* 需要配置的是用户的用户名和email，因为这些内容会出现在你的每一个提交（commit）里面的，
>git config --global user.name "your name"<br>
 git config --global user.email "your_email"

* Git的配置信息分为全局和项目两种，上面命令中带了“–global”参数，这就意味是在进行全局配置，它会影响本机上的每个一个Git项目。 
Git 可以为每个项目设定不同的配置信息，在命令行环境，进入Git项目所在目录，执行下面的命令：
>git config user.email "1606074918@qq.com"<br>
 git config user.name "DQDH"
 
初始化git
-----
git init

创建一个github仓库Test，并复制链接。将创建的仓库克隆到本地
----
git clone github.com/Test
添加上传的文件
----
cd Test
git add . 上传所有文件
git add hello.py 上传指定文件
git commit -m "This is the hello world code" 提交描述信息
git push origin master 上传到仓库
