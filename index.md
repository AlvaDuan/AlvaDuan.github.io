---
layout: page
title: Welcome
permalink: /
---

<style>
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

  /* 媒体查询，针对不同屏幕尺寸进行调整 */
  @media (max-width: 768px) {
    .text, .image {
      flex: 1 100%;
      text-align: center;
      margin: 0;
    }
    .image {
      margin-top: 20px;
      width: calc(100% - 40px); /* 使照片宽度比屏幕略窄 */
      max-width: 300px; /* 最大宽度限制 */
    }
    .image img {
      width: 100%;
      height: auto;
    }
  }
</style>

<div class="container">
  <div class="text">
  I'm Jie Duan, a Ph.D. Candidate in the Department of Economics at the National University of Singapore. My primary focus is on Macro Labor, exploring the mismatch in the labor market and seeking to understand its origins and features. Additionally, I have a keen interest in (Applied) International Trade.
    
  </div>
  <div class="image">
    {% include image.html url="images/photo1.jpg" caption="" align="center" %}
  </div>
</div>




## Contact
Address: Blk AS1, #01-02, 1 Arts Link, Singapore 117570.  

Email: duanjie@u.nus.edu

