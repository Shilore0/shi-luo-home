# home.github.io

[![License](https://img.shields.io/github/license/Shilore0/home.github.io.svg)](/LICENSE)

## 个人主页

Shilore 的个人静态主页。

灵感来源：

- 基于 [Dmego Home Page](https://github.com/dmego/home.github.io) 模板
- [Vno](https://github.com/onevcat/vno-jekyll) Jekyll 主题
- [Mno](https://github.com/mcc108/mno) Ghost 主题（部分加载效果）

## 在线预览

- GitHub Pages: `https://shilore0.github.io/home.github.io/`

## 快速开始

- Fork 后启用 GitHub Pages：见 [docs/quickstart.md](docs/quickstart.md)
- 本地预览：`python3 -m http.server 8080` 或 `npx serve .`

## 功能概览

- 一言（Hitokoto）：页面加载时调用 `https://v1.hitokoto.cn`
- Bing 壁纸：页面读取 `assets/json/images.js`，背景轮播
- WakaTime 主题：页面读取 `assets/json/config.js` 自动应用日主题

## 自定义

- `index.html`：头像、标题、导航链接、社交链接
- `assets/json/config.js`：WakaTime 配置
