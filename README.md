# Tiger Blog 🐯

> 一个专业的商务风格博客系统，基于 Next.js 16 构建

简约、专业、高效的个人博客解决方案。采用商务风格设计，让您的博客更具专业感。无需服务器，零成本部署。

## ✨ 特性

- 🎨 **商务风格设计** - 深蓝配色、简洁布局、专业氛围
- 🌓 **暗色模式** - 支持亮色/暗色主题自动切换
- 📱 **响应式设计** - 完美适配桌面、平板和移动设备
- ⚡ **极速加载** - Next.js 16 + Turbopack 构建，性能卓越
- 🔧 **可视化管理** - 通过 GitHub App 管理博客内容，无需写代码
- 🚀 **一键部署** - 支持 Vercel、Cloudflare Pages 等平台
- 📝 **Markdown 支持** - 使用 Markdown 轻松撰写博客
- 🎭 **动画效果** - 简洁克制的过渡动画，提升用户体验

## 🎨 设计风格

### 配色方案

| 类型 | 亮色模式 | 暗色模式 |
|------|----------|----------|
| 主色 | 深蓝 `#1e3a5f` | 藏青 `#0f2744` |
| 辅助色 | 金色 `#c9a227` | 银灰 `#8c8c8c` |
| 背景 | 纯白 `#ffffff` | 深蓝黑 `#0d1b2a` |
| 文字 | 深灰 `#333333` | 浅灰 `#e0e0e0` |

### 设计特点

- 📐 规整对称的网格布局
- 🔲 简洁的卡片设计（小圆角 8-12px）
- ✨ 克制的动画效果（200-300ms 过渡）
- 📏 充足的留白空间
- 🎯 清晰的信息层级

## 🛠️ 技术栈

- **Next.js 16** - React 全栈框架
- **React 19** - 最新 React 版本
- **TypeScript** - 类型安全
- **Tailwind CSS v4** - 原子化样式
- **Framer Motion** - 动画效果
- **GitHub App** - 内容管理

## 📦 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/scfast003/tiger-blog.git
cd tiger-blog
pnpm install
```

### 2. 本地开发

```bash
pnpm dev
```

访问 `http://localhost:2025` 查看效果

### 3. 构建部署

```bash
pnpm build
```

## 🚀 一键部署

### Vercel 部署（推荐）

1. Fork 本项目到你的 GitHub
2. 登录 [Vercel](https://vercel.com)，导入项目
3. 无需配置，直接点击部署
4. 约 60 秒后部署完成

### 环境变量配置

```ts
NEXT_PUBLIC_GITHUB_OWNER    // 你的 GitHub 用户名
NEXT_PUBLIC_GITHUB_REPO     // 仓库名称
NEXT_PUBLIC_GITHUB_BRANCH   // 分支名（默认 main）
NEXT_PUBLIC_GITHUB_APP_ID   // GitHub App ID
```

## 🔑 创建 GitHub App

1. 进入 GitHub **Settings** → **Developer Settings** → **GitHub Apps**
2. 点击 **New GitHub App**
3. 设置仓库 **Contents** 的 **Read and Write** 权限
4. 创建 **Private Key** 并保存
5. 安装 App 到你的博客仓库

> ⚠️ 请妥善保管 Private Key，不要上传到公开仓库

## 📁 项目结构

```
src/
├── app/                 # 页面路由
│   ├── (home)/         # 首页相关
│   ├── blog/           # 博客页面
│   └── layout.tsx      # 全局布局
├── components/          # 公共组件
│   ├── cards/          # 卡片组件
│   ├── ui/             # UI 组件
│   └── layout/         # 布局组件
├── hooks/              # 自定义 Hooks
├── config/             # 配置文件
├── styles/             # 全局样式
└── lib/                # 工具函数
```

## ⚙️ 自定义配置

### 网站信息

首页右上角有配置按钮，可以可视化配置：
- 网站标题
- 个人简介
- 社交链接
- 主题设置

### 首页卡片

编辑 `src/app/(home)/` 目录下的文件：
- `hi-card.tsx` - 欢迎卡片
- `art-card.tsx` - 作品展示
- `social-buttons.tsx` - 社交按钮

## 📝 写博客

1. 点击页面上的 **+** 按钮
2. 上传图片（建议宽度不超过 1200px）
3. 使用 Markdown 撰写内容
4. 保存后等待自动部署

## 🎯 商务风格亮点

| 特点 | 描述 |
|------|------|
| 🏢 专业配色 | 深蓝+金色，沉稳大气 |
| 📊 清晰布局 | 网格对齐，层次分明 |
| ⚡ 简洁动效 | 克制优雅，不喧宾夺主 |
| 🖼️ 精致细节 | 阴影、圆角、间距精心调校 |
| 📱 全端适配 | 桌面/平板/手机完美呈现 |

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add AmazingFeature'`)
4. 推送分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 许可证

本项目基于 [MIT 许可证](LICENSE) 开源。

## 🙏 致谢

- 原项目 [2025-blog-public](https://github.com/YYsuni/2025-blog-public) by YYsuni
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)

---

如有问题，欢迎提交 [Issue](https://github.com/scfast003/tiger-blog/issues) 或联系作者。

Made with ❤️