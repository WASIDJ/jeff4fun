# Astro 入门套件：博客

```sh
bun create astro@latest -- --template blog
```

> 🧑‍🚀 **经验丰富的宇航员？** 删除此文件，玩得开心！

功能特性：

- ✅ 极简样式（自由定制！）
- ✅ Lighthouse 性能 100/100
- ✅ SEO 友好，支持规范 URL 与 OpenGraph
- ✅ 站点地图
- ✅ RSS 订阅
- ✅ Markdown & MDX 支持

## 🚀 项目结构

Astro 项目目录如下：

```text
├── public/
├── src/
│   ├── components/   # 组件
│   ├── content/      # 内容集合
│   ├── layouts/      # 布局
│   └── pages/        # 页面
├── astro.config.mjs
├── README.md
├── package.json
└── tsconfig.json
```

Astro 会把 `src/pages/` 中的 `.astro` 或 `.md` 文件当成路由，文件名即路径。

`src/components/` 无特殊约束，可放 Astro/React/Vue/Svelte/Preact 组件。

`src/content/` 存放“内容集合”，用 `getCollection()` 获取 `src/content/blog/` 中的文章，并可借助可选模式对 frontmatter 做类型校验。详见 [Astro 内容集合文档](https://docs.astro.build/zh-cn/guides/content-collections/)。

静态资源（如图片）放在 `public/`。

## 🧞 常用命令

均在项目根目录执行：

| 命令                   | 作用                           |
| :--------------------- | :----------------------------- |
| `bun install`          | 安装依赖                       |
| `bun dev`              | 启动本地开发服务器 `localhost:4321` |
| `bun build`            | 构建生产版本到 `./dist/`       |
| `bun preview`          | 本地预览构建结果               |
| `bun astro ...`        | 运行 Astro CLI，如 `astro add`、`astro check` |
| `bun astro -- --help`  | 查看 Astro CLI 帮助            |

## 👀 了解更多？

阅读[官方文档](https://docs.astro.build/zh-cn/)或加入 [Discord 社群](https://astro.build/chat)。

## 致谢

本主题灵感源自可爱的 [Bear Blog](https://github.com/HermanMartinus/bearblog/)。