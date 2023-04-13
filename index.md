---
layout: page
title: 
permalink: /
---

<style>
  .title {
    font-family: 'Verdana', sans-serif;
    font-weight: bold;
    font-size: 35px;
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
    margin-right: 5px;
  }
  .image {
    flex: 1;
    margin-left: 5px;
  }
  .image img {
    width: 400px;
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
  .contact-info {
    margin-bottom: 5px;
    margin-top: 5px;
  }

</style>

<h2 class="title">WELCOME</h2>
<div class="container">
  <div class="text">
My name is Jie Duan, and I am currently a Ph.D. Candidate in the Department of Economics at the National University of Singapore (NUS). My research primarily focuses on Macro Labor, where I study the mismatch in the labor market and aim to identify its origins and features. Furthermore, I am also passionate about investigating the heterogeneities of employment stabilities in the labor market. Apart from my research in Macro Labor, I have a keen interest in (Applied) International Trade.
    
  </div>
  <div class="image">
    {% include image.html url="images/photolife.jpg" caption="" align="center" %}
  </div>
</div>

<h2 class="title">CONTACT</h2>
<p class="contact-info">Address: Blk AS1, #01-02, 1 Arts Link, Singapore 117570.</p>
<p class="contact-info">Email: duanjie@u.nus.edu</p>

