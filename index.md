---
layout: page
title: Welcome
permalink: /
---

<style>
  .title {
    font-family: 'Verdana', sans-serif;
    font-weight: bold;
    font-size: 24px;
    color: rgba(128, 128, 128, 0.8);
  }
  .container {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
  }
  .text {
    flex: 1;
    text-align: justify;
    margin-right: 10px;
  }
  .image {
    flex: 1;
    margin-left: 10px;
  }
  .image img {
    width: 300px;
    height: auto;
  }

  /* 媒体查询，针对不同屏幕尺寸进行调整 */
  @media (max-width: 768px) {
    .text, .image {
      flex: 1 100%;
      margin: 0;
    }
    .text {
      text-align: justify; /* 使手机浏览时文字两侧对齐 */
      margin-left: 15px; /* 左侧距离屏幕10px */
      margin-right: 15px; /* 右侧距离屏幕10px */
    }
    .image {
      margin-top: 20px;
      width: calc(100% - 20px); /* 照片宽度比屏幕窄20px */
      max-width: 300px; /* 最大宽度限制 */
      margin-left: 10px; /* 左侧距离屏幕10px */
      margin-right: 10px; /* 右侧距离屏幕10px */
    }
    .image img {
      width: 100%;
      height: auto;
    }
  }
</style>

<h2 class="title">Welcome</h2>
<div class="container">
  <div class="text">
  I'm Jie Duan, a Ph.D. Candidate in the Department of Economics at the National University of Singapore. My primary focus is on Macro Labor, exploring the mismatch in the labor market and seeking to understand its origins and features. Additionally, I have a keen interest in (Applied) International Trade.
    
  </div>
  <div class="image">
    {% include image.html url="images/photo1.jpg" caption="" align="center" %}
  </div>
</div>

<h2 class="title">Contact</h2>
<p>Address: Blk AS1, #01-02, 1 Arts Link, Singapore 117570.</p>
<p>Email: duanjie@u.nus.edu</p>

