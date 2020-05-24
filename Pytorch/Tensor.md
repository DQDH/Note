Tensor（张量）
=====
类似于Numpyde ndarrays,Tensor可以使用GPU进行计算
----
函数|含义
----|----
torch.empty(Row,Col)|创建Row行Col列的矩阵，不初始化
torch.rand(Row,Col)|构造随机初始化的矩阵
torch.zeros(Row,Col,dtype=torch.long)|创建long类型，全为0的矩阵
torch.tensor([data1,data2])|构造一个可以试用的张量
x.new_ones(Row,Col,dtype=torch.double)|创建Row行Col列全文1的矩阵
torch.randn_like(x,dtype=torch.float)|基于已经存在的tensor来创建tensor
x.size()|tensor x的维度信息，输出的torch.Size是一个元祖

