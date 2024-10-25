## 基于知识图谱的应急预案问答系统

### 项目简介

基于知识图谱的应急预案问答系统是一个结合了知识图谱技术、自然语言处理和Web开发的综合性系统。该系统旨在通过构建特定领域的知识图谱，为用户提供智能、高效的问答服务，特别是在应急预案领域，帮助用户快速获取相关信息和指导。

### 主要功能

- 知识图谱构建与展示
- 问答交互
- 数据初始化与更新


### 技术架构

系统由以下技术组成：

**后端:**
- Python 3.7+
- Django 3.2.7
- py2neo

**前端:**
- HTML/CSS/JavaScript
- ECharts

**自然语言处理:**
- Jieba
- 自然语言识别与意图识别


### 使用说明

1. 数据初始化: 执行 Python 脚本（如 `build.py`）将初始数据写入 Neo4j 数据库。
2. 创建知识图谱: 利用提供的 Web 界面进行节点和关系数据的初始化操作。
3. 提出问题: 在问答界面中输入您的问题，系统将根据您的问题内容检索知识图谱并提供答案。


### 联系方式

**微信号：**zt745324325