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
            <h3>📄 单篇文章模板</h3>
            <p>这个是写单篇文章的模板</p>
        </a>
        <!-- 文件夹：Wiki 笔记 -->
        <div class="blog-folder">
            <div class="folder-header">
                <h3>模板</h3>
                <p>文件夹模板</p>
            </div>
            <div class="folder-content">
                <a href="/wiki/intro" class="blog-item-nested">
                    <h4>Blog 01</h4>
                    <p>The first blog</p>
                </a>
                <!-- 继续在该文件夹下添加笔记 -->
                <a href="/wiki/example" class="blog-item-nested">
                    <h4>Blog 02</h4>
                    <p>The second blog</p>
                </a>
            </div>
        </div>
        <div class="blog-folder">
         <div class="folder-header">
                <h3>CSAPP</h3>
                <p>Computer System A Programmmer's Perspective</p>
            </div>
            <div class="folder-content">
                <a href="/CSAPP/Introduction" class="blog-item-nested">
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
