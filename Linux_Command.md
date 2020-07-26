Linux命令
========
命令|用法|含义
----|----|----
awk|awk '/123|abc/' filename   | awk 的实现方式
ps|ps -ef grep / '进程号' |查看进程所对应的的宿主
fuser|sudo fuser -v /dev/nvidiaN |查看N号显卡所有运行的程序
chown|chown -R 所有者 文件或目录 |修改文件所有者 -R 选项表示连同子目录中的所有文件都更改所有者 
-|chown -R 所有者:所属组 文件或目录 |同时更改所有者和所属组
su| 进入root权限，exit退出
cat| cat /usr/local/cuda/version.txt |查看cuda版本
grep| cat train_audio.csv / grep ",6,/" >z.csv |查找指定字符串
grep| grep -o objstr filename/ wc -l |查找指定字符串出现的次数
grep| grep -o `objstr1\|objstr2` filename/wc -l |查找多种指定字符串出现的次数
grep|grep -E '123/abc' filename  | 找出文件（filename）中包含123或者包含abc的行
grep|egrep '123/abc' filename    | 用egrep同样可以实现
grep|grep objstr1 files / grep objstr2 |显示既匹配 objstr1 又匹配 objstr2 的行。
grep|grep -i objstr files   |不区分大小写地搜索。默认情况区分大小写，
grep|grep -l objstr files   |只列出匹配的文件名，
grep|grep -L objstr files   |列出不匹配的文件名，
grep|grep -w objstr files  |只匹配整个单词，而不是字符串的一部分（如匹配‘magic’，而不是‘magical’），
grep|grep -C number objstr files |匹配的上下文分别显示[number]行，
scp |scp -r ./Action_Recognition_Data/ public@10.102.125.137:/home1/2020_coding_data|传输文件
head|head -100  filename | 查看文件的前100行
tail|tail -100  filename 或 tail -n 100  filename|查看文件的后100行
sed|sed -n '100,200p' filename | 查看文件中间一段,第100行到第200行
