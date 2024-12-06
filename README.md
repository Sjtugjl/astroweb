# 个人博客网站

这是一个使用 Astro 构建的个人博客网站,用于展示个人介绍、作品集和博客文章。

## 功能特性

- � 首页:个人简介和最新博客文章展示
- 📝 博客:发布和展示博客文章
- 🎨 作品集:展示个人项目作品
- 👤 关于:详细的个人介绍
- 📱 响应式设计:适配移动端和桌面端
- 🌙 深色模式:支持深色/浅色主题切换

## 项目结构

```bash
src/
├── components/     # 可复用的组件
│   ├── Header.astro    # 网站头部导航
│   ├── Footer.astro    # 网站底部
│   ├── BlogCard.astro  # 博客卡片组件
│   └── ProjectCard.astro # 项目卡片组件
├── layouts/       # 页面布局模板
│   └── BaseLayout.astro # 基础页面布局
├── pages/         # 页面路由
│   ├── index.astro     # 首页
│   ├── blog/           # 博客相关页面
│   ├── projects/       # 作品集页面
│   └── about.astro     # 关于页面
├── content/       # 内容集合
│   ├── blog/      # 博客文章 
│   └── projects/  # 项目介绍
└── styles/        # 样式文件
    └── global.css # 全局样式
```

## 开发指南

1. 安装依赖:
```bash
npm install
```

2. 启动开发服务器:
```bash
npm run dev
```

3. 构建网站:
```bash
npm run build
```

## 技术栈

- 框架: [Astro](https://astro.build)
- 样式: CSS/SCSS
- 内容管理: Markdown
- 部署: Vercel/Netlify

## 主要功能说明

### 博客系统
- 支持 Markdown 写作
- 文章分类和标签
- 文章目录
- 评论系统

### 作品集展示
- 项目卡片展示
- 项目详情页
- 技术栈标签
- 在线预览链接

### 个人介绍
- 个人技能展示
- 工作经历
- 教育背景
- 联系方式

### 其他功能
- SEO 优化
- 站内搜索
- RSS 订阅
- 网站统计

## 开发规范

### Git 提交规范
```
feat: 新功能
fix: 修复问题
docs: 文档修改
style: 代码格式修改
refactor: 代码重构
test: 测试用例修改
chore: 其他修改
```

### 文件命名规范
- 组件文件: PascalCase (如 `BlogCard.astro`)
- 页面文件: kebab-case (如 `blog-post.astro`)
- 样式文件: kebab-case (如 `global-styles.css`)

## 部署说明

1. 推送代码到 GitHub 仓库
2. 连接 Vercel/Netlify 进行自动部署
3. 配置自定义域名(可选)

## 贡献指南

1. Fork 本仓库
2. 创建新的功能分支
3. 提交代码
4. 创建 Pull Request

## 许可证

MIT License