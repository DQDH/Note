Linux命令
========
命令|用法|含义
----|----|----
ps|ps -ef grep / '进程号' |查看进程所对应的的宿主
fuser|sudo fuser -v /dev/nvidiaN |查看N号显卡所有运行的程序
chown|chown -R 所有者 文件或目录 |修改文件所有者 -R 选项表示连同子目录中的所有文件都更改所有者 
-|chown -R 所有者:所属组 文件或目录 |同时更改所有者和所属组
