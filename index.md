---
layout: home
title: 首页
---

<div class="profile">
    <img src="/assets/avatar.jpg" alt="Avatar" class="profile-avatar">
    <h1 class="profile-name">{{ site.title }}</h1>
    <p class="profile-bio">{{ site.description }}</p>
</div>

<div class="blog-index">
    <h2>博客文章</h2>
    <div class="blog-list">
        <a href="/about" class="blog-item">
            <h3>关于我</h3>
            <p>个人简介与联系方式</p>
        </a>
        <a href="/wiki/intro" class="blog-item">
            <h3>Wiki 简介</h3>
            <p>纯文本风格的 Wiki 模板介绍</p>
        </a>
        <a href="/wiki/example" class="blog-item">
            <h3>示例页面</h3>
            <p>Markdown 使用示例与代码演示</p>
        </a>
    </div>
</div>
