---
layout: default # 使用 default 布局，与你的其他页面保持一致
title: 联系我们
permalink: /contact/ # 页面的固定链接
---

# 联系我们

如果您有任何问题、建议或合作意向，欢迎通过以下方式与我们联系：

**电子邮箱:** ssk937520@gmail.com

**天算AI博客:** https://jinv2.github.io/

**联系方式:** 手机/微信: 15632151615

---

<div style="text-align: center; margin-top: 30px; margin-bottom: 10px;">
  <h2 style="margin-bottom: 20px;">天算AI名片预览</h2>
  <!-- === 使用修正后的图片路径 === -->
  <!-- 请确保 assets/images/ 目录下有名为 '天算AI 名片圆角xxxxxxxxxxxxx.png' 的图片 -->
  <img src="{{ site.baseurl }}/assets/images/天算AI 名片圆角xxxxxxxxxxxxx.png" alt="天算AI 名片预览" style="max-width: 320px; height: auto; border-radius: 15px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
</div>

<div style="text-align: center; margin-top: 20px; margin-bottom: 30px;">
  <!-- 下载 ZIP 包的按钮 -->
  <!-- === 使用修正后的下载链接路径 === -->
  <!-- 请确保仓库的 assets/ 目录下有名为 '天算AI数字名片.zip' 的文件 -->
  <a
    href="{{ site.baseurl }}/assets/天算AI数字名片.zip"
    download="天算AI数字名片.zip"
    style="display: inline-block; padding: 12px 20px; background-color: #4CAF50; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; cursor: pointer; margin: 5px;"
  >
    下载交互式名片 (ZIP)
  </a>
  <!-- RSS 订阅按钮 -->
  <!-- === 使用修正后的 RSS Feed 链接路径 === -->
  <a
    href="{{ site.baseurl }}/feed.xml"
    target="_blank"
    rel="noopener noreferrer"
    style="display: inline-block; padding: 12px 20px; background-color: #ff9800; /* 橙色 */ color: white; text-decoration: none; border-radius: 5px; font-weight: bold; cursor: pointer; margin: 5px;"
  >
    订阅 RSS Feed
  </a>
</div>

<!-- 二维码部分 -->
<div style="text-align: center; margin-top: 30px; margin-bottom: 40px; border-top: 1px solid #eee; padding-top: 30px;">
  <h3 style="margin-bottom: 15px;">扫码关注/访问</h3>
  <!-- === 使用修正后的二维码图片路径 === -->
  <!-- 请确保 assets/images/ 目录下有名为 'tsai_qrcode.png' 的图片 -->
  <img src="{{ site.baseurl }}/assets/images/tsai_qrcode.png" alt="天算AI网站二维码" style="width: 150px; height: 150px; border: 1px solid #ccc; display: block; margin: 0 auto 10px;">
  <p style="font-size: 0.9em; color: #555; margin: 0;">手机扫描二维码访问或收藏网站</p>
</div>

<!-- Optional Footer Navigation -->
<!--
<hr>
<p>
  <a href="{{ '/' | relative_url }}">首页</a> |
  <a href="{{ '/blog/' | relative_url }}">博客</a> |
  <a href="{{ '/about/' | relative_url }}">关于</a> |
  <a href="{{ '/contact/' | relative_url }}">联系我们</a>
</p>
-->
