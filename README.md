# homepage

一个简洁美观、响应式的多功能个人主页模板，适合开发者、极客、博主展示自我、作品、友链、导航等内容。

copy of [Deer](https://github.com/deerwan) 
---

## ✨ 特性

- 个人简介、技能、兴趣展示
- 博客、导航、留言、友链等多区块
- 自定义常用导航
- 友链申请自动推送（支持 Telegram/飞书）
- GitHub Discussions/Issues 留言板
- 网易云音乐播放器
- 响应式设计，适配 PC & 移动端
- SEO 优化，社交媒体预览
- 丰富图标，极简加载动画

---

## 🚀 快速部署

1. **Fork 本仓库** 到你的 GitHub 账号。
2. 进入仓库 `Settings` → `Pages`，选择 `main` 分支，保存。
3. 访问自动生成的网址即可上线。

> 也可用 Cloudflare Pages，直接导入仓库、默认设置一键部署。

---

## 🗂️ 目录结构

```
homepage/
├── assets/         # 静态资源
│   ├── css/        # 样式
│   ├── fonts/      # 字体
│   ├── img/        # 图片
│   ├── js/         # 脚本
│   └── sounds/     # 音效
├── index.html      # 主页入口
├── manifest.json   # PWA 配置
├── push_friend_link.js # 友链推送脚本
├── web.config      # 部署配置
├── CNAME           # 自定义域名
├── LICENSE         # 许可证
└── README.md
```

---

## ⚙️ 配置说明

- **友链推送**：如需自动推送到 Telegram/飞书，配置 `push_friend_link.js` 并在 Cloudflare Worker 设置环境变量。
- **API 配置**：在 `main.js` 填写壁纸、一言、友链等 API 地址。
- **留言板**：用 [Giscus](https://giscus.app/zh-CN) 配置 GitHub Discussions 留言。

---

## 📄 License

Apache-2.0 license

---

## 🤝 贡献

欢迎 PR、Issue 反馈与贡献！