---
sort: 3
---

# 核信息获取与处理 Chapter 4

## 4.1 名词解释

### 4.1.1 原电离（原初电离）

入射粒子和气体分子**直接作用**产生的电离对数目。

### 4.1.2 次级电离

电离产生的次级粒子**再次和气体分子作用**产生的电离对数目。

### 4.1.3 能量分辨率

$$ \varepsilon = \frac{\Delta E}{E} = \frac{2.35\sigma}{E} = \frac{全能峰半高全宽\ \Delta E(FWHM)}{全能峰峰位\ E} \tag{4.1}$$

若以 $$\sigma$$ 标记高斯分布的标准误差，则 $$\Delta E = 2.35\ \sigma$$。

### 4.1.4 本征半导体和掺杂半导体

+ **本征半导体**

  理想的**不含杂质的半导体**称为本征半导体，导带上的电子 数目严格等于满带上的空穴数目，n = p 。

+ **掺杂半导体**

  某些杂质和缺陷对半导体的电子性质有着强烈的影响。在化合物半导体中一种组分对化学计量比的欠缺会起到杂质一样的作用，这种半导体称为欠缺半导体(也有人称之杂质半导体)，有意识地把杂质加入半导体称为掺杂。这种半导体也被成为掺杂半导体。

### 4.1.5 半导体探测器的死层

粒子进入探测器灵敏区之前通过的非灵敏区叫**窗**或**死层**

### 4.1.6 量能器

高能物理实验研究需要精确测量实验中基本粒子衰变的产物或次级粒子的能量，测量粒子能量的探测器称为量能器。（Calorimeter）

### 4.1.7 取样型量能器

与全吸收型量能器并称为电磁量能器。取样型量能器由取样计数器与吸收体交迭而成。

> 采样量能器中将使粒子发射簇射的材料和吸收粒子发射出来的能量的材料分开设置。通常这两种材料会分层相间放置，就像三明治一样。采样量能器可以使用不同的材料来满足实验中不同的需求。例如说，多种材料的其中一种可以选择密度很大的材料，这些材料与粒子的相互作用强，是很好的吸收体，即使这些材料不适合测量能量，也可以用另外一种材料的性能来补充。这种量能器的缺点是只能看到粒子簇射的一部分而不能完整地测量整个簇射，所以探测精度相对较低。
>
> -- Wikipedia "量能器（粒子物理）"

### 4.1.8 强子簇射

> There are two basic types of showers. *Electromagnetic showers* are produced by a particle that interacts primarily or exclusively via the [electromagnetic force](https://en.wikipedia.org/wiki/Electromagnetic_force), usually a [photon](https://en.wikipedia.org/wiki/Photon) or [electron](https://en.wikipedia.org/wiki/Electron). *Hadronic showers* are produced by [hadrons](https://en.wikipedia.org/wiki/Hadron) (i.e. [nucleons](https://en.wikipedia.org/wiki/Nucleon) and other particles made of [quarks](https://en.wikipedia.org/wiki/Quark)), and proceed mostly via the [strong nuclear force](https://en.wikipedia.org/wiki/Strong_nuclear_force).

![Particle_Shower](https://z3.ax1x.com/2021/07/08/ROXhXd.png)

> The physical processes that cause the propagation of a hadron shower are considerably different from the processes in electromagnetic showers. About half of the incident hadron energy is passed on to additional secondaries. The remainder is consumed in multiparticle production of slow pions and in other processes. The phenomena which determine the development of the hadronic showers are: hadron production, nuclear deexcitation and pion and muon decays. Neutral pions amount, on average to 1/3 of the produced pions and their energy is dissipated in the form of electromagnetic showers. Another important characteristic of the hadronic shower is that it takes longer to develop than the electromagnetic one. This can be seen by comparing the number of particles present versus depth for pion and electron initiated showers. The longitudinal development of hadronic showers scales with the nuclear interaction length:
>
> $$ \lambda = \frac{A}{N_A\sigma_{abs}} $$
>
> The lateral shower development does not scale with $$\lambda$$.

---

## 4.2 填空题

### *4.2.1 

**带电粒子通过气体介质时，在其路径上与气体介质原子和分子发生直接碰撞产生的电子-离子对被称为原电离。**

### *4.2.2 

**带电粒子在外电场作用下会发生扩散、漂移、电子吸附以及复合过程，其中漂移运动对总电离的收集是有利的，是气体探测器所需要的。**

### 4.2.3 

在气体探测器中，雪崩倍增过程起着十分重要的作用，其输出信号大小与粒子在气体中沉积的能量之间具有正比性。

### 4.2.4 

为了操作方便，通常正比计数器的工作气体以惰性气体为主要成分。

### *4.2.5 

**带电粒子或 γ 射线入射到闪烁体内，使得闪烁体内的原子(分子)发生电离、激发，在退激过程中发光，人们通常称之为荧光。**

### 4.2.6 

闪烁探测器由闪烁体、光探测器件和相应的电子学组成。

### 4.2.7 

有机闪烁体探测器常应用的方法是采用铝薄膜反射层较松的包装，构成全反射 和镜反射的混合方法，既保持了快脉冲输出又尽可能得到高的光收集效率。

### 4.2.8 

在外电场作用下，电子可以从外电场中吸收能量跃迁到未被电子占据的能级中 去，形成电流，起导带作用，这种能带称为导带。

### *4.2.9 

**至少写成四种 p-n 结的形成方法：扩散法、表面位垒法、离子注入法、外延法、全耗尽法。**

### 4.2.10 

切伦科夫计数器由切伦科夫辐射体、光的传播和收集系统以及光探测器三部分组成。 

### 4.2.11

穿越辐射的产生与介质的瞬间极化密切相关。

### 4.2.12 

通常选用充 Xe 的正比室作为穿越辐射 X 射线探测器。

### 4.2.13 

从入射粒子与量能器物质的主要物理过程来看，量能器可分为电磁量能器和强子量能器两类。

### 4.2.14 

量能器从结构上可分为全灵敏型(均匀介质)和取样型两类。

### 4.2.15 

取样型量能器由簇射介质与探测器灵敏层相间堆砌而成，入射粒子在簇射介质中产生簇射，但不给出信号。簇射的信号由位于簇射层之间的探测器灵敏层给出。

### 4.2.16 

强子簇射的发展主要以核相互作用为基础，簇射发展的大小由核相互作用长度控制。

### 4.2.17 

电磁簇射的发展主要以电磁相互作用为基础，簇射发展的大小由物质辐射长度控制。

### 4.2.18 

强子量能器常用的吸收体是 Fe 或 Cu,，此处 Fe 的作用往往集吸收体、结构支 架和提供磁场回路的功能为一身。

### 4.2.19 

取样量能器通常采用高 Z 材料作为吸收介质。电磁量能器中常采用高 Z、短辐射长度的铅作为吸收体以压缩体积。强子量能器常用的吸收体是 Fe 或 Cu,为了“补偿”也有添加低 Z 含 H 的材料或裂变材料 238U 的，此处 Fe 的作用往往集吸收体、 结构支
架和提供磁场回路的功能为一身。取样灵敏介质都是低 Z 物质。

### 4.2.20 

量能器有两种趋势，一是对强子量能器“补偿”将成为标准形式，二是存在将电磁量能器与强子量能器组合为一个整体的可能性。

---

## 4.3 简答题

### 4.3.1 粒子物理实验中一个“理想的”探测器，应当具有哪些良好性能？

1. 能覆盖整个立体角；

2. 能探测、显示粒子径迹和识别所有粒子(质量和电荷)；

3. 能测量粒子的动量和能量；

4. 具有快速响应能力而无任何死时间。

实际上，由于工艺和技术、经费及空间的限制，一个实际的粒子探测器很难做到如此完善与“理想”。

### 4.3.2 影响光电倍增管输出线性的主要原因？ 

1. 入射光强超过一定数值时，光阴极材料的光电转换趋于饱和；

2. 高压使用过高，脉冲信号太大，电子群的空间屏蔽效应，造成后几级打拿级间的电场下降，使得后到的电子增益下降。

### 4.3.3 简述硅微条探测器的特点。

+ 优点：

1. 非常好的位置分辨率；

2. 很高的能量分辨率；

3. 很宽的线性范围；

4. 非常快的响应时间；

5. 体积可做得很小。

+ 缺点：

对辐照损伤比较敏感，如果受到强辐射其性能将变差。

### 4.3.4 切伦科夫辐射的物理机制

从经典电磁理论，当带电粒子通过介质时，由于电磁相互作用，它能使介质中的原子或分子发生瞬间极化。当粒子通过后，这些被极化的原子或分子立即被退极化，退极化能量以电磁辐射形式发射出来。由于这些电磁辐射之间的相干性，在一定方向则得到加强，从而产生切伦科夫辐射。

### 4.3.5 简述阈式与微分式切伦科夫探测器如何探测粒子？

+ 阈式切伦科夫计数器是探测速度超过切伦科夫辐射阈速度的带电粒子的探测器，阈速度由辐射体的折射率决定；

+ 微分式切伦科夫探测器不仅利用切伦科夫阈速度之外，还可以通过测量切伦科夫角来鉴别粒子。

### 4.3.6 穿越辐射的物理机制

### 4.3.7 量能器的重要特性（8 选 5）

### 4.3.8 电磁簇射横向分布的原因有哪两个？

### 4.3.9 阈式与微分式切伦科夫探测器用什么探测粒子？

### 4.3.10 为了适应新的物理实验的需要，对量能器有哪些基本要求？

1. 好的能量分辨率和线性响应；

2. 良好的空间分辨；

3. 能承受高的计数率；

4. 覆盖立体角大，密封性好；

5. 抗辐照能量强，这一点对高亮度加速器十分重要；

6. e/π/μ 分辨能力强。

---

## 4.4 论述题

### 4.4.1 由下图分析气体探测器中收集的电荷与外加电场的关系。

### 4.4.2 为什么一些辐射探测器把半导体 p-n 结耗尽层作为其灵敏区？

### 4.4.3 由电磁粗设的简单图像描述一下电磁簇射的过程。

### 4.4.4 电磁簇射与强子簇射的区别。

1. 强子簇射的发展主要以核相互作用为基础，因而簇射发展的大小由核相互作用长度控制。强子簇射的纵向深度和横向宽度都比电磁簇射大；

2. 强子簇射中有一部分能量损失是不可测量的，这部分能量包括强子簇射发展过程中的中微子和高能 μ 子可能逸出的那部分能量，以及从核场中释放核子时所需的结合能；

3. 来源于在强子簇射沉积的能量中有相当部分被非相对性论粒子即质子和中子所携带；

4. 最关键的区别是有相当大一部分能量被非电离粒子，即核蒸发过程产生的软中子(几 MeV)所携带。

### 4.4.5 对强子量能器进行补偿的途径有哪些？

有两条途径可对强子量能器进行补偿：提高 $$ \epsilon_h $$ 或是压低 $$ \epsilon_e $$:

1. 提高 $$ \epsilon_h $$ 的办法是使探测器对核激发的产物，如中子、低能光子更灵敏；

2. 利用电磁簇射中软光子能量沉积的特点压低量能器对电磁成分的响应，即降低 $$ \epsilon_e $$，在能量小于 1 MeV 时，光电效应是主要的能损机制；

3. 最重要的是可以利用中子的响应，特别是含 H 的灵敏物质中的响应，来控制 e/h 值；

总之，量能器的补偿不仅限于 238U 量能器，或采用 238U 吸收层。吸收物质和灵敏层对 e/h 值都有影响。在取样量能器中，改变取样比适当选取量能器的参数可以获得很好的补偿。而均匀介质量能器无法进行这种补偿。

---

## 4.5 计算题

### 4.5.1

1. **description**

   求 1 cm 厚的 $$Ar$$(70%) 和 $$C_4H_{10}$$(30%) 混合气体的 $$N_p$$ 和 $$N_T$$。

2. **solution**

   混合物原则：

   $$ N_{total} = \frac{\Delta E}{W_i} = \frac{\frac{dE}{dx}\cdot \Delta x}{W_i} \tag{4.1} $$

   其中，$$ \Delta x = 1\ cm $$

   $$ \frac{dE}{dx} = \frac{MeV\cdot cm^2}{g} $$，将其转化为 $$ dE $$，则有 $$ \frac{MeV\cdot cm^2}{g}\cdot cm $$

   $$ \rho = \frac{g}{cm^3} $$，则 $$ N_t = \frac{\frac{dE}{dx}\cdot \Delta x\cdot \rho}{W_i} $$

   对于 $$N_p$$，查表，混合气体权重加权即得。
   
   那么对于上文中提到的 1 cm 厚的 $$Ar$$(70%) 和 $$C_4H_{10}$$(30%) 混合气体，其 $$N_p$$ 和 $$N_T$$ 有：

   $$ \begin{align} N_p &= n_{p,Ar}\cdot c_{Ar} + n_{p,C_4H_{10}}\cdot c_{C_4H_{10}} \\ &= 24.3\times 0.7 + 84\times 0.7 \\ &= 42。21\ (i.p./cm) \end{align} $$

   $$ \begin{align} N_T &= \displaystyle\sum_{i=1}^2 \frac{\frac{dE}{dx_i}\cdot \Delta x\cdot c_i\cdot p_i}{W_i} \\ &= \frac{1.52\times10^6\times1\times0.7\times1.78\times10^{-3}}{26} + \frac{2.25\times10^6\times1\times0.3\times2.67\times10^{-3}}{23} \\ &= 151.202\ (i.p./cm) \end{align} $$