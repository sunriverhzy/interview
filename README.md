### 腾讯广告 （拿到意向书）
（CDG）（后来合并到TEG数平）
 腾讯在九月份通知转正了，所以就么有面试啦

### 字节抖音提前批（gg）
#### 一面
* 问项目，犀牛鸟图谱，图怎么设计的，商品是什么
* c++ 多态重载
* 二叉树最大宽度

#### 二面
* 问项目，图神经网络，GraphSage，loss函数怎么设计的，embedding怎么得到的，讲解一下GCN具体的，你构建的图不需要根据权重删减？ 
* attention， softmax 漏了大意了， 具体怎么算的
* LCS，输出最长子序列

### 爱奇艺（自己给拒了）
#### 一面：
* BERT，Roberta的区别
* 如何处理超长文本？
* 实习的主要工作,有什么想法
* code: 区间合并

#### 二面
* 了解哪些预训练模型，
* 讲一下实习的工作，
* 机器学习了解哪些
* 处理的都是剧本这种超长文本，有什么好的方法
* code: 字符串字符替换
  （爱奇艺后面三面我直接给拒了）

### 猿辅导人工智能研究院NLP(9/16 拿到意向书)
#### 一面
* 字符消消乐
* 两个字符串，#号代表退格，判断完成退格后两字符串是否一样

#### 二面
* k个一组翻转链表
* 最小覆盖字符

#### 三面
* 问了我论文的做法，为什么有效？
* 来的意愿
* 了解预训练模型，选个讲一讲
* code : 大数乘法

### 商汤 
#### 二面
* 自然语言处理为什么使用LN，不适用BN
* 最大频率堆栈

### 百度提前批（gg）
#### 一面
* Transformer权重共享：1）Encoder和Decoder间的Embedding层权重共享，2）Decoder中Embedding层和FC层权重共享
* Self-Attention复杂度
* word2vec中，skipgram和cbow的区别，哪个低频词更好
* 怎么衡量那种词向量更好。
* const关键字作用	
* 内存泄漏介绍一下
* code:   1）实现linear层的前向逻辑和反向逻辑
          2）k个一组翻转链表
          3）双核GPU分配任务，使得总体时间最短

#### 二面
* 问项目，
* NLP都有哪些任务，具体怎么做的，模型用的什么
* 有了解NLP的哪些任务，NLP目前的实际应用有哪些
* 删除字符串的空格

#### 三面（经理面）
* 什么能力很重要？
* 自己对未来规划
* 最大的挑战？
* 自己什么能力最突出？
* 对公司的看法

**（吐槽一下，这都经理面了，还给我挂了，然后知道的身边七个人好像就没有人过的）**

### 百度正式批（9/17 搜索策略部HR打电话通知过了）
#### 一面
* 先写个题： m*n矩阵，每个位置都有一个值，从(0,0)走到(m-1,n-1)的路径之和最小值；
* 介绍一个最熟悉的项目，项目的创新点在哪？

#### 二面
* 介绍一下实习的工作，遇到的难题
* 剑指offer原题：长度为n的数组，取值在1 ~ n-1，找出重复的数字

#### 三面
* 就问了一些有的没的，没啥技术含量好像，问了一些HR会问的问题

### 美团优选（拿到意向书）
#### 一面
* 问项目，知识图谱， 事件抽取，做了什么，大词林
* BERT预训练怎么做的，了解其他的预训练模型吗
* 有关注过下游任务具体应用吗
* 题目：无限次没有手续费购买股票

#### 二面
* 唠嗑，和我讨论业务的做法。。

### 字节广告（gg  四面给我挂了，我*****）
#### 一面
* 介绍论文，怎么做的？
* 讲下BERT，BERT的预训练任务，
            1）mask: 为什么分为三部分？ 不是所有的mask都是训练的目标， 还有一部分词输入是错误的，就是加噪，因为mask在实际上并没有，
            2）NSP任务无效？：改进，判断是否是上下句，以及句子重排
* 介绍Transformer： Encoder怎么做的？
		            self attention(为什么除以sqrt(d)), 
		            FFN有什么用, 
                    为什么要加LN，为什么要层归一化(LN)？ 为什么使用LN
                    为什么要加残差网络？
                    激活函数是什么？GELU RELU
* Softmax的改进，层次Softmax
* BERT后加CRF为什么，必须吗？为什么？
* 介绍一下CRF？和HMM最大的区别是什么（判别生成）？
* 介绍一下F值，宏平均F1，微平均F1, beta的意思是什么
* 介绍一下实习任务，图的节点是什么，要用什么训练？
* code: 逆序对数量

#### 二面
* 论文介绍，怎么做的，创新点在哪？
* 交叉熵损失函数是啥
* 伪代码实现梯度下降
* code：有序矩阵topk

#### 三面
* 讲一下论文
* 计算机基础怎么样？
* dijsktra算法讲一下？
* 堆排序怎么做的讲一下，堆排序更适用于哪些场景
* code: 约瑟夫环问题
* 概率题： 50个学生，至少有两个在同一天生日的概率

#### 四面
* 挑一个熟悉的项目讲一下
* 项目具体怎么做的？
* 模型CNN和BERT直接是什么关系
* 输入token的长度会影响pooling的效果吗？
* 为什么你觉得BIO标注和BIEOS标注结果差不多？说说你自己的看法
* 用序列标注解决事件抽取，你的文档长度2000+，一篇文档只有几个实体，这个标签的占比是多少，不平衡，你觉得怎么解决？
* 类型的信息不是已经融合到你的标签标注体系了，为什么还要吧事件类型编码加到模型里？
* 给你两个集合，实现去交集的操作

### 拼多多
#### 一面
* 先coding: 实现链表k个一组翻转
* 介绍一下实习的工作，图的节点都是啥？
* 看起来像二部图，为啥不用矩阵分解？
* 你了解矩阵分解吗？
* 怎么评价最终学习的embedding的效果？

#### 二面
* 讲一下熟悉的项目
* 你用到了BERT，讲一下BERT具体的实现吧
* 了解机器学习下相关算法吗？
* 那就看一下逻辑回归的相关问题：
    （1）逻辑回归有最优解吗? 怎么判断优化函数是凸函数？
    （2）逻辑回归会陷入局部最优解吗？
    （3）怎么求解最优解？
    （4）现在又item_id和catgory_id，在有了item_id后，逻辑回归算法在预测点击率的时候还需要catogory_id吗？
* coding: 扔n个m面的骰子（1~m），同时扔出，朝上的数字之和大于k的概率是多少？

### 华为
#### 一面
* 挑一个熟悉的项目讲一下
* 实习做的是什么?具体讲一下
* 深度学习偏多，有了解机器学习吗? 讲一下？
* coding: leetcode_1160

#### 二面
* 讲下这个论文
* 了解软件开发吗？
* 了解嵌入式开发吗？
* c++开发有做过吗？
* 计算机网络，计算机系统怎么样？
* 数据结构怎么样？给我讲一下堆吧？
* coding:和为k的最长连续子数组









