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
  gap: 5%; /* 10% 的间距 */
}

.text {
  flex: 0 0 60%; /* 文字占 60% */
  text-align: justify;
  font-size: 20px;
}

.photo {
  flex: 0 0 30%; /* 照片占 30% */
  max-width: 300px; /* 限制最大宽度 */
  height: auto;
  aspect-ratio: 3/3; /* 推荐 3:4 人像比例 */
  border: 3px solid rgba(128, 128, 128, 0.5);
  border-radius: 5px;
  overflow: hidden;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

/* 移动端适配 */
@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
  .text, .photo {
    flex: 1 100%; /* 小屏幕下均占满宽度 */
  }
  .photo {
    max-width: 80%; /* 移动端照片占 80% */
    margin: 20px auto; /* 居中显示 */
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
Welcome to my website! I am an Assistant Professor ("Hundred Talents Program") in the School of Economics at the Zhejiang University. <br>
<br>
My research field is Macro Labor, where I study the sources and aggregate implications of mismatch in the labor market. <br>
<br>

Before joining ZJU, I obtained my Ph.D. in Economics from National University of Singapore in 2025. Here is my <a href="https://jie-duan.com/files/CV_JMC.pdf" class="cv-link" target="_blank">CV</a>.   
  </div>
  
  <div class="photo">
    <!-- 替换为您的个人照片路径 -->
    <img src="/images/NUSCeremonyHalf.jpg" alt="Profile Photo">
  </div>
</div>

<h2 class="title">CONTACT</h2>
<p class="contact-info section" style="margin-bottom: 0;">Address: 866 Yuhangtang Rd, Hangzhou 310058, China</p>
<p class="contact-info section" style="margin-top: 0;">Email: <a href="mailto:jieduan@zju.edu.cn">jieduan@zju.edu.cn</a></p>
