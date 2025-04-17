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
    gap: 20px; /* 添加间距，占剩下的5% */
  }
  .text {
    flex: 0 0 65%; /* 占65%宽度 */
    text-align: justify;
    font-size: 20px;
  }
  .photo {
    flex: 0 0 30%; /* 占30%宽度 */
    max-width: 300px; /* 设置最大宽度防止过大 */
    height: auto; /* 高度自适应 */
    aspect-ratio: 1/1; /* 保持1:1比例 */
    border: 3px solid rgba(128, 128, 128, 0.5);
    border-radius: 5px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  .photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* 媒体查询，针对不同屏幕尺寸进行调整 */
  @media (max-width: 768px) {
    .container {
      flex-direction: column;
    }
    .text, .photo {
      flex: 1 100%; /* 在小屏幕上各占100% */
      max-width: 100%;
    }
    .photo {
      margin-top: 20px;
      order: -1;
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
    <img src="/assets/images/profile.jpg" alt="Profile Photo">
  </div>
</div>

<h2 class="title">CONTACT</h2>
<p class="contact-info section" style="margin-bottom: 0;">Address: Blk AS1, #01-02, 1 Arts Link, Singapore 117570.</p>
<p class="contact-info section" style="margin-top: 0;">Email: <a href="mailto:duanjie@u.nus.edu">duanjie@u.nus.edu</a></p>
