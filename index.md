---
layout: page
title: 
permalink: /
---

<style>
  .title {
    font-family: 'Verdana', sans-serif;
    font-weight: bold;
    font-size: 25px;
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
    font-size: 20px;
    margin-right: 5px;
  }
  .image {
    flex: 1;
    margin-left: 5px;
  }
  .image img {
    margin-top: 5px;
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
      margin-top: 10px;
      width: calc(100% - 20px); /* 照片宽度比屏幕窄20px */
      max-width: 285px; /* 最大宽度限制 */
      margin-left: 10px; /* 左侧距离屏幕10px */
      margin-right: 10px; /* 右侧距离屏幕10px */
    }
    .image img {
      width: 90%;
      height: auto;
    }
  }
  .contact-info {
    margin-bottom: 5px;
    margin-top: 5px;
    font-size: 20px; 
  }
  .section {
    font-size: 20px;
  }
  .committee {
    font-size: 20px; 
  }
</style>




<h2 class="title">WELCOME</h2>
<div class="container">
  <div class="text">
Welcome to my website, I am a doctoral candidate in the Department of Economics at the National University of Singapore (NUS). Prior to joining NUS, I obained my master's degree in Economics from London School of Economics, and my bachelor's degree in Economics from Central University of Finance and Economics.  <br>
<br>
My research focuses on Macro Labor, where I study the mismatch in the labor market and aim to identify its origins and features. Furthermore, I am also passionate about investigating the heterogeneities of employment stabilities in the labor market. <br>
<br>
    
I will be on the 2024/25 academic job market. Here is my <a href="https://jie-duan.com/files/CV_JMC.pdf">CV</a>.


  </div>
  <div class="image">
    {% include image.html url="images/official_photo.jpg" caption="" align="center" %}
  </div>
</div>

<h2 class="title">COMMITTEE</h2>
<div class="committee">
  <strong>Committee:</strong> <a href="https://www.paulgjackson.com/">Paul Jackson</a> (Advisor, NUS), 
  <a href="https://sites.google.com/view/ying-feng/home">Ying Feng</a> (NUS), 
  <a href="http://individual.utoronto.ca/wolthoff/">Ronald Wolthoff</a> (UoT)
</div>


<h2 class="title">CONTACT</h2>
<p class="contact-info section">Address: Blk AS1, #01-02, 1 Arts Link, Singapore 117570.</p>
<p class="contact-info section">Email: duanjie@u.nus.edu</p>

