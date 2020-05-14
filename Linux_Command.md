Linux命令
========
命令|用法|
---------
----|----
ps|查看进程所对应的的宿主：ps -ef grep | '进程号'
sudo|查看*号显卡所有运行的程序：sudo fuser -v /dev/nvidia
chown| 命令，可以认为是 "change owner" 的缩写
主要用于修改文件（或目录）的所有者，除此之外，这个命令也可以修改文件（或目录）的所属组。

当只需要修改所有者时，可使用如下 chown 命令的基本格式：
[root@localhost ~]# chown [-R] 所有者 文件或目录
-R 选项表示连同子目录中的所有文件，都更改所有者。

如果需要同时更改所有者和所属组，chown 命令的基本格式为：
[root@localhost ~]# chown [-R] 所有者:所属组 文件或目录
