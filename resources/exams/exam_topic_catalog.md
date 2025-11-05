# 历年算法综合考试题库（按考点归类）

> 说明：以下汇总覆盖 2005-2023 年历次 Honors Analysis of Algorithms 期末/资格考试中，与今年考纲重合的题目。已排除涉及形式语言/自动机等理论计算内容的题目。

## 1. 题目总览

| ID | 年份 | 题号 | 题目摘要 | 标签 |
| --- | --- | --- | --- | --- |
| 2023_P1 | 2023 | P1 | B-bounded {0,1}-IP 常数约束下的NP完备归约 | NP-Completeness |
| 2023_P2 | 2023 | P2 | 在 O(|V|+|E|) 时间比较有向游走数量是否达阈值 | Graph Algorithms |
| 2023_P3 | 2023 | P3 | 树上最大全权短缺集合动态规划 | Dynamic Programming |
| 2023_P4 | 2023 | P4 | Horn-3SAT 判定与近似保证（线性传播+期望) | Linear-Time Algorithms, Randomization |
| 2023_P5 | 2023 | P5 | 稀疏矩阵字典结构与乘积 | Hashing, Data Structures |
| 2023_P6 | 2023 | P6 | 混合排序递归比较次数 O(n log n) 证明 | Recurrence & Divide-and-Conquer |
| 2022_P1 | 2022 | P1 | 包含根的固定规模最优子树 | Dynamic Programming |
| 2022_P2 | 2022 | P2 | 数组实现栈的扩容缩容势能分析 | Amortized Analysis |
| 2022_P3 | 2022 | P3 | 递归上界与最接近0子数组求解 | Recurrence & Divide-and-Conquer |
| 2022_P4 | 2022 | P4 | 医生-药店-母亲最短路径建模 | Graph Algorithms |
| 2022_P5 | 2022 | P5 | 超图染色满足边数的随机算法 | Randomization |
| 2022_P6 | 2022 | P6 | 常数出现次数约束的3SAT归约 | NP-Completeness |
| 2021_P1 | 2021 | P1 | 带插入/删除/换位的序列比对 DP | Dynamic Programming |
| 2021_P2 | 2021 | P2 | 带颜色约束的最短路归约 | Graph Algorithms |
| 2021_P3 | 2021 | P3 | 5-平衡图着色判定与子集DP | Graph Algorithms, Dynamic Programming |
| 2021_P4 | 2021 | P4 | 逆序计数与递增三元组统计 | Recurrence & Divide-and-Conquer |
| 2021_P5 | 2021 | P5 | 随机二分图满足Hall条件分析 | Randomization |
| 2021_P6 | 2021 | P6 | 三分变量3SAT NP完全证明 | NP-Completeness |
| 2020_P1 | 2020 | P1 | 三车辆负载平衡 DP | Dynamic Programming |
| 2020_P2 | 2020 | P2 | 2-3树与2-6树的摊还分裂合并 | Balanced Trees & Augmentation, Amortized Analysis |
| 2020_P3 | 2020 | P3 | DAG 红节点覆盖路径 | Graph Algorithms, Dynamic Programming |
| 2020_P4 | 2020 | P4 | 带返回路径的安保预算最小化 | Graph Algorithms |
| 2020_P5 | 2020 | P5 | 随机图删边构造无短环 | Randomization |
| 2020_P6 | 2020 | P6 | 3LIN 约束满足 NP完全证明 | NP-Completeness |
| 2019_P1 | 2019 | P1 | 堆中小于阈值的元素数量判定 | Data Structures, Linear-Time Algorithms |
| 2019_P2 | 2019 | P2 | 最大子数组和线性时间算法 | Linear-Time Algorithms |
| 2019_P3 | 2019 | P3 | 3-超图独立集 NP完全 | NP-Completeness |
| 2019_P4 | 2019 | P4 | 差分约束系统解的图算法 | Graph Algorithms |
| 2019_P5 | 2019 | P5 | 球入箱最大负荷概率估计 | Randomization |
| 2019_P6 | 2019 | P6 | 二叉树叶子对最大祖先权值 | Dynamic Programming |
| 2018_P1 | 2018 | P1 | Prim风格MST正确性证明 | Graph Algorithms |
| 2018_P2 | 2018 | P2 | 颜色交替游走存在性判定 | Graph Algorithms |
| 2018_P3 | 2018 | P3 | RNA折叠最大配对 | Dynamic Programming |
| 2018_P4 | 2018 | P4 | 扩展图直径对数界证明 | Graph Algorithms |
| 2018_P5 | 2018 | P5 | 随机图最大独立集上界 | Randomization |
| 2018_P6 | 2018 | P6 | 固定比例顶点覆盖 NP完全 | NP-Completeness |
| 2017_P1 | 2017 | P1 | 双栈实现队列并支持Find-Min | Data Structures, Amortized Analysis |
| 2017_P2 | 2017 | P2 | 三色分段最短路径 | Graph Algorithms |
| 2017_P3 | 2017 | P3 | 最小成本核心节点集 | Graph Algorithms |
| 2017_P4 | 2017 | P4 | 一维简单随机游走统计 | Randomization |
| 2017_P5 | 2017 | P5 | Monotone 2SAT 最小真值 NP完全 | NP-Completeness |
| 2017_P6 | 2017 | P6 | 修路高度规划动态规划 | Dynamic Programming |
| 2016_P1 | 2016 | P1 | 受限范围整数的线性时间排序 | Linear-Time Algorithms |
| 2016_P2 | 2016 | P2 | 随机3着色满足边数保证 | Randomization |
| 2016_P3 | 2016 | P3 | 买啤酒最短路 (Dijkstra 变奏) | Graph Algorithms |
| 2016_P4 | 2016 | P4 | 双层循环打印次数的精确与渐近分析 | Recurrence & Divide-and-Conquer |
| 2016_P5 | 2016 | P5 | 连续任务分段调度 DP | Dynamic Programming |
| 2016_P6 | 2016 | P6 | Non-mixed-3SAT NP完全 | NP-Completeness |
| 2015_P1 | 2015 | P1 | 冗余二进制计数器摊还成本 | Amortized Analysis |
| 2015_P2 | 2015 | P2 | Pretty good 哈希构造(通用哈希) | Hashing, Randomization |
| 2015_P3 | 2015 | P3 | 最长轨迹子序列 | Dynamic Programming, Linear-Time Algorithms |
| 2015_P4 | 2015 | P4 | 带容量限制的DAG拾石子 | Graph Algorithms, Dynamic Programming |
| 2015_P5 | 2015 | P5 | 多地铁系统出行最短费用 | Graph Algorithms |
| 2015_P6 | 2015 | P6 | Joker-3SAT NP完全 | NP-Completeness |
| 2014_P1 | 2014 | P1 | 无环先修课最小学期数 | Graph Algorithms |
| 2014_P2 | 2014 | P2 | 在线连通性与最大分量维护 | Data Structures, Amortized Analysis |
| 2014_P3 | 2014 | P3 | 字典分词可行性 | Dynamic Programming |
| 2014_P4 | 2014 | P4 | 非负/单位/双权最短路方案 | Graph Algorithms |
| 2014_P5 | 2014 | P5 | 随机图连通性的概率上界 | Randomization |
| 2014_P6 | 2014 | P6 | 3-超图顶点覆盖 NP完全 | NP-Completeness |
| 2013_P1 | 2013 | P1 | 树上最大权独立集 | Dynamic Programming |
| 2013_P2 | 2013 | P2 | 最近更大元素索引线性栈 | Linear-Time Algorithms |
| 2013_P3 | 2013 | P3 | 有向图根节点判定 | Graph Algorithms |
| 2013_P4 | 2013 | P4 | 带购物的往返最短路 | Graph Algorithms |
| 2013_P5 | 2013 | P5 | 4LIN 满足度估计与求解 | Randomization |
| 2013_P6 | 2013 | P6 | FOREST 子图 NP完全 | NP-Completeness |
| 2011_P1 | 2011 | P1 | 三角打包与带权顶点覆盖 NP完全 | NP-Completeness |
| 2011_P2 | 2011 | P2 | MST单边权更新维护 | Graph Algorithms |
| 2011_P3 | 2011 | P3 | 线性方程差分一致性判定 | Graph Algorithms |
| 2011_P4 | 2011 | P4 | 线性时间超过阈值频率检测 | Linear-Time Algorithms |
| 2011_P5 | 2011 | P5 | 保姆调度与算式最大化 DP | Dynamic Programming |
| 2010_P1 | 2010 | P1 | 随机递归期望与乘法次数分析 | Recurrence & Divide-and-Conquer, Randomization |
| 2010_P3 | 2010 | P3 | 最长回文子序列与子串 | Dynamic Programming |
| 2010_P4 | 2010 | P4 | 银价风险数据结构设计 | Balanced Trees & Augmentation, Data Structures |
| 2010_P5 | 2010 | P5 | BUOE 与 DS 的 NP完全证明 | NP-Completeness |
| 2010_P6 | 2010 | P6 | Floyd-Warshall 及双目标最短路 | Graph Algorithms |
| 2009_P1 | 2009 | P1 | DAG路径权重总和计算 | Graph Algorithms, Dynamic Programming |
| 2009_P3 | 2009 | P3 | 树中找到平衡顶点 | Graph Algorithms |
| 2009_P4 | 2009 | P4 | 森林分解与合并的摊还代价 | Data Structures, Amortized Analysis |
| 2009_P5 | 2009 | P5 | 美国式哈密顿环 NP完全 | NP-Completeness |
| 2009_P6 | 2009 | P6 | 随机割期望至少半边 | Randomization |
| 2008_P1 | 2008 | P1 | BST 高度与基本操作分析 | Balanced Trees & Augmentation, Data Structures |
| 2008_P2 | 2008 | P2 | (2,3)-SAT 满足率随机法 | Randomization |
| 2008_P3 | 2008 | P3 | 距离阈值节点割点查找 | Graph Algorithms |
| 2008_P4 | 2008 | P4 | 带字符串标签的路径搜索 | Graph Algorithms |
| 2008_P6 | 2008 | P6 | Triangle-free 集合 NP完全 | NP-Completeness |
| 2007_P1 | 2007 | P1 | 随机割至少切半数边证明 | Randomization |
| 2007_P2 | 2007 | P2 | MAX-2SAT 由顶点覆盖归约 | NP-Completeness |
| 2007_P3 | 2007 | P3 | 树结构Goodness最大化 DP | Dynamic Programming |
| 2007_P5 | 2007 | P5 | Floyd-Warshall 处理负环与扩展 | Graph Algorithms |
| 2007_P6 | 2007 | P6 | 加法电路进位计数保持 | Amortized Analysis |
| 2006_Q1 | 2006 | Q1 | k-循环有向图检测与受限最短路 | Graph Algorithms |
| 2006_Q2 | 2006 | Q2 | 支持AddValue与Merge的优先队列 | Data Structures, Amortized Analysis |
| 2006_Q3 | 2006 | Q3 | FATCHAT 满足率与 VERSAT NP完全 | Randomization, NP-Completeness |
| 2006_Q4 | 2006 | Q4 | 加权最长公共子序列变体 DP | Dynamic Programming |
| 2006_Q5 | 2006 | Q5 | 滚动哈希字符串比较结构 | Hashing, Data Structures |
| 2005_P1 | 2005 | P1 | 只读数组多数元素分治 | Recurrence & Divide-and-Conquer |
| 2005_P2 | 2005 | P2 | 递归随机过程期望 O(n) | Randomization |
| 2005_P3 | 2005 | P3 | Shuffle 子序列判定 DP | Dynamic Programming |
| 2005_P5 | 2005 | P5 | 最大收益路径 (SCC 分析) | Graph Algorithms |
| 2005_P6 | 2005 | P6 | 最大利润路径 NP完全 | NP-Completeness |

## 2. 按考点分类

### Amortized Analysis
- **2022 P2 (2022_P2)**：数组实现栈的扩容缩容势能分析
- **2020 P2 (2020_P2)**：2-3树与2-6树的摊还分裂合并
- **2017 P1 (2017_P1)**：双栈实现队列并支持Find-Min
- **2015 P1 (2015_P1)**：冗余二进制计数器摊还成本
- **2014 P2 (2014_P2)**：在线连通性与最大分量维护
- **2009 P4 (2009_P4)**：森林分解与合并的摊还代价
- **2007 P6 (2007_P6)**：加法电路进位计数保持
- **2006 Q2 (2006_Q2)**：支持AddValue与Merge的优先队列

### Balanced Trees & Augmentation
- **2020 P2 (2020_P2)**：2-3树与2-6树的摊还分裂合并
- **2010 P4 (2010_P4)**：银价风险数据结构设计
- **2008 P1 (2008_P1)**：BST 高度与基本操作分析

### Data Structures
- **2023 P5 (2023_P5)**：稀疏矩阵字典结构与乘积
- **2019 P1 (2019_P1)**：堆中小于阈值的元素数量判定
- **2017 P1 (2017_P1)**：双栈实现队列并支持Find-Min
- **2014 P2 (2014_P2)**：在线连通性与最大分量维护
- **2010 P4 (2010_P4)**：银价风险数据结构设计
- **2009 P4 (2009_P4)**：森林分解与合并的摊还代价
- **2008 P1 (2008_P1)**：BST 高度与基本操作分析
- **2006 Q2 (2006_Q2)**：支持AddValue与Merge的优先队列
- **2006 Q5 (2006_Q5)**：滚动哈希字符串比较结构

### Dynamic Programming
- **2023 P3 (2023_P3)**：树上最大全权短缺集合动态规划
- **2022 P1 (2022_P1)**：包含根的固定规模最优子树
- **2021 P1 (2021_P1)**：带插入/删除/换位的序列比对 DP
- **2021 P3 (2021_P3)**：5-平衡图着色判定与子集DP
- **2020 P1 (2020_P1)**：三车辆负载平衡 DP
- **2020 P3 (2020_P3)**：DAG 红节点覆盖路径
- **2019 P6 (2019_P6)**：二叉树叶子对最大祖先权值
- **2018 P3 (2018_P3)**：RNA折叠最大配对
- **2017 P6 (2017_P6)**：修路高度规划动态规划
- **2016 P5 (2016_P5)**：连续任务分段调度 DP
- **2015 P3 (2015_P3)**：最长轨迹子序列
- **2015 P4 (2015_P4)**：带容量限制的DAG拾石子
- **2014 P3 (2014_P3)**：字典分词可行性
- **2013 P1 (2013_P1)**：树上最大权独立集
- **2011 P5 (2011_P5)**：保姆调度与算式最大化 DP
- **2010 P3 (2010_P3)**：最长回文子序列与子串
- **2009 P1 (2009_P1)**：DAG路径权重总和计算
- **2007 P3 (2007_P3)**：树结构Goodness最大化 DP
- **2006 Q4 (2006_Q4)**：加权最长公共子序列变体 DP
- **2005 P3 (2005_P3)**：Shuffle 子序列判定 DP

### Graph Algorithms
- **2023 P2 (2023_P2)**：在 O(|V|+|E|) 时间比较有向游走数量是否达阈值
- **2022 P4 (2022_P4)**：医生-药店-母亲最短路径建模
- **2021 P2 (2021_P2)**：带颜色约束的最短路归约
- **2021 P3 (2021_P3)**：5-平衡图着色判定与子集DP
- **2020 P3 (2020_P3)**：DAG 红节点覆盖路径
- **2020 P4 (2020_P4)**：带返回路径的安保预算最小化
- **2019 P4 (2019_P4)**：差分约束系统解的图算法
- **2018 P1 (2018_P1)**：Prim风格MST正确性证明
- **2018 P2 (2018_P2)**：颜色交替游走存在性判定
- **2018 P4 (2018_P4)**：扩展图直径对数界证明
- **2017 P2 (2017_P2)**：三色分段最短路径
- **2017 P3 (2017_P3)**：最小成本核心节点集
- **2016 P3 (2016_P3)**：买啤酒最短路 (Dijkstra 变奏)
- **2015 P4 (2015_P4)**：带容量限制的DAG拾石子
- **2015 P5 (2015_P5)**：多地铁系统出行最短费用
- **2014 P1 (2014_P1)**：无环先修课最小学期数
- **2014 P4 (2014_P4)**：非负/单位/双权最短路方案
- **2013 P3 (2013_P3)**：有向图根节点判定
- **2013 P4 (2013_P4)**：带购物的往返最短路
- **2011 P2 (2011_P2)**：MST单边权更新维护
- **2011 P3 (2011_P3)**：线性方程差分一致性判定
- **2010 P6 (2010_P6)**：Floyd-Warshall 及双目标最短路
- **2009 P1 (2009_P1)**：DAG路径权重总和计算
- **2009 P3 (2009_P3)**：树中找到平衡顶点
- **2008 P3 (2008_P3)**：距离阈值节点割点查找
- **2008 P4 (2008_P4)**：带字符串标签的路径搜索
- **2007 P5 (2007_P5)**：Floyd-Warshall 处理负环与扩展
- **2006 Q1 (2006_Q1)**：k-循环有向图检测与受限最短路
- **2005 P5 (2005_P5)**：最大收益路径 (SCC 分析)

### Hashing
- **2023 P5 (2023_P5)**：稀疏矩阵字典结构与乘积
- **2015 P2 (2015_P2)**：Pretty good 哈希构造(通用哈希)
- **2006 Q5 (2006_Q5)**：滚动哈希字符串比较结构

### Linear-Time Algorithms
- **2023 P4 (2023_P4)**：Horn-3SAT 判定与近似保证（线性传播+期望)
- **2019 P1 (2019_P1)**：堆中小于阈值的元素数量判定
- **2019 P2 (2019_P2)**：最大子数组和线性时间算法
- **2016 P1 (2016_P1)**：受限范围整数的线性时间排序
- **2015 P3 (2015_P3)**：最长轨迹子序列
- **2013 P2 (2013_P2)**：最近更大元素索引线性栈
- **2011 P4 (2011_P4)**：线性时间超过阈值频率检测

### NP-Completeness
- **2023 P1 (2023_P1)**：B-bounded {0,1}-IP 常数约束下的NP完备归约
- **2022 P6 (2022_P6)**：常数出现次数约束的3SAT归约
- **2021 P6 (2021_P6)**：三分变量3SAT NP完全证明
- **2020 P6 (2020_P6)**：3LIN 约束满足 NP完全证明
- **2019 P3 (2019_P3)**：3-超图独立集 NP完全
- **2018 P6 (2018_P6)**：固定比例顶点覆盖 NP完全
- **2017 P5 (2017_P5)**：Monotone 2SAT 最小真值 NP完全
- **2016 P6 (2016_P6)**：Non-mixed-3SAT NP完全
- **2015 P6 (2015_P6)**：Joker-3SAT NP完全
- **2014 P6 (2014_P6)**：3-超图顶点覆盖 NP完全
- **2013 P6 (2013_P6)**：FOREST 子图 NP完全
- **2011 P1 (2011_P1)**：三角打包与带权顶点覆盖 NP完全
- **2010 P5 (2010_P5)**：BUOE 与 DS 的 NP完全证明
- **2009 P5 (2009_P5)**：美国式哈密顿环 NP完全
- **2008 P6 (2008_P6)**：Triangle-free 集合 NP完全
- **2007 P2 (2007_P2)**：MAX-2SAT 由顶点覆盖归约
- **2006 Q3 (2006_Q3)**：FATCHAT 满足率与 VERSAT NP完全
- **2005 P6 (2005_P6)**：最大利润路径 NP完全

### Randomization
- **2023 P4 (2023_P4)**：Horn-3SAT 判定与近似保证（线性传播+期望)
- **2022 P5 (2022_P5)**：超图染色满足边数的随机算法
- **2021 P5 (2021_P5)**：随机二分图满足Hall条件分析
- **2020 P5 (2020_P5)**：随机图删边构造无短环
- **2019 P5 (2019_P5)**：球入箱最大负荷概率估计
- **2018 P5 (2018_P5)**：随机图最大独立集上界
- **2017 P4 (2017_P4)**：一维简单随机游走统计
- **2016 P2 (2016_P2)**：随机3着色满足边数保证
- **2015 P2 (2015_P2)**：Pretty good 哈希构造(通用哈希)
- **2014 P5 (2014_P5)**：随机图连通性的概率上界
- **2013 P5 (2013_P5)**：4LIN 满足度估计与求解
- **2010 P1 (2010_P1)**：随机递归期望与乘法次数分析
- **2009 P6 (2009_P6)**：随机割期望至少半边
- **2008 P2 (2008_P2)**：(2,3)-SAT 满足率随机法
- **2007 P1 (2007_P1)**：随机割至少切半数边证明
- **2006 Q3 (2006_Q3)**：FATCHAT 满足率与 VERSAT NP完全
- **2005 P2 (2005_P2)**：递归随机过程期望 O(n)

### Recurrence & Divide-and-Conquer
- **2023 P6 (2023_P6)**：混合排序递归比较次数 O(n log n) 证明
- **2022 P3 (2022_P3)**：递归上界与最接近0子数组求解
- **2021 P4 (2021_P4)**：逆序计数与递增三元组统计
- **2016 P4 (2016_P4)**：双层循环打印次数的精确与渐近分析
- **2010 P1 (2010_P1)**：随机递归期望与乘法次数分析
- **2005 P1 (2005_P1)**：只读数组多数元素分治
