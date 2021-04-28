# HITszDBLab42021
HITsz数据库实验4 2021春

1. 实现基于线性搜索的关系选择算法：基于ExtMem程序库，使用C语言实现线性搜索算法，选
出S.C=50的元组，记录IO读写次数，并将选择结果存放在磁盘上。（模拟实现 select S.C,
S.D from S where S.C = 50）

2.  实现两阶段多路归并排序算法（TPMMS）：利用内存缓冲区将关系R和S分别排序，并将排
序后的结果存放在磁盘上。（不可定义长度大于10的整型或字符型数组）

3.  实现基于索引的关系选择算法：利用（2）中的排序结果为关系S建立索引文件，利用索引文
件选出S.C=50的元组，并将选择结果存放在磁盘上。记录IO读写次数，与（1）中的结果对
比。（模拟实现 select S.C, S.D from S where S.C = 50 ）
4.  实现基于排序的连接操作算法（Sort-Merge-Join）：对关系S和R计算S.C连接R.A ，并统计
连接次数，将连接结果存放在磁盘上。 （模拟实现 select S.C, S.D, R.A, R.B from S inner
join R on S.C = R.A）
5. 实现基于排序或散列的两趟扫描算法，实现并（S R） 、交（S R） 、差（S - R）其中
一种集合操作算法。将结果存放在磁盘上，并统计并、交、差操作后的元组个数
