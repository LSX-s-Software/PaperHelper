<div align="center">

# PaperHelper

<!-- markdownlint-disable-next-line MD036 -->
_✨ 基于 C# 和 Vue 的多人协作文献管理平台 ✨_

_✨ Author: [LSX-s-Software](https://github.com/LSX-s-Software) | [NagisaCo](https://github.com/NagisaCo/) ✨_
</div>

<p align="center">
  <a href="license">
    <img src="https://img.shields.io/badge/LICENSE-GPLv3-red" alt="license">
  </a>
  <a href="stargazers">
    <img src="https://img.shields.io/github/stars/LSX-s-Software/PaperHelper?color=yellow&label=Github%20Stars" alt="star">
  </a>
  <br/>
  <img src="https://img.shields.io/badge/ASP.Net%20Core-6.0-512BD4" alt="aspnetcore">
  <img src="https://img.shields.io/badge/Vue-3.0-41B784" alt="vue">
</p>
<!-- markdownlint-enable MD033 -->

## 选题动机

写论文时需要查找大量的文献资料，如何管理繁多的文献已经成为摆在一众学生和科研人员面前的问题。现在流行的文献管理系统多只支持英文文献的识别管理，且在多人协同标注、文献库共享等方面均存在局限性。

## 软件功能

- 文献管理
  - 自动识别文献的元数据并归类
  - 通过文献的元数据查询文献
  - 云端文献库

- 跨平台访问

- 多人协同标注

## 技术实现

### 技术路线

- 采用 `Vue` 实现前端页面，提供 GUI 供用户使用本平台。运用开源库实现协同标注功能。
- 采用 `C#` 实现后端，提供用户注册登录、文献自动识别、文件管理等功能。

### 技术难度

- 文章结构丰富多样，难以通用的形式从中提取有用的数据
- 合理管理资源文件，减少服务器开销
- 搭配 `ShareDB` 实现协同功能

## 成员分工
- LSX-s-Software: UI 设计，前端界面，后端功能
- NagisaCo: 数据库设计，后端服务

## 目录结构

```
├── LICENSE
├── README.md              本文件
├── docs                   其他文档
└── paper_helper_frontend  前端项目仓库
```

