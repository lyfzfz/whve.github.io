# bioinformatics

## 小分子在生命中的作用
生命的起源与火山相关.一些火山口附近,存在小分子即小肽.
有一种假说,正是因为这些小分子的出现,才会为后来蛋白质的出现提供基础.就好像是织毛衣的毛衣球,毛球的形状取决于内部的形状.    
此为蛋白质起源的小分子诱导假说.

## 生信杂志
1. [bib](https://academic.oup.com/bib)
1. [bioinformatics](https://academic.oup.com/bioinformatics)


# 蛋白质结构预测与分析  
## 蛋白质的结构  
### 蛋白质的结构分为四类
一级结构也就是氨基酸序列，  
二级结构是周期性的结构构象，比如α螺旋β折叠等。  
三级结构是整条多肽链的三维空间结构。  
四级结构是几个蛋白质分子形成的复合体结构，比如三聚体，四聚体等。  
蛋白质是由氨基酸组成的，前一个氨基酸的羧基和后一个氨基酸的氨基脱去一分子的水，缩合形成的肽键。肽键将氨基酸连接起来形成肽链。
发掘蛋白质的结构特征是理解蛋白质生物
功能的基础，这对于整个生物医药领域的研究都非常重要。  
拥有了空间立体结构之后，蛋白质才能发挥功能。  

## 蛋白质的二级结构  
以字母形式书写的二级结构序列能够更加精准的描述。其中，E 代表β折叠，H 代表α螺旋，T 代表转角。没有写任何字母的地方是松散的 coil 结构。
## 蛋白质的三级结构
实验方法
x射线衍射法
核磁共振法
冷冻电镜显微技术
## 三级结构可视化软件
VMD
pymol

## 计算方法预测三级结构
从头计算法ab initio
1973 Anfinsen 蛋白质的三维结构决定于自身的氨基酸序列,并且处于最低自由能状态.  
quack 张阳
同源建模法homolog modeling  
**原理**  相似的氨基酸对应着相似的蛋白质结构.  
步骤流程:找到与目标序列同源的已知结构模板(一致度>=30%)  
穿线法threading
不相似的氨基酸序列也可以对应着相似的蛋白质结构.  
已知的蛋白质结构约10万个,所具有的不同的拓扑结构只有1393个.  
根据能量方程,能量越低预测越好.
I-TASSER 美国密歇根大学张阳  
casp蛋白质结构生物信息预测国际竞赛

综合法ensemble method
找到模板的区域用同源建模法,找不到的区域用从头计算法.
## 三级结构的比对
## 蛋白质分子表面性质
## 获取蛋白质四级结构
## 蛋白质-蛋白质分子对接
## 蛋白质-小分子分子对接
## 虚拟筛选与反向对接
## 分子动力学模拟

F=U-TS
F 自由能，U 内能，T 温度，S 熵