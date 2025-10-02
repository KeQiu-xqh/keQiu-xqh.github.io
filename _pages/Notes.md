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

# 添加新笔记

如何添加新的笔记：
1. 在 `_Notes` 文件夹中创建新的 .md 文件
2. 文件开头添加以下格式：
```yaml
---
title: "笔记标题"
collection: Notes
permalink: /Notes/笔记标识符/
tags:
  - 标签1
  - 标签2
---
```
3. 使用 Markdown 格式编写笔记内容
            margin: 0 auto;
        }

        /* 时间线竖线 */
        .timeline-container::after {
            content: '';
            position: absolute;
            width: 2px;
            background-color: #3498db;
            top: 0;
            bottom: 0;
            left: 20px;
        }

        /* 单个时间线项目 */
        .timeline-item {
            position: relative;
            margin-bottom: 40px;
            padding-left: 60px;
        }

        /* 时间节点圆点 */
        .timeline-node {
            position: absolute;
            left: 10px;
            top: 5px;
            width: 20px;
            height: 20px;
            background: #fff;
            border: 3px solid #3498db;
            border-radius: 50%;
            z-index: 1;
        }

        /* 内容区域 */
        .content {
            position: relative;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        /* 时间标题 */
        .content h3 {
            color: #3498db;
            margin-bottom: 8px;
        }

        /* 时间日期 */
        .time {
            display: block;
            color: #666;
            font-size: 0.9em;
            margin-bottom: 10px;
        }

        /* 响应式设计 */
        @media (max-width: 600px) {
            .timeline-container::after {
                left: 10px;
            }
            
            .timeline-item {
                padding-left: 40px;
            }
            
            .timeline-node {
                left: 0;
            }
        }
    </style>
