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
    gap: 20px; /* 添加间距 */
  }
  .text {
    flex: 1;
    text-align: justify;
    font-size: 20px;
    min-width: 300px; /* 确保在小屏幕上也有良好显示 */
  }
  .photo {
    flex: 0 0 auto;
    width: 200px;
    height: 200px;
    border: 3px solid rgba(128, 128, 128, 0.5); /* 灰色半透明边框 */
    border-radius: 5px; /* 轻微圆角 */
    overflow: hidden; /* 确保图片不超出边框 */
    box-shadow: 0 2px 5px rgba(0,0,0,0.1); /* 轻微阴影效果 */
  }
  .photo img {
    width: 100%;
    height: 100%;
    object-fit: cover; /* 保持图片比例 */
  }

  /* 媒体查询，针对不同屏幕尺寸进行调整 */
  @media (max-width: 768px) {
    .container {
      flex-direction: column;
    }
    .text {
      flex: 1 100%;
      text-align: justify;
      margin-left: 15px;
      margin-right: 15px;
    }
    .photo {
      margin-top: 20px;
      order: -1; /* 在小屏幕上照片显示在上方 */
    }
  }
  .contact-info {
    margin-bottom: -5px;
    margin-top: -5px;
    font-size: 20px; 
  }
  .section {
    font-size: 20px;
  }
  .committee {
    font-size: 20px; 
  }
</style>

<h2 class="title">ABOUT ME</h2>
<div class="container">
  <div class="text">
Welcome to my website! I am a Ph.D. candidate in the Department of Economics at the National University of Singapore, with an expected graduate date of June 2025.   <br>
<br>
My research field is Macro Labor, where I study the sources and aggregate implications of mismatch in the labor market. <br>
<br>

I will join the School of Economics, Zhejiang University as an assistant professor in July 2025.    
  </div>
  <div class="photo">
    <!-- 替换为您的个人照片路径 -->
    <img src="/images/profile.jpg" alt="Profile Photo">
  </div>
</div>

<h2 class="title">CONTACT</h2>
<p class="contact-info section" style="margin-bottom: 0;">Address: Blk AS1, #01-02, 1 Arts Link, Singapore 117570.</p>
<p class="contact-info section" style="margin-top: 0;">Email: <a href="mailto:duanjie@u.nus.edu">duanjie@u.nus.edu</a></p>
