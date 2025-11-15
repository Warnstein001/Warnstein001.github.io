---
layout: default
title: Blog Posts
---
<div class="post-list">
    <article class="post-card">
        <a href="/methods/十六字方针" class="post-link">
            <div class="post-image">
                <img src="/assets/十六字方针.jpg" alt="Learning Methods">
            </div>
            <div class="post-content">
                <h2>学习方法：十六字方针</h2>
                <p>学以致用、学而时习、循序渐进、持之以恒 —— 探索高效学习的核心方法论</p>
                <div class="post-meta">
                    <span class="post-date">📅 2025-11-14</span>
                    <span class="post-tags">#学习方法 #效率 #方法论</span>
                </div>
            </div>
        </a>
    </article>
    

    <!-- 可以继续添加更多文章 -->
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
    background: #f5f5f5;
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
