---
sort: 8
---

# 核信息获取与处理 Chapter NEW

## Chapter IV 辐射探测器

#### 1. 结合所学，试定性分析，用一块塑料闪烁体配以光电倍增管组成的探头，测量到的 0.662 MeV γ 谱形状和 NaI(Tl)测到的有何不同？

由于塑料闪烁体有效原子序数 Z、密度 ρ 及发光效率均低于 NaI(Tl)闪烁晶体，对测得的 0.662MeVγ 射线谱的形状，其总谱面积相应的计数、峰总比、全能峰的能量分辨率均比 NaI(Tl)闪烁晶体差，甚至可能没有明显的全能峰。

#### 2. 试解释 0.662 MeV γ NaI(Tl)探头能量分辨率优于 BGO 闪烁探测器的原因。两者 对 γ 的探测效率相差很大，为什么？

NaI(Tl)闪烁探测器的能量分辨率优于 BGO 闪烁探测器是由于前者的发光效率明显优于后者，BGO 仅为 NaI(Tl)的 8%。而后者的密度和有效原子序数则优于前者。

---

## Chapter IX 核数据处理

### A. 简答题

1. 核辐射测量数据特征：随机性（被测对象 测量过程）局限性 混合型 空间性

2. 数据分类：测量型计数型级序型状态型名义型精度：精密度正确度准确度

3. 统计误差：核辐射测量中，待测物理量本身就是一个随机变量。准确值为无限次测量的平均值，实际测量为有限次，把样本的平均值作为真平均值，因此存在误差。

4. 变量分类：（原始组合变换）变量

5. 误差来源：（设备方法人员环境被测对象）误差

6. 误差分类：系统误差随机误差统计误差粗大误差

7. 放射性测量统计误差的规律

   答：各次测量值围绕平均值涨落 二项分布 泊松分布 高斯分布

8. 精度的计算，提高测量精度的方法？

   答：

   采用灵敏度高的探测器增加放射源强度增加测量次数延长测量时间减少测量时本底计数

9. 放射性测量中的统计误差与一般测量的误差的异同点？

   答：

   不同点：测量对象是随机的，核衰变本身具有统计性，放射性测量数据间相差可能很大。测量过程中存在各种随机因素影响。

   相同点：测量都存在误差

10. 样本的集中性统计量？答：算术平均值几何平均值中位数众数（最大频数）

11. 样本的离散性统计量？答：极差方差变异系数或然系数算术平均误差

12. 单变量的线性变换方法？答：1.标准化变换2极差变换3均匀化变换4均方差变换

13. 单变量的正态化变换方法？答：标准化变化角度变换平方根变换对数变换

14. 数据网格化变换的目的？答：1把不规则的网点变为规则网点2网格加密

15. 教据网格变换的方法？

    答：

    1.插值法（拉格朗日插值三次样条插值距离导数法方位法）

    2.曲面拟合法（趋势面拟合法趋势面和残差叠加法加权最小二乘拟合法）

16. 边界扩充的方法有哪些答：拉格朗日外推法余弦尖灭法偶开拓法直接扩充法补零法

17. 核数据检验目的：1.帮助检査测量系统的工作和测量条件是否正常和稳定，判断测量除统计误差外是否存在其它的随机误差或系统误差2.确定测量数据之间的差异是统计涨落引起的，还是测量对象或条件确实发生了变化引起的

18. 变量选择的数学方法：几何作图法（点聚图数轴）相关法（简单相关系数逐步回归分析秩相关系数）秩和检验法

### B. 问答题

1. **谱光滑的意义是什么？方法有哪些？**

   答：

   一、**意义**

   1. 由于核衰变及测量的统计性，当计数较小时，计数的统计涨落比较大，计数最多的一道不一定是高斯分布的期望，真正峰被湮没在统计涨落中
   2. 为了在统计涨落的影响下，能可靠的识别峰的存在，并准确确定峰的位置和能量，从而完成定性分析，就需要谱光滑
   3. 由于散射的影响，峰边界受统计涨落较大，需要谱光滑

   二、**方法**

   算术滑动 平均法 重心法 多项式最小二乘法 其他（傅里叶变换法）

2. 峰面积计算的意义和方法？答：1）峰面积的计算是定量分析的基础。2）知道了特征峰的 净峰面积，就可以计算目标元素的含量线性本底法 （科沃尔 沃森 Sterlinski）峰面积法 单峰 曲面拟合法

3. 谱的定性分析、定量分析的内容。答：定性：确定产生放射性的核素或元素 定量：峰边 界的确定 峰面积计算 重锋分析 含量计算

4. 核辐射测量特点：核辐射是核衰变的产物 核辐射的能量具有特征性 核素的含量与特征辐 射的强度存在正比关系

5. 蒙特卡罗方法:是以概率统计理论为基础，通过随机模拟统计试验来得出某事件发生的频率或随机变量的数学期望（算术平均值），从而求解数学物理工程技术问题近似解的数值方法。 随机模拟：对客观世界中的随机现象（原子核的衰变、射线与物质的相互作用等）用计算机从 数量上进行“模仿”“仿真”，以求出某些必要的参数或物理量。

6. 蒙特卡罗法：优点 1）能比较逼真地描述具有随机性质的事物的特点及物理实验过程，它 从实际问题本身出发，而不从方程或数学表达式出发，直观、形象。2）受几何条件限制小（可 以多维）。3）收敛速度与问题的维数无关。4）具有同时计算多个方案与多个未知量的能力。5） 误差容易确定，程序构造简单，易于实现。缺点 1）收敛速度慢，对于维数少的问题，不如其 它方法好。若要提高一个数量级，试验次数 N 需要增加两个数量级 2）误差具有概率性。蒙特 卡罗方法的误差为概率误差

### C. 计算题

![ch-new-cal](https://z3.ax1x.com/2021/07/08/ROX5nA.png)

---

## Chapter X 信号与系统补充知识

#### 1.对“信号”的分析工作主要包括

1. 信号的建模。将现实生活中遇到的各种物理信号通过数学方法抽象为一个数 学表达式，即“数学建模”，其目的是将物理信号变成可以“纸上谈兵”的数学函 数。
2. 信号的分解与组合。将一个信号分解为其他信号的线性组合形式，或者说， 用一组信号的线性组合去表达另一个信号。

#### 2. 什么是信号？

信号是消息的表现形式，消息则是信号的具体内容。

#### 3. 什么是系统？

系统是物理器件的集合，对给定的信号做出反应而产生出另外的信号。系 统其实就是一个信号转换器。

#### 4. 信号的分类

 函数自变量数目：一维信号和多维信号

函数自变量取值的连续性和离散性：连续时间信号和离散时间信号 

函数周期性与否：周期信号和非周期信号
