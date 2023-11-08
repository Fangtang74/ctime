# Ctime

利用MIRACL函数库来获取认证协议密码学操作的时间，分别对每次操作执行1000次运算并统计其时间，文件说明为：

| 操作              | 文件    |
| ----------------- | ------- |
| 椭圆曲线点乘      | sm.c    |
| 哈希函数(160-bit) | hash.c  |
| 异或操作(160-bit) | xor.c   |
| 随机数生成器      | rand.c  |
| 拉格朗日插值法    | lag.cpp |

