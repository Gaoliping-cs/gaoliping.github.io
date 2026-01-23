---
layout: default
title: "高立平 – 软件开发工程师"
---

# 高立平（GaoLiping）

软件开发工程师 ｜ Software Engineer  
技术博客｜学习记录

---

## 关于我（About Me）

Hi，我是高立平，一名软件开发工程师，专注于软件系统设计、Web 开发与技术实践。

这个个人网站，主要用于：

- 记录和整理我在软件开发过程中的经验与思考  
- 展示我参与或主导过的技术项目  
- 分享我对新技术、工具和行业趋势的理解

我相信长期、系统地输出高质量内容，是技术人成长和建立个人品牌的重要方式。

---

## 技术方向与能力（Skills & Focus）

我的主要技术方向包括：

- 软件开发与系统设计  
- Web 技术（前端 / 后端）  
- 编程语言与工程实践  
- 技术学习方法与效率工具  

我注重：

- 可维护性与可读性  
- 结构化思考与问题拆解  
- 将复杂问题转化为可执行方案

---

## 项目与实践（Projects）

### 个人技术网站（本网站）
- 基于 GitHub Pages 构建  
- 用于长期沉淀技术内容与个人项目  
- 持续优化网站结构、SEO 与可访问性

### 技术学习与实验项目
- 针对新技术或新工具进行独立研究与实践  
- 编写示例代码与技术总结  
- 在 GitHub 上进行版本管理与迭代

---

## 博客文章（Blog）

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

---

## 在线平台（Profiles）

你也可以在以下平台找到我：

- GitHub：[Gaoliping-cs](https://github.com/Gaoliping-cs)  
- X / Twitter：[高立平](https://x.com/golpng157682)
- Medium：[高立平](https://medium.com/@glpdoctor)

---

## 联系方式（Contact）

如果你希望交流技术、项目或合作机会，欢迎通过以上平台联系我。

---

<!-- JSON-LD Person schema -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "高立平",
  "url": "https://gaoliping.com/",
  "jobTitle": "软件开发工程师",
  "sameAs": [
    "https://github.com/Gaoliping-cs",
    "https://x.com/golpng157682",
    "https://medium.com/@glpdoctor"
  ]
}
</script>
