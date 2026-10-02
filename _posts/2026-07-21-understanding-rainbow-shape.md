---
layout: post
title: "理解彩虹的形状"
date: 2026-07-21
categories: [Physics_in_Everyday_Life]
---
为什么我们能看到每种颜色都呈现出完美的圆弧形状呢？

# 1.一滴水如何改变光线方向

## 球形水滴与平行光（先假设可以想象太阳光以平行光线的形式照射到空气中的水滴上）

天空中悬浮着许多近似球形的小水滴。

由于太阳距离地球非常遥远，到达水滴附近的太阳光可以近似看作相互平行。

## 折射、内部反射、再次折射（假设只经过一次反射）

阳光进入水滴时发生第一次折射；到达水滴背面后，一部分光射出，另一部分被反射回水滴内部。反射光到达水滴另一侧，再次折射并射出。主虹的代表性光路就是：折射 → 一次内部反射 → 再次折射。

在入射点附近，可以把水滴表面看成一小段平面，即图中的切线。经过入射点和球心、并与切线垂直的直线就是法线。α 是入射角，β 是折射角。

<img src="{{ '/assets/images/rainbow-shape/media/image1.png' | relative_url }}" style="width:4.95417in;height:3.42083in" />
<p class="image-caption">图 1：主虹光线在球形水滴中的传播路径。光线进入水滴时发生折射，经过一次内部反射后，再次折射离开水滴；α和β分别为入射角和折射角，均以法线为基准。作者绘制。</p>


## 斯涅尔定律

光线斜着从一种介质进入另一种介质时，传播方向会发生改变，这种现象叫作折射。入射角与折射角满足：

当光线从介质1进入介质2时：n₁ sin α= n₂ sin β

其中：n₁是介质1的折射率，n₂是介质2的折射率，α是入射角，β是折射角。空气的折射率约为 1，水的折射率约为 1.33，因此：β= arcsin(sin α÷n<sub>水</sub>)

由于水的折射率更大，所以 β\<α，光线进入水滴后会向法线偏折。

## 总偏转角 D(α)

光线经过两次折射和一次内部反射后，最终出射方向相对于原来入射方向的总转向角，它随入射角α变化，因此写作 D(α)。

<img src="{{ '/assets/images/rainbow-shape/media/image2.png' | relative_url }}" style="width:5.55069in;height:3.96458in" />
<p class="image-caption">图 2：主虹光线总偏转角 D(α) 的几何推导。光线在球形水滴中经历两次折射和一次内部反射。作者绘制。</p>

<img src="{{ '/assets/images/rainbow-shape/media/image3.jpeg' | relative_url }}" style="width:3.23056in;height:3.23056in" />
<p class="image-caption">图 3：D(α)的函数图</p>


# 2.一滴水为什么会产生明显的彩色光

从图中可以看出，D(α) 存在最小值，最小值附近的光线集中，不同颜色出现在不同观察角度。

I<sub>1</sub>,I<sub>2</sub> ：同样宽的入射角范围。

J<sub>1</sub>,J<sub>2</sub>：对应的出射偏转角范围。

如图，红色线条集中，金色线条散开。

<img src="{{ '/assets/images/rainbow-shape/media/image4.png' | relative_url }}" style="width:5.76806in;height:2.78333in" />
<p class="image-caption">图 4：偏转角极小值与光线的集中。相同大小的入射角区间I1和I2 ，αₘ 附近的I1只对应很小的偏转角范围J1，因此红色线条出射后更加集中，也更明亮。作者绘制。</p>

<img src="{{ '/assets/images/rainbow-shape/media/image5.png' | relative_url }}" style="width:5.76806in;height:3.02361in" />

# 3.无数水滴为什么组成圆弧

D(α) 存在最小值，最小值附近的光线集中，那么太阳光偏转的方向为这种状态下的D(α)，更容易被我们看到。

<img src="{{ '/assets/images/rainbow-shape/media/image6.jpeg' | relative_url }}" style="width:4.16667in;height:3.05139in" alt="Graph" />
<p class="image-caption">图 5：主虹的观察角约为42.5°。来源：Plus Magazine，“Maths behind the rainbow”</p>


<img src="{{ '/assets/images/rainbow-shape/media/image7.png' | relative_url }}" style="width:5.76806in;height:2.16319in" />

# 4. 属于你自己的彩虹

彩虹的几何结构还表明，你所看到的每一道彩虹都只属于你一个人，站在你旁边的人所看到的彩虹，其实源自另一组水滴，因此那也是一道不同的彩虹。

有时候，如果运气好的话，你还可以在主彩虹的上方看到第二道、稍微暗淡一些的彩虹。第二道彩虹是由于光线在水滴中发生了两次反射而形成的。

<img src="{{ '/assets/images/rainbow-shape/media/image8.jpeg' | relative_url }}" style="width:4.16667in;height:3.70486in" alt="Graph" />
<p class="image-caption">图 6：笛卡尔关于主虹与副虹形成的示意图，出自《气象学》第八篇“论彩虹”（1637）</p>


<img src="{{ '/assets/images/rainbow-shape/media/image9.jpeg' | relative_url }}" style="width:5.75972in;height:4.32014in" alt="IMG_20210526_181035" />
<p class="image-caption">图 7：主虹。作者摄于北京，2021年5月</p>


<img src="{{ '/assets/images/rainbow-shape/media/image10.jpeg' | relative_url }}" style="width:5.75972in;height:4.32014in" alt="IMG_20210526_181131" />
<p class="image-caption">图 8：主虹与副虹。作者摄于北京，2021年5月</p>


从理论上来说，确实有可能出现由水滴中的三次、四次或更多次反射而形成的彩虹现象。

参考资料：

[Maths behind the rainbow \| plus.maths.org](https://plus.maths.org/rainbows)

René Descartes, Les Météores, “Discours huitième: De l’arc-en-ciel”, 1637.
