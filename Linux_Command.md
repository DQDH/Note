Linux命令
========
命令|用法|
----|----
ps|ps -ef grep [] '进程号' 查看进程所对应的的宿主
fuser|查看*号显卡所有运行的程序：sudo fuser -v /dev/nvidia*
chown|  "change owner" 的缩写主要用于修改文件（或目录）的所有者，也可以修改文件（或目录）的所属组。

当只需要修改所有者时，可使用如下 chown 命令的基本格式：
[root@localhost ~]# chown [-R] 所有者 文件或目录
-R 选项表示连同子目录中的所有文件，都更改所有者。

如果需要同时更改所有者和所属组，chown 命令的基本格式为：
[root@localhost ~]# chown [-R] 所有者:所属组 文件或目录
