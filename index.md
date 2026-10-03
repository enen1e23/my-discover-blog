---
layout: home
---

<style>
/* 只作用于本页；以后改文字，直接修改下方 HTML。 */
#nan-home { color: #171717; }
#nan-home .nd-hero {
  display: grid;
  grid-template-columns: 1.15fr 1fr;
  column-gap: 56px;
  align-items: end;
  padding: 34px 0 52px;
  border-bottom: 1px solid #171717;
}
#nan-home .nd-kicker {
  grid-column: 1 / -1;
  margin: 0 0 34px;
  color: #69665f;
  font-family: Consolas, "Courier New", monospace;
  font-size: 11px;
  line-height: 1.7;
  letter-spacing: .14em;
}
#nan-home .nd-hero h1 {
  margin: 0;
  font-size: clamp(56px, 7.5vw, 86px);
  line-height: .98;
  letter-spacing: -.055em;
}
#nan-home .nd-hero h1 span {
  display: block;
  font-family: Arial, sans-serif;
  font-weight: 300;
}
#nan-home .nd-hero h1 em {
  display: block;
  margin: 2px 0 0 30px;
  color: #e04b24;
  font-family: Georgia, "Times New Roman", serif;
  font-weight: 400;
}
#nan-home .nd-intro {
  max-width: 350px;
  margin: 0 0 3px;
  color: #4d4942;
  font-family: "Microsoft YaHei", "PingFang SC", sans-serif;
  font-size: 18px;
  line-height: 2;
  text-align: left;
  overflow-wrap: break-word;
}
#nan-home .nd-categories { margin: 0 0 48px; }
#nan-home .nd-row,
#nan-home .nd-row:visited {
  display: grid;
  grid-template-columns: 38px minmax(0, 1.15fr) minmax(0, 1fr) 26px;
  align-items: center;
  gap: 22px;
  min-height: 116px;
  box-sizing: border-box;
  padding: 25px 0;
  border-bottom: 1px solid #c9c5bc;
  color: #171717;
  background: transparent;
  text-decoration: none;
  transition: background-color .18s ease;
}
#nan-home .nd-number {
  align-self: center;
  color: #777168;
  font-family: Consolas, "Courier New", monospace;
  font-size: 12px;
}
#nan-home .nd-title {
  font-family: Arial, sans-serif;
  font-size: 26px;
  font-weight: 500;
  line-height: 1.2;
  letter-spacing: -.035em;
}
#nan-home .nd-description {
  grid-column: auto;
  max-width: none;
  color: #565149;
  font-size: 18px;
  line-height: 1.7;
  opacity: 1;
}
#nan-home .nd-arrow {
  grid-column: auto;
  grid-row: auto;
  align-self: center;
  color: #e04b24;
  font-size: 23px;
  text-align: right;
  transition: transform .18s ease;
}
#nan-home .nd-row:hover { background: #ece7dc; }
#nan-home .nd-row:hover .nd-arrow { transform: translate(2px, -2px); }
#nan-home .nd-row:focus-visible { outline: 2px solid #e04b24; outline-offset: 4px; }
#nan-home .nd-recent {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 8px 24px;
  margin: 0 0 24px;
  color: #69665f;
  font-size: 12px;
  letter-spacing: .1em;
}
#nan-home .nd-recent span:last-child {
  font-family: "Microsoft YaHei", "PingFang SC", sans-serif;
  font-size: 15px;
  letter-spacing: 0;
}
@media (max-width: 760px) {
  #nan-home .nd-hero { grid-template-columns: 1fr; gap: 0; padding: 20px 0 34px; }
  #nan-home .nd-kicker { margin-bottom: 26px; font-size: 10px; }
  #nan-home .nd-hero h1 { font-size: clamp(52px, 12vw, 76px); }
  #nan-home .nd-hero h1 em { margin-left: 24px; }
  #nan-home .nd-intro { max-width: 440px; margin: 30px 0 0; font-size: 17px; line-height: 1.9; }
  #nan-home .nd-row {
    grid-template-columns: 26px minmax(0, 1fr) 24px;
    gap: 9px 14px;
    min-height: 0;
    padding: 24px 0;
  }
  #nan-home .nd-number { grid-column: 1; grid-row: 1; align-self: start; padding-top: 4px; }
  #nan-home .nd-title { grid-column: 2; grid-row: 1; font-size: 24px; }
  #nan-home .nd-description { grid-column: 2; grid-row: 2; font-size: 17px; }
  #nan-home .nd-arrow { grid-column: 3; grid-row: 1 / 3; }
  #nan-home .nd-categories { margin-bottom: 34px; }
}
@media (prefers-reduced-motion: reduce) {
  #nan-home .nd-row, #nan-home .nd-arrow { transition: none; }
  #nan-home .nd-row:hover .nd-arrow { transform: none; }
}
</style>

<div id="nan-home">
<section class="nd-hero">
  <p class="nd-kicker">A PERSONAL INDEX OF THINGS NOTICED</p>
  <h1><span>Nan</span><em>Discovers</em></h1>
</section>

<nav class="nd-categories" aria-label="内容分类">
  <a class="nd-row" href="{{ '/categories/Physics_in_Everyday_Life/' | relative_url }}">
    <span class="nd-number">01</span>
    <strong class="nd-title">Physics<br>in Everyday Life</strong>
    <span class="nd-description">生活中的物理发现</span>
    <span class="nd-arrow" aria-hidden="true">↗</span>
  </a>
  <a class="nd-row" href="{{ '/categories/Life_Wisdom/' | relative_url }}">
    <span class="nd-number">02</span>
    <strong class="nd-title">Life<br>Wisdom</strong>
    <span class="nd-description">群众的智慧</span>
    <span class="nd-arrow" aria-hidden="true">↗</span>
  </a>
  <a class="nd-row" href="{{ '/categories/Cities/' | relative_url }}">
    <span class="nd-number">03</span>
    <strong class="nd-title">Ways of Seeing<br>a City</strong>
    <span class="nd-description">看见城市</span>
    <span class="nd-arrow" aria-hidden="true">↗</span>
  </a>
  <a class="nd-row" href="{{ '/categories/Books/' | relative_url }}">
    <span class="nd-number">04</span>
    <strong class="nd-title">Reading</strong>
    <span class="nd-description">分享我喜欢的书</span>
    <span class="nd-arrow" aria-hidden="true">↗</span>
  </a>
</nav>

<div class="nd-recent">
  <span>RECENT NOTES</span>
  <span>下方是最近更新的文章 ↓</span>
</div>
</div>
