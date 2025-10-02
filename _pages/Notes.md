---
layout: archive
title: "学习笔记"
permalink: /Notes/
author_profile: true
---

{% include base_path %}

# 课程笔记

## 物理课程
* [理论力学](/Notes/theoretical-mechanics/)
* [数学物理方法](/Notes/mathematical-physics/)
* [量子力学](/Notes/quantum-mechanics/)

## 数学课程
* [高等数学](/Notes/calculus/)
* [线性代数](/Notes/linear-algebra/)
* [概率论](/Notes/probability/)

## 编程相关
* [Python学习笔记](/Notes/python/)
* [C++学习笔记](/Notes/cpp/)

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
3. 使用 Markdown 格式编写笔记内容;
            max-width: 800px;
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
   <details><summary>点击展开 </summary>
  <div class="timeline-container">
        <!-- 2022 秋 -->
    <div class="timeline-item">
      <div class="timeline-node"></div>
        <div class="content">
                <h3>你好, EECS</h3>
                <span class="time">2022 秋</span>
                <p>入燕园，初窥计算机语言与 Github</p>
        </div>
    </div>
    </div>
</details>



## 111

{% assign paths = "nameofthemd.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}
