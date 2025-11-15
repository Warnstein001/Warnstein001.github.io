---
layout: default
title: CSAPP 笔记
---

# CSAPP - Computer System: A Programmer's Perspective

深入理解计算机系统课程笔记集合。

<div class="post-list">
    <article class="post-card">
        <a href="/CSAPP/Introduction" class="post-link">
            <div class="post-image">
                <div class="placeholder-text">CSAPP</div>
            </div>
            <div class="post-content">
                <h2>导论 - Introduction</h2>
                <p>在数字时代的浪潮中，计算机已渗透到科学研究、工业生产、日常生活的每一个角落。本章介绍为什么要"深入理解"计算机系统，以及课程的核心内容框架。</p>
                <div class="post-meta">
                    <span class="post-date">📅 2025-11-14</span>
                    <span class="post-tags">#CSAPP #计算机系统 #导论</span>
                </div>
            </div>
        </a>
    </article>
    
    <!-- 可以继续添加更多笔记 -->
</div>

<style>
.post-list {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 30px;
}

.post-card {
    background: #fff;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    transition: all 0.3s ease;
    border: 1px solid #e5e5e5;
}

.post-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 24px rgba(0,0,0,0.12);
}

.post-link {
    display: flex;
    text-decoration: none;
    color: inherit;
}

.post-image {
    width: 280px;
    height: 200px;
    flex-shrink: 0;
    overflow: hidden;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}

.placeholder-text {
    color: white;
    font-size: 48px;
    font-weight: bold;
    letter-spacing: 2px;
}

.post-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.post-card:hover .post-image img {
    transform: scale(1.05);
}

.post-content {
    flex: 1;
    padding: 24px 28px;
    display: flex;
    flex-direction: column;
}

.post-content h2 {
    font-size: 22px;
    font-weight: 600;
    color: #1a1a1a;
    margin: 0 0 12px 0;
    line-height: 1.4;
}

.post-content p {
    font-size: 15px;
    color: #666;
    line-height: 1.6;
    margin: 0 0 16px 0;
    flex: 1;
    display: -webkit-box;
    -webkit-line-clamp: 2;
    -webkit-box-orient: vertical;
    overflow: hidden;
}

.post-meta {
    display: flex;
    gap: 16px;
    font-size: 14px;
    color: #999;
}

.post-date {
    display: flex;
    align-items: center;
}

.post-tags {
    color: #0066cc;
}

@media (max-width: 768px) {
    .post-link {
        flex-direction: column;
    }
    
    .post-image {
        width: 100%;
        height: 180px;
    }
    
    .post-content {
        padding: 20px;
    }
}
</style>
