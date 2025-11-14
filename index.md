---
layout: home
title: 首页
---

<div class="profile">
    <div class="profile-left">
        <img src="./assets/avatar.jpg" alt="Avatar" class="profile-avatar">
        <h1 class="profile-name">{{ site.title }}</h1>
        <div class="social-links">
            <a href="https://github.com/warnstein001" target="_blank" class="social-link" title="GitHub">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
                </svg>
            </a>
        </div>
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
    <h2>Blog Post</h2>
    <div class="blog-list">
        <!-- 单篇文章 -->
        <a href="/methods" class="blog-item">
            <h3>Introduction to Learning Methods</h3>
            <p>This is a template for writing an article on strategic study techniques.</p>
        </a>
        <!-- 文件夹：Wiki 笔记 -->
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
