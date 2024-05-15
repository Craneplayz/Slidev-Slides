---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: image.png
# some information about your slides, markdown enabled
title: Paleotemp
info: |
  Hello World
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
transition: slide-left
mdc: true
hideInToc: true
---
# 古温度指标：氧同位素

Paleo-temperature Proxies: Oxygen Isotopes

许智翔

15 May, 2024

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layoutClass: gap-16
hideInToc: true
---

# 目录

<Toc minDepth="1" maxDepth="2"></Toc>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---

# 古温度指标
Paleo-Temperature Proxies

<div class="flex flex-col items-center">
      <img src="table_summary.png" class="h-96 rounded-lg shadow-md">
      <span class="text-sm text-slate-300">(Lea, 2014)</span>
</div>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# 前提假设
Background Information

理论基础：碳酸盐矿物中的氧同位素存在热力学分馏 (thermodynamic fractionation)，这使得碳酸盐中

$$
\delta\ce{^18O} = \cfrac{\ce{^{18/16}O}_\text{sample}}{\ce{^{18/16}O}_\text{standard}} - 1
$$

值比海水中大约 +30‰

上述热力学分馏与温度成对数关系，在海洋温度为-2至 30°C 的范围内，其斜率为每摄氏度 -0.20‰ 至 0.27‰

这与热力学的预测相吻合，由于氧同位素的分馏是热力学现象，所以相对Robust而被其他次要动力学因素影响较小

对于钙质生物（有孔虫、单细胞浮游动物、底栖生物）而言，氧同位素信号同样相当Robust，惟其较容易受到个体发育差异 (ontogenetic variation) 和海水中 $\ce{CO3^2-}$ 离子浓度的影响

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
layout: center
transition: slide-up
class: text-center
---

# 氧同位素比在古海洋研究中应用广泛
Background Information


### 能够通过质谱仪准确测量
<br/>

### 对次要因子响应不大 <span class="text-base text-stone">（至少在年轻的沉积物来说是如此的）</span>

<br/>

### 相关记录可复现性强

<br/>

### 充分展现气候的变化性

<br/>

### 在年代地层学有重要应用

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
layout: default
---
# 质谱分析
Mass Spectrometry

<div class="flex justify-evenly items-center gap-x-4">
  <div class="flex flex-col">
      <img src="mass1.png" class="h-70 rounded-lg shadow-md">
      <span class="text-sm text-slate-300">质谱仪结构示意图</span>
  </div>
  <div class="flex flex-col">
      <img src="mass2.png" class="h-70 rounded-lg shadow-md">
      <span class="text-sm text-slate-300">质谱</span>
  </div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="王大勇，普通物理(I) PPT" />

---
transition: slide-up
level: 1
---

# 限制
Complications

碳酸盐固体中测得的氧同位素既包括了热力学分馏的信号，也包括了海水中 $\ce{CO3^2-}$ 离子沉淀时的分馏，  
海水中的 $\delta\ce{^18O}$ 反映了两个信息：

### <span class="text-blue">海水中 $\delta\ce{^18O}$ 的平均值</span>

受大陆冰盖大小变化（$10^4$到$10^5$年尺度）和海水与海床的玄武岩间相互作用（$10^7$到$10^8$年尺度）因素决定

### <span class="text-blue">蒸发-降雨平衡 (Evaporation-Precipitation Balance, E-P)</span>

蒸发-降雨平衡使得海洋中的不同水体的氧同位素产生变化。由于海洋中的盐度(salinity)也与E-P有关，所以这一个影响因子也被是“盐度因子(salinity factor)”，氧同位素与盐度在统计上存在相关性。然而由于降雨带来的淡水的同位素组成变化大，上述相关性在不同海域相差较大。

上述两个因素为氧同位素的信号引入了不确定性

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
level: 1
---

# 生物因素
Biological Factors

不同种类的有孔虫在海洋中占据不同的生态位（表层水、浅层海水、温跃层、底栖）

这使得可以通过有孔虫测得水体中的不同部分氧同位素的信号

然而，许多有孔虫种类会在垂向上迁移，使得相关信号可能经过复合

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
level: 1
---
# 古温度方程式
Paleo-Temperature Equation

前人对使用有孔虫进行氧同位素信号重建提出了一些校正公式，如：
- 依据其他生物体 (Epstein et al., 1953)
- 依据培养 (Bemis et al., 1998; Eres and Luz, 1983)
- 依据岩芯顶部校准 (Shackleton, 1974)

<br>

这些校正公式的形式多为多项式

$$
T = a + b(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water}) + c(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water})^2
$$

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
hideInToc: true
---
# 古温度方程式
Paleo-Temperature Equation

$$
T = a + b(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water}) + c(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water})^2
$$

- $T$：温度，单位为°C
- $\delta\ce{^18O}$ ：氧同位素分馏，单位为‰，以V-PBD量表为标准
- $a$ ：方解石和海水不存在分馏时的温度
- $b$ ：斜率 —— 单位温度下的氧同位素信号变化量
- $c$ ：曲率，有时会被省略，如果不为零，这代表斜率可变

<br/>

> <span class="text-amber"> **Vienna Pee Dee Belemnite, V-PDB**</span>  
> PDB是美国南卡罗来纳州白垩系皮狄组(Pee Dee)地层内拟箭石(_Belemnitella_)的碳氧同位素丰度比，可用作碳同位素的国际统一标准。该标准后来改良为Vienna PDB (Coplen, 1994)。

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
hideInToc: true
---
# 古温度方程式
Paleo-Temperature Equation

$$
T = a + b(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water}) + c(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water})^2
$$

Urey (1947) 指出斜率$b$大小应该与海水温度成负相关，因为温度降低时，同位素分馏效应增大

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
hideInToc: true
---
# 古温度方程式
Paleo-Temperature Equation

对于<span class="text-red">**温暖水体**</span>的测温，Bemis et al. (1998) 提出了基于(_Orbulina universa_)的校正公式：

$$
T = 16.5 - 4.80(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water})
$$

<br>

对于<span class="text-blue">**寒冷水体**</span>和部分<span class="text-emerald">**底栖生物**</span>，Shackleton (1974) 在 O'Neil et al. (1969)的基础上提出了另一校正公式：

$$
T = 16.9 - 4.38(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water}) + 0.1(\delta\ce{^18O}_\text{calcite} - \delta\ce{^18O}_\text{water})^2
$$

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
hideInToc: true
---
# 古温度方程式
Paleo-Temperature Equation

<div class="flex flex-col items-center">
      <img src="table_oxy.png" class="h-96 rounded-lg shadow-md">
      <span class="text-sm text-slate-300">(Lea, 2014)</span>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
hideInToc: true
---
# 次要因子
Secondary Effects

有孔虫壳体距离理想的氧同位素平衡偏移了多少？

研究方法：进行无机实验，并将实验获得的数据和有孔虫校正公式进行比较

针对各种因素的比较识别出了下列偏移

- 底栖种的未知生命效应 (vital effects) (Duplessy et al., 1970)
- 光对共生藻的影响 (Bemis et al., 1998; Spero and Lea, 1993)
- 个体发育影啊 (Spero and Lea, 1996)
- 海洋中碳酸根离子浓度 (Spero et al., 1997)
- 与配子相关的方解石形成 (gametogenic calcite) (Duplessy et al., 1981) 

部分上述偏移对 $\ce{Mg}$/$\ce{Ca}$ 古温度指标也有影响，对于上述偏移机制的更多研究，有助于我们更好地校正古温度指标

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
hideInToc: true
---
# 后期成岩作用
Diagenesis

- 在第四纪的时间尺度下，最大的变质现象是部分有孔虫壳体的溶解，该现象一般发生在海床，或不同沉积物的界面之间
- 这使得在深层、溶解作用强烈的沉积物中的有孔虫壳体 $\delta\ce{^18O}$ 值升高 $0.2 ‰ \space \text{km}^{-1}$，  
称为部分溶解偏差 (partial dissolution bias)
- 可能是因为壳体中 $\delta\ce{^18O}$ 为负的组分流失了
- 在更大的时间尺度，在表述成岩作用的时候也需要考虑初生方解石的逐渐替换
- Pearson et al. (2001) 发现与深层埋藏的开阔大洋序列中的有孔虫壳体相比，部分特异埋藏在不透水的黏土沉积中的有孔虫壳体 $\delta \ce{^18O}$ 值更负，指示更高的海水温度
- Kozdon et al. (2021) 基于离子微探针分析(ion microprobe analysis) 建议应选取后期变质作用不那么强烈的样本

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
transition: slide-up
---
# 往深时拓展
Expanding to Deep Time

- 显生宙底栖有孔虫的 $\ce{^18O}$ 是通过地球化学手段去还原古气候的最大成果。

- 由于氧同位素收到温度和冰盖大小的综合影响，这两个信号基本上是半独立演化的，因此氧同位素更多反映了地球系统的演化，而不单单仅是温度这一因子

- 研究与争论聚焦在对低纬度海洋中的浮游有孔虫使用氧同位数指示深时热带海洋的温度，然而后期成岩作用的影响严重

- 以晚白垩纪至始新世的低纬度表层海水温度 (sea surface temperature, SSTs)为例，在保存状态良好的样本中测得温度为28-32°C，而在受成岩作用“污染”的样本中，则测得15-23°C

- 成岩作用影响严重的样本中，$\delta\ce{^18O}$ 值偏正，使得估计温度偏低

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="Lea, 2014" />

---
layout: two-cols
transition: slide-up
---
# 牙形石
Conodonts

- 繁盛于寒武纪至三叠纪的脊椎动物
- 具有磷灰质的齿状结构，  
称为牙形分子 (conodonts element)  
<span class="text-blue">（与牙齿不同源，为趋同演化）</span>

$$
\ce{Ca5Na_{0.14}(PO4)_{3.01}(CO3)_{0.16}F_{0.73}(H2O)_{0.85}}
$$

- 是最早拥有磷酸盐壳体的生物
- 身体柔软，仅有两具完整个体化石被发现，  
但齿状结构坚硬，齿状结构化石随处可见
- 在“金钉子”选择的生物中，牙形石是最多的一类

::right::


<div class="flex flex-col items-end">
      <div class="flex flex-col items-end">
        <img src="conodonts.png" class="h-50 rounded-lg shadow-md">
        <span class="text-sm text-slate-300">(Shutterstock)</span>
      </div>
      <div class="flex flex-col items-end">
        <img src="elements.png" class="h-50 rounded-lg shadow-md">
        <span class="text-sm text-slate-300">(Dzik, 2015)</span>
      </div>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="孙作玉，古生物学前沿 PPT" />

---
layout: two-cols
transition: slide-up
---
# 磷酸盐壳体中的氧同位素
Oxygen Isotopes in Phosphate

Longinelli (1966) 研究了现生和化石物种的生长温度和磷酸盐壳体中的氧同位素之间的关系

使用最小二乘法拟合后得到

$$
T = -90 - 4.8(\delta\ce{^18O}_\text{phosphate} - \delta\ce{^18O}_\text{water})
$$

由于各项数量级不同，难以和 $T-\ce{CO2}$ 关系直接对比，但两者斜率相近

::right::

<div class="flex flex-col items-center">
    <img src="phos1.png" class="h-96 rounded-lg shadow-md">
    <span class="text-sm text-slate-300">SMOW: Standard Mean Ocean Water</span>
</div>

<Citation src="(Longinelli, 1966)" />

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
transition: slide-up
hideInToc: true
---
# 磷酸盐壳体中的氧同位素
Oxygen Isotopes in Phosphate

将 $\delta\ce{^18O}_\text{phosphate}$ 和 $\delta\ce{^18O}_\text{calcite}$ 置于同一张图上，斜率大约为1.4

通过斜率和差值（$\delta\ce{^18O}_\text{phosphate} - \delta\ce{^18O}_\text{calcite}$），
可以得出碳酸盐和磷酸盐同时存在的体系中

$$
T = \pm 4.5 \degree \text{C}\\

\delta  = \pm 0.8 \space ‰
$$

::right::

<div class="flex flex-col items-center">
    <img src="phos2.png" class="h-90 rounded-lg shadow-md">
    <span class="text-sm text-slate-300">(Longinelli, 1966)</span>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
transition: slide-up
hideInToc: true
---
# 化石物种
Fossil Species

<div class="flex flex-col items-center">
    <img src="phos3.png" class="h-90 rounded-lg shadow-md">
    <span class="text-sm text-slate-300">(Longinelli, 1966)</span>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
layout: two-cols
transition: slide-up
hideInToc: true
---
# 化石物种
Fossil Species

Longinelli 对不同地区、不同时代的化石物种进行研究

研究对象：  
- 拟箭石(belemnite)、  
- 双壳纲(bivalves, <span class="text-stone text-sm">"pelecypods" in orginal text</span>)、  
- （少数）腕足类
- （少数）固着蛤 (rudists)、  
- （少数）甲壳类
- （少数）鱼类牙齿

::right::

<div class="flex flex-col items-end
">
    <img src="phos4.png" class="h-110 rounded-lg shadow-md">
    <span class="text-sm text-slate-300">(Longinelli, 1966)</span>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
layout: two-cols
transition: slide-up
hideInToc: true
---
# 化石物种
Fossil Species

发现以下现象：

- 地质年代越年轻的样本，其 $\delta\ce{^18O}$ 值越负。  
这可能是由于磷酸盐和地下水的氧同位素之间存在交换。  
尽管磷酸盐中的 $\ce{O}$ 与 $\ce{P}$ 之间的化学键具有很高的键能，
但这在古生代的样本中很长发生

- 淡水化石种和海生种的氧同位素构成没有差异

- 由于碳酸盐中的 $\ce{O}$ 与 $\ce{C}$ 之间的化学键键能较低，在中生代发生了碳酸盐和地下水间的同位素交换

::right::

<div class="flex flex-col items-end
">
    <img src="phos4.png" class="h-110 rounded-lg shadow-md">
    <span class="text-sm text-slate-300">(Longinelli, 1966)</span>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
layout: two-cols
transition: slide-up
hideInToc: true
---
# 化石物种
Fossil Species

### <span class="text-red">问题</span>

拟箭石化石中的磷酸盐氧同位素$\delta\ce{^18O}$值均偏正，研究者提出下列4个假设：

1. 存在生物分馏作用
2. 在固态碳酸根和磷酸根之间存在物质交换
3. 化石中存在次生磷酸盐
4. 双壳纲和腕足类化石在后期成岩过程中与地下水的同位素交换较少

::right::

<div class="flex flex-col items-end
">
    <img src="phos4.png" class="h-110 rounded-lg shadow-md">
    <span class="text-sm text-slate-300">(Longinelli, 1966)</span>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
transition: slide-up
level: 2
---
# 假设与驳斥
Hypotheses and Refutations

### 生物分馏作用
- 无法解释侏罗纪和晚白垩世的拟箭石中的差别
- 现代头足类可以在同位素平衡的情况下主动沉淀出磷酸钙和碳酸钙
- 晚白垩世的鱼类牙齿化石显示类似的氧同位素信号

<br>

### 固态碳酸根和磷酸根之间的物质交换
- 难以解释为什么相关物质交换会在拟箭石和双壳纲中发生，却产生截然相反的效应

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
transition: slide-up
level: 2
---
# 假设与驳斥
Hypotheses and Refutations

### 次生磷酸盐
- 乍看之下相当奇怪，一般化石在成岩作用中会逐渐消耗$\ce{^18O}$，古生代化石中获取的磷酸盐样本不应例外
- 需要后续研究加以论证
- 判准：如果存在次生磷酸盐，那么磷原子应该集中在拟箭石的根尖(apical canal) 和外表面上

<br>

### 双壳纲和腕足类化石与地下水同位素交换少
- 最为合理的解释，考虑交换面积 $S$ 与 质量 $M$ 之比 $\cfrac{S}{M}$
$$
\cfrac{S}{M}(\text{belemnites}) \approx 1 \\
\cfrac{S}{M}(\text{bivalves, branchippods}) \approx 10, 15
$$
- 得到化石记录佐证

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
transition: slide-up
level: 2
---
# 问题
Caveats

化石的成岩作用会使得 $\delta\ce{^18O}$ 值变负

自然假设：就是样本中 $\delta\ce{^18O}$ 值最正的反映的信号应当最为准确而接近原始海洋。

若侏罗纪海水温度和现代海洋相差不大，  
那么海洋中的 $\delta\ce{^18O}$ 应该要比现在正得多，  
推到得出氧同位素的 $\delta$ 值应当相差5-9个数量级（以‰为数量级）

#### <span class="text-red">这是相当离谱的。</span>


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
transition: slide-up
level: 2
hideInToc: true
---
# 可能解释
Possible Explanations

- 持续的埋藏（碳酸盐、磷酸盐、硅酸盐、硫酸盐）中的分馏作用  
使得海水中的 $\ce{^18O}$ 含量下降

- 氧同位素的演替主要受到  
风化作用、侵蚀作用、沉积作用以及新生水 (juvenile water)的加入影响，  
然而没有任何手段去估计新生水的贡献

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<Citation src="(Longinelli, 1966)" />

---
layout: default
---

# 参考文献

References

<div class="text-sm">

1. Lea, D. W. (2014). Elemental and Isotopic Proxies of Past Ocean Temperatures. In Treatise on Geochemistry (pp. 373–397). Elsevier. https://doi.org/10.1016/B978-0-08-095975-7.00614-8
2. Longinelli, A. (1966). Ratios of Oxygen-18: Oxygen-16 in Phosphate and Carbonate from Living and Fossil Marine Organisms. Nature, 211(5052), 923–927. https://doi.org/10.1038/211923a0
3. Pucéat, E., Joachimski, M. M., Bouilloux, A., Monna, F., Bonin, A., Motreuil, S., Morinière, P., Hénard, S., Mourin, J., Dera, G., & Quesne, D. (2010). Revised phosphate–water fractionation equation reassessing paleotemperatures derived from biogenic apatite. Earth and Planetary Science Letters, 298(1–2), 135–142. https://doi.org/10.1016/j.epsl.2010.07.034
4. WoRMS - World Register of Marine Species—Chihsienella Y.Z.Liang & R.C.Tsao, 1974. (n.d.). Retrieved April 16, 2024, from https://marinespecies.org/aphia.php?p=taxdetails&id=369470
</div>

<style>
  h1 {
      background-color: #2b90b6;
      background-image: linear-gradient(45deg, #4ec5d4 10%, #146b8c 20%);
      background-size: 100%;
      -webkit-background-clip: text;
      -moz-background-clip: text;
      -webkit-text-fill-color: transparent;
      -moz-text-fill-color: transparent;
    }
</style>

---
layout: end
class: text-center
hideInToc: true
---

# 谢谢

欢迎针对前述内容提问～

<style>
  h1 {
      background-color: #2b90b6;
      background-image: linear-gradient(45deg, #4ec5d4 10%, #146b8c 20%);
      background-size: 100%;
      -webkit-background-clip: text;
      -moz-background-clip: text;
      -webkit-text-fill-color: transparent;
      -moz-text-fill-color: transparent;
    }
</style>