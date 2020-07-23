Linux命令
========
命令|用法|含义
----|----|----
ps|ps -ef grep / '进程号' |查看进程所对应的的宿主
fuser|sudo fuser -v /dev/nvidiaN |查看N号显卡所有运行的程序
chown|chown -R 所有者 文件或目录 |修改文件所有者 -R 选项表示连同子目录中的所有文件都更改所有者 
-|chown -R 所有者:所属组 文件或目录 |同时更改所有者和所属组
su| 进入root权限，exit退出
cat| cat /usr/local/cuda/version.txt |查看cuda版本
grep| cat train_audio.csv / grep ",6,/" >z.csv 查找指定字符串
scp |scp -r ./Action_Recognition_Data/ public@10.102.125.137:/home1/2020_coding_data|传输文件
