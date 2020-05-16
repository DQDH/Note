字符串&字符
====
函数|用法|含义
----|----|----
strip| s.strip()| #删除空白字符
-|strip('a') |  #删除指定字符
rstrip|'aaddfaa'.rstrip('a') |#删除字符串右端指定字符>>aaddf
lstrip|'aaddfaa'.lstrip('a') |#删除字符串左端指定字符>>ddfaa
chr|chr|chr(int_num) |#将整型转成字符型(对应ascii表)
int|int('52')=52 |#可直接将字符串转为数字
ord|ord('a')  |#将字符转为ASCII十进制码
bin|bin(6)='0b110' |数字转二进制码字符串，有0b标识符
int|int('10',base=2)=2|二进制转十进制
大写字母|65~90| A~Z
小写字母|97~122 |a~z
join|''.join(dp) |#将字符串数组dp连接为一个字符串
特殊表达|s=s[::-1] |将s翻转
特殊表达|strx == stry |判x,y字符串是否相等
count|s.count(s[i]) |计算某个字符出现的次数
replace|s.replace(s[i],ss) |用ss替代s中的s[i]
split|s.split(' ')  |将字符串s以' '分开，返回一个列表
zfill|s.zfill(5)  |将字符串s以0补全到5位
upper|str.upper()  |将str转为大写
lower|str.lower() |将str转为小写
islower|str.islower() |方法检测字符串是否由小写字母组成
isupper|str.isupper() |方法检测字符串是否由大写字母组成

列表
====
sorted([5, 2, 3, 1, 4])#所有可迭代对象都可以
一个新的list：>>[1, 2, 3, 4, 5]
>>> a = [5, 2, 3, 1, 4]
>>> a.sort()  #只能用在list
>>> a
[1, 2, 3, 4, 5]  原list被修改

list.index(list[i])#某元素下标

[[0]*cols,for i in range(rows)]#生成二维列表

list(string) 将string转为list

set（list）将list去除重复项 返回新的集合对象{} 需list()

list.remove(list[i])删除list中list[i]

list.reverse() 将list翻转

list.count(123) 计算某个元素出现的次数

list1 = ['Google', 'Runoob', 'Taobao']
list1.insert(1, 'Baidu')
print ('列表插入元素后为 : ', list1)
列表插入元素后为 :  ['Google', 'Baidu', 'Runoob', 'Taobao']
del list[2] 删除list第3个元素

list.insert(i, x)	在指定位置插入一个元素。
第一个参数是准备插入到其前面的那个元素的索引，
例如 a.insert(0, x) 会插入到整个列表之前，而 a.insert(len(a), x) 相当于 a.append(x)
list1+list2  ##两个list相连

sorted(intervals, key=lambda x: x.start)

aList = [123, 'xyz', 'zara', 'abc', 123];
bList = [2009, 'manni'];
aList.extend(bList)=[123, 'xyz', 'zara', 'abc', 123, 2009, 'manni']

A=['1','1','1']
B=['2','2','2']
lst=list(zip(A,B))
print(lst)
print(list(zip(*lst)))
print(list(zip(lst)))
[('1', '2'), ('1', '2'), ('1', '2')]
[('1', '1', '1'), ('2', '2', '2')]
[(('1', '2'),), (('1', '2'),), (('1', '2'),)]

########链表
处理链表时：a=b=ListNode()生成的a,b指向同一地址
pA = pA.next if pA else headB
等于=
if pA:
pA=pA.next
else:
pA=headB


内置函数：
map(square, [1,2,3,4,5])   # 计算列表各个元素的平方
[1, 4, 9, 16, 25]
map(lambda x: x ** 2, [1, 2, 3, 4, 5])  # 使用 lambda 匿名函数
[1, 4, 9, 16, 25]
 
# 提供了两个列表，对相同位置的列表数据进行相加
>>> map(lambda x, y: x + y, [1, 3, 5, 7, 9], [2, 4, 6, 8, 10])
[3, 7, 11, 15, 19]



<<	左移动运算符：运算数的各二进位全部左移若干位，由"<<"右边的数指定移动的位数，高位丢弃，低位补0。
>>	右移动运算符：把">>"左边的运算数的各二进位全部右移若干位，">>"右边的数指定移动的位数


