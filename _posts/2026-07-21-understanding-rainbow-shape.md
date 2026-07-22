---
layout: post
title: "理解彩虹的形状"
date: 2026-07-21 20:00:00 +0800
categories:
  - Physics_in_Everyday_Life
---
为什么我们能看到每种颜色都呈现出完美的圆弧形状呢？

# 1.一滴水如何改变光线方向

## 球形水滴与平行光（先假设可以想象太阳光以平行光线的形式照射到空气中的水滴上）

天空中悬浮着许多近似球形的小水滴。

由于太阳距离地球非常遥远，到达水滴附近的太阳光可以近似看作相互平行。

## 折射、内部反射、再次折射（假设只经过一次反射）

当阳光到达水滴表面时，一部分光被表面反射，另一部分折射进入水滴，只有少量光被吸收。进入水滴的光继续传播，到达水滴背面的水-空气界面。在这里，一部分光折射出去，另一部分在水滴内部发生反射。内部反射的光继续传播，到达水滴另一侧的表面，再由水进入空气，发生第二次折射并射出水滴。

当阳光到达水滴表面时，一部分光被表面反射，另一部分折射进入水滴，只有少量光被吸收。进入水滴的光继续传播，到达背面的水—空气界面。在这里，一部分光折射进入空气，另一部分在界面处被反射回水滴内部。反射光继续传播，到达水滴另一侧的水—空气界面，再次发生折射并射出水滴。

形成主虹的一条代表性光路可以概括为：进入水滴时第一次折射 → 在水滴背面的内表面发生一次反射 → 离开水滴时第二次折射。

光线照射到球形水滴的不同位置时，入射角并不相同。入射角是入射光线与入射点处法线的夹角。对于球形水滴，入射点处的法线就是入射点与球心的连线；切线与法线垂直，代表水滴表面在该点附近的方向。

<img src="{{ '/assets/images/rainbow/media/image1.png' | relative_url }}" />

图：主虹光线在球形水滴中的传播路径。光线进入水滴时发生折射，经过一次内部反射后，再次折射离开水滴；α和β分别为入射角和折射角，均以法线为基准。作者绘制。

## 斯涅尔定律

当光线从介质1进入介质2时：

n₁ sin α= n₂ sin β

其中：n₁是介质1的折射率，n₂是介质2的折射率，α是入射角，β是折射角。

在“空气进入水滴”的情况下：

n<sub>空气</sub> sin α = n<sub>水</sub> sin β

由于空气的折射率约为 1，因此还可以写成：

sin α = n<sub>水</sub>sin β

或：β= arcsin(sin α÷n<sub>水</sub>)

## 总偏转角 D(α)

<img src="{{ '/assets/images/rainbow/media/image2.png' | relative_url }}" />

图：主虹光线总偏转角 D(α) 的几何推导。光线在球形水滴中经历两次折射和一次内部反射。作者绘制。

<img src="{{ '/assets/images/rainbow/media/image3.jpeg' | relative_url }}" />

图：D(α)的函数图

# 2.一滴水为什么会产生明显的彩色光

从图中可以看出，D(α) 存在最小值，最小值附近的光线集中，不同颜色出现在不同观察角度。

I<sub>1</sub>,I<sub>2</sub> ：同样宽的入射角范围。

J<sub>1</sub>,J<sub>2</sub>：对应的出射偏转角范围。

红光集中，金色光线散开。

<img src="{{ '/assets/images/rainbow/media/image4.png' | relative_url }}" />

图：偏转角极小值与彩虹光线的集中。相同大小的入射角区间I1 和I2，αₘ 附近的I1 只对应很小的偏转角范围 J₁，因此红色光线出射后更加集中，也更明亮。作者绘制。

<img src="{{ '/assets/images/rainbow/media/image5.png' | relative_url }}" />

# 3.无数水滴为什么组成圆弧

D(α) 存在最小值，最小值附近的光线集中，那么太阳光偏转的方向为这种状态下的D(α)，更容易被我们看到。

<img src="{{ '/assets/images/rainbow/media/image6.jpeg' | relative_url }}" alt="Graph" />

图：主虹的观察角约为42.5°。来源：Plus Magazine，“Maths behind the rainbow”

<img src="{{ '/assets/images/rainbow/media/image7.png' | relative_url }}" />

# 4. 属于你自己的彩虹

彩虹的几何结构还表明，你所看到的每一道彩虹都只属于你一个人，站在你旁边的人所看到的彩虹，其实源自另一组水滴，因此那也是一道不同的彩虹。

有时候，如果运气好的话，你还可以在主彩虹的上方看到第二道、稍微暗淡一些的彩虹。第二道彩虹是由于光线在水滴中发生了两次反射而形成的。

<img src="{{ '/assets/images/rainbow/media/image8.jpeg' | relative_url }}" alt="Graph" />

图：笛卡尔关于主虹与副虹形成的示意图，出自《气象学》第八篇“论彩虹”（1637）

<img src="{{ '/assets/images/rainbow/media/image9.jpeg' | relative_url }}" alt="IMG_20210526_181035" />

图：主虹。作者摄于北京，2021年5月

<img src="{{ '/assets/images/rainbow/media/image10.jpeg' | relative_url }}" alt="IMG_20210526_181131" />

图：主虹与副虹。作者摄于北京，2021年5月

从理论上来说，确实有可能出现由水滴中的三次、四次或更多次反射而形成的彩虹现象。

参考资料：

[Maths behind the rainbow \| plus.maths.org](https://plus.maths.org/rainbows)

René Descartes, Les Météores, “Discours huitième: De l’arc-en-ciel”, 1637.


