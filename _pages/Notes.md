---
layout: archive
title: "学习笔记"
permalink: /Notes/
author_profile: true
---

{% include base_path %}

<style>
    .notes-container {
        max-width: 900px;
        margin: 0 auto;
        padding: 20px;
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
        background-color: transparent;
    }
    
    .subject-section {
        margin-bottom: 40px;
    }
    
    .subject-title {
        color: #2c3e50;
        font-size: 1.8em;
        font-weight: 600;
        margin-bottom: 20px;
        padding-bottom: 10px;
        border-bottom: 2px solid #3498db;
    }
    
    .notes-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
        gap: 20px;
        margin-bottom: 30px;
    }
    
    .note-card {
        background: white;
        border-radius: 8px;
        box-shadow: 0 2px 15px rgba(0,0,0,0.1);
        transition: transform 0.2s ease, box-shadow 0.2s ease;
        overflow: hidden;
    }
    
    .note-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 20px rgba(0,0,0,0.15);
    }
    
    .note-card-header {
        background: #3498db;
        color: white;
        padding: 15px 20px;
    }
    
    .note-card-title {
        margin: 0;
        font-size: 1.2em;
        font-weight: 500;
    }
    
    .note-card-content {
        padding: 15px 20px;
        color: #666;
    }
    
    .note-card-link {
        color: #2c3e50;
        text-decoration: none;
        display: block;
    }
    
    .note-card-link:hover {
        text-decoration: none;
    }
    
    .note-description {
        font-size: 0.9em;
        line-height: 1.5;
        margin: 10px 0;
    }
</style>

<div class="notes-container">
    <div class="subject-section">
        <h2 class="subject-title">物理课程</h2>
        <div class="notes-grid">
            <a href="/Notes/theoretical-mechanics/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">理论力学</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">经典力学的进阶课程，包括拉格朗日力学、哈密顿力学等内容</p>
                    </div>
                </div>
            </a>
            <a href="/Notes/mathematical-physics/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">数学物理方法</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">物理学中的重要数学工具，包括复变函数、特殊函数等</p>
                    </div>
                </div>
            </a>
            <a href="/Notes/quantum-mechanics/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">量子力学</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">微观世界的基本理论，包括波函数、薛定谔方程等</p>
                    </div>
                </div>
            </a>
        </div>
    </div>

    <div class="subject-section">
        <h2 class="subject-title">数学课程</h2>
        <div class="notes-grid">
            <a href="/Notes/calculus/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">高等数学</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">微积分与数学分析的基础知识</p>
                    </div>
                </div>
            </a>
            <a href="/Notes/linear-algebra/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">线性代数</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">矩阵、向量空间等线性代数基础</p>
                    </div>
                </div>
            </a>
            <a href="/Notes/probability/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">概率论</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">概率统计的基本理论与应用</p>
                    </div>
                </div>
            </a>
        </div>
    </div>

    <div class="subject-section">
        <h2 class="subject-title">编程相关</h2>
        <div class="notes-grid">
            <a href="/Notes/python/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">Python 学习笔记</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">Python 编程基础与科学计算应用</p>
                    </div>
                </div>
            </a>
            <a href="/Notes/cpp/" class="note-card-link">
                <div class="note-card">
                    <div class="note-card-header">
                        <h3 class="note-card-title">C++ 学习笔记</h3>
                    </div>
                    <div class="note-card-content">
                        <p class="note-description">C++ 编程基础与高级特性</p>
                    </div>
                </div>
            </a>
        </div>
    </div>
</div>

