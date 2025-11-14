---
layout: home
title: 首页
---

<div class="profile">
    <div class="profile-left">
        <img src="./assets/avatar.jpg" alt="Avatar" class="profile-avatar">
        <h1 class="profile-name">{{ site.title }}</h1>
        <p class="profile-title">{{ site.description }}</p>
    </div>
    <div class="profile-right">
        <div class="profile-bio">
            <p>Hi! I'm Warnstein — welcome to my personal blog.</p>
            <p>Here, I document my study notes, technical explorations, and reflections on life. I’m passionate about programming, enjoy diving into new technologies, and appreciate the process of capturing my thoughts through writing.</p>
            <p>I hope the content here can be helpful to you, and you're always welcome to reach out and discuss ideas with me!</p>
        </div>
    </div>
</div>

<div class="blog-index">
    <h2>博客文章</h2>
    <div class="blog-list">
        <!-- 单篇文章 -->
        <a href="/about" class="blog-item">
            <h3>📄 关于我</h3>
            <p>个人简介与联系方式</p>
        </a>
        <!-- 文件夹：Wiki 笔记 -->
        <div class="blog-folder">
            <div class="folder-header">
                <h3>📁 Wiki 笔记</h3>
                <p>技术文档与学习笔记集合</p>
            </div>
            <div class="folder-content">
                <a href="/wiki/intro" class="blog-item-nested">
                    <h4>Wiki 简介</h4>
                    <p>纯文本风格的 Wiki 模板介绍</p>
                </a>
                <!-- 继续在该文件夹下添加笔记 -->
                <a href="/wiki/example" class="blog-item-nested">
                    <h4>示例页面</h4>
                    <p>Markdown 使用示例与代码演示</p>
                </a>
            </div>
        </div>
        <div class="blog-folder">
         <div class="folder-header">
                <h3>CSAPP</h3>
                <p>Computer System A Programmmer's Perspective</p>
            </div>
            <div class="folder-content">
                <a href="/CSAPP/intro" class="blog-item-nested">
                    <h4>CSAPP introduce</h4>
                    <p>Introduction</p>
                </a>
            </div>
        </div>
        <!-- 可以继续添加更多文章或文件夹 -->
    </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const folders = document.querySelectorAll('.blog-folder');
    folders.forEach(folder => {
        const header = folder.querySelector('.folder-header');
        const content = folder.querySelector('.folder-content');
        
        header.addEventListener('click', function() {
            folder.classList.toggle('open');
        });
    });
});
</script>
