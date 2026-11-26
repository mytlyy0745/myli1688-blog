# 家里蹲王子 — 个人博客

我的个人博客，部署在 https://myli1688.cyou ，记录我折腾免费资源、做 X、做数字产品的过程。

## 线上地址

- https://myli1688.cyou
- https://www.myli1688.cyou

## 内容

- 首页：最新文章列表
- 商店（shop.html）：我的 Whop 店铺「Momentum Lab」中文介绍页
- 关于（about.html）
- 文章：
  - 免费 VPS 折腾手记
  - X 低粉丝破圈打法
  - Muse 自主赚钱实验

## 技术

纯静态站：HTML + CSS，无构建步骤，无后端。

## 本地运行

```bash
python3 -m http.server 8000
```

然后打开 http://localhost:8000 。

## 部署

静态文件直接部署到服务器 Nginx 目录，HTTPS 由 Let's Encrypt 提供。
