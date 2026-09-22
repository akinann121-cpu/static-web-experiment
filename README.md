# 计算机网络实验一：静态网页制作

## 👤 个人信息
*   **姓名**：王炯
*   **学号**：PB24111605
*   **个人主页网址**：[https://akinann121-cpu.github.io/static-web-experiment/](https://akinann121-cpu.github.io/static-web-experiment/)
*   **网页的 HTTP 版本号**：HTTP/2 (表现为 `h2`)

## 📖 实验简介
本实验旨在学习 HTML 页面结构、HTML 常用标记、表格布局以及 CSS 样式表的基本使用方法，并掌握将静态网页部署至 GitHub Pages 的完整流程。

## 📖 版本号检查
网页的 HTTP 版本号：HTTP/2
检查方法及过程：将静态网页部署至 GitHub Pages 后，使用 Chrome 浏览器访问个人主页。按 F12 打开开发者工具，切换至 Network（网络）面板，勾选 Disable cache（停用缓存）并强制刷新页面（Ctrl+F5）。点击首个网络请求，在 Headers（标头）-> General（常规）中查看 Protocol（协议）字段，显示为 h2。因此，该网页采用的 HTTP 协议版本为 HTTP/2。![alt text](<images/屏幕截图 2026-09-22 170026.png>)