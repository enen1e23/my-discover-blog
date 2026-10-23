---
layout: null
title: "理解彩虹的形状"
date: 2026-07-21
categories: [Physics_in_Everyday_Life]
permalink: /physics_in_everyday_life/understanding-rainbow-shape/
---
<!--
这篇文章的页面内容与样式现在都放在这个 Markdown 文件中。
直接修改下面的 <main> 内的中文文字、标题、图注和图片地址即可。
CSS 在顶部 <style> 中；太阳高度互动代码在文末 <script> 中。
10 张原图仍引用仓库 assets/images/rainbow-shape/media/ 下的原文件。
-->
<!doctype html>
<html lang="zh-CN">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="color-scheme" content="light">
<title>理解彩虹的形状｜Nan Discovers</title>
<meta name="description" content="从一滴水中的折射与反射，理解彩虹为什么呈现圆弧形状。保留作者绘制的光路、偏转角示意以及实拍彩虹照片。">
<link rel="canonical" href="https://enen1e23.github.io/my-discover-blog/physics_in_everyday_life/understanding-rainbow-shape/">
<style>

:root{
  --paper:#fbf9f4; --ink:#222124; --body:#353238; --muted:#7e7881;
  --line:#ddd8d1; --softline:#ebe7e2; --accent:#70586c; --panel:#f3f0f4;
  --tag:#f4f0e9; --tagline:#a97453;
  --sans:"Noto Sans CJK SC","PingFang SC","Hiragino Sans GB","Microsoft YaHei",sans-serif;
  --mono:"SFMono-Regular","Consolas","Liberation Mono","Courier New",monospace;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--body);font:400 17px/1.92 var(--sans);-webkit-font-smoothing:antialiased;text-rendering:optimizeLegibility}
a{color:inherit;text-underline-offset:3px}a:hover{color:#7a6076}
button,input{font:inherit}:focus-visible{outline:2px solid var(--accent);outline-offset:4px}
.site-shell{max-width:1130px;margin:0 auto;padding:0 18px}
.topbar{height:58px;display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid var(--line)}
.logo{text-decoration:none;font:500 17px/1.1 var(--mono);color:#17161a;letter-spacing:.055em}
.site-nav a{text-decoration:none;font:600 16px/1 var(--sans);color:#17161a}
.hero{width:min(100% - 40px,760px);margin:0 auto;padding:68px 0 48px}
.hero-meta{display:flex;justify-content:space-between;align-items:end;gap:18px;margin-bottom:34px}
.category-card{display:inline-block;background:var(--tag);padding:10px 14px 9px;border-left:2px solid #d98257}
.category-card strong{display:block;font:650 14px/1.2 var(--sans);color:#19181b;margin-bottom:6px}
.category-card span{display:block;font:500 10.5px/1.2 var(--mono);letter-spacing:.13em;color:#8f6b54;text-transform:uppercase}
.hero-date{font:500 12px/1.2 var(--mono);letter-spacing:.18em;color:#8a8187;white-space:nowrap;padding-bottom:5px}
.eyebrow{font:500 12px/1.6 var(--sans);letter-spacing:.04em;color:#8e7e89;margin:0 0 20px}
.hero h1{margin:0 0 18px;color:var(--ink)}
.rainbowword{display:block;width:max-content;max-width:100%;font:900 clamp(68px,11vw,96px)/1.05 var(--sans);letter-spacing:-.08em;margin:0 0 10px -3px;color:transparent;background:repeating-radial-gradient(ellipse 85% 95% at 35% 50%,#c889a0 0 6px,#ead0c1 6px 12px,#d7b577 12px 18px,#a3b69c 18px 24px,#88afbf 24px 30px,#b5a1c5 30px 36px,#dcacb5 36px 42px);-webkit-background-clip:text;background-clip:text;-webkit-text-stroke:.5px #a78293;filter:drop-shadow(0 1px 0 #e6dcda)}
.title-rest{display:block;font:650 clamp(33px,5vw,42px)/1.28 var(--sans);letter-spacing:-.04em}
.hero-intro{max-width:620px;margin:0;font-size:17px;line-height:1.95;color:#4e4a4f}
.toc{width:min(100% - 40px,760px);margin:0 auto 74px;padding:18px 0;border-top:1px solid var(--line);border-bottom:1px solid var(--line);display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
.toc a{text-decoration:none;font-size:12px;line-height:1.6;color:#555155;padding:0 4px}
.toc em{display:block;font:normal 10.5px/1.5 var(--mono);margin:0 0 5px;color:#ac8d9b}
.article{width:min(100% - 40px,760px);margin:0 auto}
.section{margin:0 0 94px;scroll-margin-top:30px}
.section-header{max-width:620px;margin:0 auto 24px}
.section-index{font:500 12px/1.4 var(--mono);letter-spacing:.12em;color:#907a8c;display:flex;align-items:center;gap:12px}
.section-index:after{content:"";width:34px;height:1px;background:#d7ccd4}
.section h2{margin:15px 0 0;font:650 clamp(28px,4.2vw,34px)/1.38 var(--sans);letter-spacing:-.03em;color:var(--ink)}
.section h3{max-width:620px;margin:38px auto 14px;font:650 20px/1.5 var(--sans);letter-spacing:-.01em;color:var(--ink)}
.section p,.section .lead{max-width:620px;margin:0 auto 18px}
.section .lead{font-size:17px;line-height:1.95;color:#3f3b41}
.tiny{color:var(--muted);font-size:12px}
.original-figure{width:100%;max-width:760px;margin:34px auto 40px}
.original-figure>a{display:block;text-align:center;text-decoration:none;padding:0;background:transparent}
.original-figure img{display:block;margin:0 auto;width:auto;max-width:100%;height:auto;max-height:620px;object-fit:contain}
.original-figure figcaption{max-width:620px;margin:0 auto;padding:11px 0 0;font-size:12px;line-height:1.75;color:#767077}
.fig-prefix{font-weight:600;color:#816a7a;margin-right:8px}
.offline{min-height:220px;align-items:center;justify-content:center;flex-direction:column;gap:6px;color:#6e6271;background:linear-gradient(160deg,#fbfaf8,#f7f4f5);border:1px solid var(--softline)}
.offline b{font-size:18px}.offline small{color:#8c878d}.offline .original-link{font-size:13px;text-decoration:underline;margin-top:4px}
.original-figure.photograph img{max-height:680px}
.math-note{width:100%;max-width:700px;margin:30px auto 45px;background:var(--panel);border:1px solid #e4dde7;border-radius:8px;overflow:hidden}
.math-note summary{list-style:none;cursor:pointer;display:flex;align-items:center;justify-content:space-between;gap:14px;padding:18px 22px}
.math-note summary::-webkit-details-marker{display:none}.math-note summary span{font-size:16px;font-weight:600;color:#3d3540}.math-note summary small{display:block;margin-top:3px;font-size:12px;color:#83798a;font-weight:400}
.math-note summary i{font:normal 23px/1 var(--sans);color:#8e7f96}.math-note[open] summary i{transform:rotate(45deg)}
.math-note .math-body{padding:20px 22px 22px;border-top:1px solid #e1d8e4}.math-body p{font-size:15px;line-height:1.9}
.formula{max-width:620px;margin:18px auto 24px;font:normal 29px/1.6 Georgia,"Times New Roman",serif;color:#674f73;text-align:center;overflow-x:auto;white-space:nowrap}.formula sub{font-size:55%}
.observation,.focal,.extra-demo,.closing,.references{width:100%;max-width:700px;margin-left:auto;margin-right:auto}
.observation{margin-top:34px;margin-bottom:38px;padding:22px 24px;background:#f6f2ed;border-left:2px solid #bda69c}
.observation strong{display:block;font-size:14px;font-weight:600;margin:0 0 6px}.observation p{font-size:15px;line-height:1.9;margin:0}
.focal{display:grid;grid-template-columns:122px 1fr;gap:22px;align-items:center;margin-top:38px;margin-bottom:22px;padding:22px 24px;background:#f6f2ed}
.focal .number{font:normal 68px/.98 Georgia,serif;letter-spacing:-.06em;color:#80697b}.focal p{font-size:15px;line-height:1.85;margin:0}
.extra-demo{border-top:1px solid var(--line);border-bottom:1px solid var(--line);margin-top:42px;margin-bottom:48px;padding:26px 0 22px}
.extra-title{max-width:620px!important;margin:0 auto 7px!important;font-size:15px!important;font-weight:650;color:var(--ink)}
.extra-demo .tiny{max-width:620px;margin:0 auto 14px;font-size:12px}
.extra-svg{width:100%;max-width:700px;height:auto;display:block;margin:12px auto 4px}
.slider{max-width:620px;display:flex;align-items:center;gap:18px;margin:8px auto 0;font-size:13px}.slider label{white-space:nowrap}.slider input{flex:1;accent-color:#86778f;min-width:80px;cursor:pointer}.slider output{min-width:39px;color:#665570;font-weight:600}
.slider-text{max-width:620px!important;margin:10px auto 0!important;font-size:13px!important;color:#696367}
.photos{margin-top:38px}.photos .original-figure{margin-bottom:32px}
.closing{max-width:620px;margin:0 auto 74px;padding:0}.closing p{font-size:17px;line-height:1.95}
.references{max-width:620px;margin:0 auto 82px;padding:24px 0 0;border-top:1px solid var(--line);font-size:13px;color:#777178;line-height:1.9}.references h2{font-size:15px;font-weight:650;color:var(--ink);margin:0 0 12px}.references a{color:#6b5d75}
.footer-wrap{max-width:1130px;margin:0 auto;padding:0 18px}
.footer{padding:24px 0 34px;border-top:1px solid var(--line);display:flex;justify-content:space-between;flex-wrap:wrap;gap:18px;font-size:12px;color:#858087;line-height:1.6}.footer a{text-decoration:none}
@media(max-width:720px){
 body{font-size:16px;line-height:1.86}
 .site-shell,.footer-wrap{padding:0 16px}
 .topbar{height:56px}.logo{font-size:16px;letter-spacing:.03em}.site-nav a{font-size:15px}
 .hero{width:calc(100% - 34px);padding:48px 0 36px}
 .hero-meta{display:block;margin-bottom:24px}.hero-date{margin-top:14px;padding-bottom:0}
 .category-card{padding:9px 12px 8px}.category-card strong{font-size:13px}
 .eyebrow{font-size:11px;margin-bottom:16px}
 .rainbowword{font-size:clamp(64px,22vw,88px);margin:0 0 8px -2px}
 .title-rest{font-size:clamp(28px,8vw,36px);line-height:1.34}
 .hero-intro{font-size:15.5px;line-height:1.92}
 .toc{width:calc(100% - 34px);grid-template-columns:1fr 1fr;gap:0 12px;margin-bottom:62px;padding:10px 0}
 .toc a{padding:10px 0}.toc a:nth-child(-n+2){border-bottom:1px solid var(--line)}
 .article{width:calc(100% - 34px)}
 .section{margin-bottom:74px}.section-header{margin-bottom:20px}.section h2{font-size:26px}.section h3{font-size:18px;margin:32px auto 12px}
 .original-figure{margin:28px auto 34px}.original-figure img{max-height:500px}.original-figure figcaption{font-size:11.5px;line-height:1.68}
 .math-note{margin:24px auto 34px}.math-note summary{padding:16px 18px}.math-note .math-body{padding:17px 18px 19px}
 .formula{font-size:clamp(22px,6vw,27px)}
 .observation{padding:18px 18px}.focal{grid-template-columns:1fr;gap:12px;padding:18px 18px}.focal .number{font-size:60px}
 .extra-demo{margin-top:36px;margin-bottom:40px}.slider{gap:10px}.slider label{font-size:12px}
 .closing{margin-bottom:58px}.closing p{font-size:16px}
 .references{margin-bottom:60px}
 .footer{padding:22px 0 30px}
}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}}

</style>
</head>
<body>
<div class="site-shell">
<header class="topbar"><a class="logo" href="https://enen1e23.github.io/my-discover-blog/">Nan Discovers</a><nav class="site-nav"><a href="https://enen1e23.github.io/my-discover-blog/about/">关于</a></nav></header>
</div>
<main>
<section class="hero" aria-labelledby="main-title"><div class="hero-meta"><div class="category-card"><strong>生活中的物理发现</strong><span>Physics in Everyday Life</span></div><div class="hero-date">2026 · 07 · 21</div></div>

<h1 id="main-title"><span class="rainbowword">彩虹</span><span class="title-rest">为什么是弯的？</span></h1>
<p class="hero-intro">雨后，天空里有时能看到一段很整齐的圆弧。水滴并没有排成弧线，但不同颜色的光却沿着弧线出现。</p>
</section>
<nav class="toc" aria-label="文章目录"><a href="#drop"><em>01</em>光线进入水滴</a><a href="#gather"><em>02</em>光线为什么集中</a><a href="#arc"><em>03</em>为什么形成圆弧</a><a href="#personal"><em>04</em>不同的观察者</a></nav>
<div class="article">
<section class="section" id="drop"><div class="section-header"><div class="section-index">01 / 一滴水</div><h2>光线怎样穿过一滴水</h2></div>
<p class="lead">天空中有许多近似球形的水滴。由于太阳很远，到达一小片雨幕的阳光可以看成一束束平行光。</p>
<p>阳光进入水滴时发生折射；到达水滴背面后，一部分光射出，一部分被反射回内部。反射的光到达另一侧，再次折射并离开水滴。这就是形成主虹的一条典型光路。</p>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image1.png" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image1.png" alt="原文配图 1：主虹光线在球形水滴中的传播路径。α 和 β 均以法线为基准。作者绘制。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 1</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 1</span>主虹光线在球形水滴中的传播路径。α 和 β 均以法线为基准。作者绘制。</figcaption>
    </figure>
<p>图中的 α 是入射角，β 是折射角。两个角度都是相对于水滴表面的法线测量的。光线进入水滴后会向法线方向偏折。</p>
<details class="math-note"><summary><div><span>折射角怎样计算<small>斯涅尔定律</small></span></div><i aria-hidden="true">+</i></summary><div class="math-body"><p>空气的折射率近似取 1，水的折射率约为 1.33。入射角和折射角满足：</p><div class="formula">sin α = 1.33 sin β</div><p>所以，β = arcsin(sin α / 1.33)。折射率与颜色略有关系，图中先用一个近似值讨论光线的几何路径。</p></div></details>
<h3>光线最终偏转了多少</h3>
<p>不同的入射位置，对应不同的入射角。光线走过水滴后，最终出射方向也会有所不同。把出射方向相对原来入射方向的总转向角记作 D(α)。</p>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image2.png" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image2.png" alt="原文配图 2：主虹光线总偏转角 D(α) 的几何推导。作者绘制。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 2</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 2</span>主虹光线总偏转角 D(α) 的几何推导。作者绘制。</figcaption>
    </figure>
<p>对于一次内部反射的主虹光路，总偏转角可以写成：</p><div class="formula">D(α) = 180° + 2α − 4β</div>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image3.jpeg" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image3.jpeg" alt="原文配图 3：D(α) 的函数图。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 3</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 3</span>D(α) 的函数图。</figcaption>
    </figure>
<p>这条曲线有一个最低点。接下来，彩虹的亮度就与它有关。</p>
</section>
<section class="section" id="gather"><div class="section-header"><div class="section-index">02 / 光线聚集</div><h2>为什么某些方向特别亮</h2></div>
<p class="lead">图中最值得注意的地方，是总偏转角 D(α) 并不是一直增大或一直减小。它会先减小，再增大。</p>
<p>在极小值附近，入射角即使变化一些，出射方向也变化得很少。很多光线因此会聚集在相近的方向。这个方向上的光就比较强。</p>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image4.png" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image4.png" alt="原文配图 4：偏转角极小值与光线的集中。相同入射角范围在极小值附近对应更小的出射角范围。作者绘制。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 4</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 4</span>偏转角极小值与光线的集中。相同入射角范围在极小值附近对应更小的出射角范围。作者绘制。</figcaption>
    </figure>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image5.png" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image5.png" alt="原文配图 5：光线在不同出射方向上的分布。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 5</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">原文图示</span>光线在不同出射方向上的分布。</figcaption>
    </figure>
<div class="observation"><strong>从曲线到观察</strong><p>水滴并不是把所有方向的光都均匀地送到我们眼里。比较多的光会从接近极小偏转角的方向射出来，因此我们更容易看到那个方向的颜色。</p></div>
<p>不同颜色的光在水中的折射率略有不同，对应的集中方向也不同。这是彩虹颜色分开的原因之一。</p>
</section>
<section class="section" id="arc"><div class="section-header"><div class="section-index">03 / 空间中的圆</div><h2>一个角度怎样变成圆弧</h2></div>
<p class="lead">对于主虹，红光的典型观察角约为 42°，紫光更靠内侧，约为 40°。</p>
<p>这里的角度不是水滴在天空中的高度，而是以<strong>反太阳方向</strong>为中心，从观察者眼睛量出去的角度。</p>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image6.jpeg" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image6.jpeg" alt="原文配图 6：主虹的观察角约为 42.5°。来源：Plus Magazine，Maths behind the rainbow。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 6</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 5</span>主虹的观察角约为 42.5°。来源：Plus Magazine，Maths behind the rainbow。</figcaption>
    </figure>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image7.png" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image7.png" alt="原文配图 7：圆弧方向示意图。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 7</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">原文图示</span>圆弧方向示意图。</figcaption>
    </figure>
<div class="focal"><div class="number">42°</div><p>将与反太阳方向成约 42° 的视线绕一圈，会得到一个圆锥面。落在这些方向上的水滴，能够把相应的主虹光送入观察者的眼睛。于是，看到的颜色沿圆弧排列。</p></div>
<div class="extra-demo"><div class="extra-title">补充示意 · 太阳升高时</div><p class="tiny">这里新增了一个简单的动态示意，原文插图仍保留在上面。移动滑块，可以看彩虹露出地平线的部分如何变化。</p>
<svg class="extra-svg" viewBox="0 0 740 350" role="img" aria-label="简化示意：太阳越高，反太阳点越低，彩虹露出地平线的部分越少"><defs><clipPath id="skyclip"><rect x="0" y="0" width="740" height="250"/></clipPath></defs><rect x="0" y="0" width="740" height="250" fill="#f5f6f4"/><rect x="0" y="250" width="740" height="100" fill="#eaece8"/><line x1="0" y1="250" x2="740" y2="250" stroke="#b8c0b8" stroke-width="1.5"/><g clip-path="url(#skyclip)"><g id="rainbow-ring" fill="none" stroke-width="4"><circle cx="370" cy="250" r="220" stroke="#c98a9d"/><circle cx="370" cy="250" r="215" stroke="#d3ab8d"/><circle cx="370" cy="250" r="210" stroke="#d6c590"/><circle cx="370" cy="250" r="205" stroke="#9db99f"/><circle cx="370" cy="250" r="200" stroke="#93afc0"/><circle cx="370" cy="250" r="195" stroke="#b0a1bf"/></g></g><g fill="#7e7b7a" font-size="13" font-family="Noto Sans CJK SC,sans-serif"><text x="17" y="242">地平线</text><text x="380" y="325">观察者</text></g><circle cx="370" cy="301" r="7" fill="#766778"/><path d="M358 325q12-28 24 0" fill="#766778"/><circle id="anti-point" cx="370" cy="250" r="3.5" fill="#9d859e"/><text id="anti-text" x="383" y="247" fill="#978699" font-size="12">反太阳点</text></svg>
<div class="slider"><label for="sun">太阳高度</label><input id="sun" type="range" min="0" max="42" value="12" step="1"><output id="sun-value" for="sun">12°</output></div><p id="sun-result" class="slider-text">太阳高约 12° 时，主虹的最高处大约在地平线上方 30°。</p><p class="tiny" style="margin-top:16px">说明：这里用简化的二维图表示角度关系，不是严格的天空投影。</p></div>
</section>
<section class="section" id="personal"><div class="section-header"><div class="section-index">04 / 观察者</div><h2>每个人看到的彩虹不完全相同</h2></div>
<p class="lead">两个人站在不同的位置，能够把光送进他们眼睛里的水滴，也就不完全相同。</p>
<p>彩虹看起来像挂在远处的物体，其实它由太阳、水滴和观察者之间的几何关系决定。</p>
<p>有时主虹外侧还会出现一道较暗的副虹。副虹的光在水滴内部经历两次反射，所以它的颜色顺序与主虹相反。</p>
<figure class="original-figure ">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image8.jpeg" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image8.jpeg" alt="原文配图 8：笛卡尔关于主虹与副虹形成的示意图。出自《气象学》第八篇《论彩虹》（1637）。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 8</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 6</span>笛卡尔关于主虹与副虹形成的示意图。出自《气象学》第八篇《论彩虹》（1637）。</figcaption>
    </figure>
<p>下面两张照片拍于北京，2021 年 5 月。第一张是主虹，第二张同时出现了主虹和副虹。</p>
<div class="photos"><figure class="original-figure photograph">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image9.jpeg" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image9.jpeg" alt="原文配图 9：主虹。作者摄于北京，2021 年 5 月。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 9</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 7</span>主虹。作者摄于北京，2021 年 5 月。</figcaption>
    </figure><figure class="original-figure photograph">
      <a href="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image10.jpeg" target="_blank" rel="noopener" title="查看原图">
        <img src="https://enen1e23.github.io/my-discover-blog/assets/images/rainbow-shape/media/image10.jpeg" alt="原文配图 10：主虹与副虹。作者摄于北京，2021 年 5 月。" loading="lazy" onerror="this.style.display='none';this.parentNode.querySelector('.offline').style.display='flex'" />
        <span class="offline" style="display:none"><b>原文配图 10</b><small>图片使用原文地址，联网后可显示</small><span class="original-link">查看原图 ↗</span></span>
      </a>
      <figcaption><span class="fig-prefix">图 8</span>主虹与副虹。作者摄于北京，2021 年 5 月。</figcaption>
    </figure></div>
<p>从理论上说，水滴中经历三次、四次或更多次反射的光，也可能形成更高阶的虹，只是通常不容易在日常观察中看到。</p>
</section>
</div>
<div class="closing"><p>从一滴水中的光路，到天空里的一段圆弧，中间连接着的是一个角度，以及观察者站立的位置。</p></div>
<div class="references" style="padding-left:26px;padding-right:26px"><h2>参考资料</h2><div>Plus Magazine，<a href="https://plus.maths.org/rainbows" target="_blank" rel="noopener">Maths behind the rainbow</a></div><div>René Descartes, <i>Les Météores</i>, « Discours huitième: De l’arc-en-ciel », 1637.</div></div>
</main>
<div class="footer-wrap"><footer class="footer"><div>Nan Discovers · 生活中的物理 / 观察笔记</div><a href="https://enen1e23.github.io/my-discover-blog/">返回首页 ↗</a></footer></div>
<script>
(()=>{const slider=document.getElementById('sun'),out=document.getElementById('sun-value'),result=document.getElementById('sun-result'),ring=document.getElementById('rainbow-ring'),dot=document.getElementById('anti-point'),label=document.getElementById('anti-text');function render(){const s=Number(slider.value);const y=s/42*220;ring.setAttribute('transform',`translate(0 ${y})`);dot.setAttribute('cy',250+y);label.setAttribute('y',247+y);out.textContent=s+'°';result.textContent=`太阳高约 ${s}° 时，主虹的最高处大约在地平线上方 ${42-s}°。`};slider.addEventListener('input',render);render()})();
</script>
</body>
</html>
