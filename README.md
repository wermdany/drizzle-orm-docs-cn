> [!WARNING]
> **AI 翻译声明**：本 README 由 AI 从英文原版翻译而来，内容可能与原文存在出入，仅供参考。
> 如需获取最准确、最新的信息，请以原始仓库为准：
> - 原仓库：https://github.com/drizzle-team/drizzle-orm-docs
> - 官方文档站：https://orm.drizzle.team

## 🚀 项目结构

MDX 文件位于以下目录：

```text
├── src/
│   ├── content/
│   │   └── docs
```

公告（Announcements）Markdown 文件：

```text
├── src/
│   ├──data/
│   │   └── announcements
```

路线图（Roadmap）Markdown 文件：

```text
├── src/
│   ├──data/
│   │   └── roadmap.md
```

Shipping 板块的 YAML 文件：

```text
├── src/
│   ├──data/
│   │   └── shipping.yaml
```

```
progress: number
weeks:
  - date:
      start: "YYYY-MM-DD"
    details:
      - string
```


## 🧞 命令

所有命令都在项目根目录下、从终端运行：

| 命令                      | 作用                                             |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | 安装依赖                                         |
| `pnpm run dev`             | 在 `localhost:4321` 启动本地开发服务器           |
| `pnpm run build`           | 将生产站点构建到 `./dist/`                       |
| `pnpm run preview`         | 在本地预览构建结果（部署前）                     |
| `pnpm run astro ...`       | 运行 CLI 命令，如 `astro add`、`astro check`     |
| `pnpm run astro -- --help` | 查看 Astro CLI 的使用帮助                        |

## 📄 许可证

本仓库中的文档采用 [Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE) 许可协议。在注明适当出处的前提下，你可以自由地以任何媒介或格式复制、再分发和改编这些内容，包括用于商业用途。

版权所有 © Drizzle Team。

### 署名与规范链接

当你再分发或改编本文档（镜像站、离线文档浏览器、翻译版本等）时，你必须按以下方式署名：

1. 注明作者为 **Drizzle Team**，并声明内容采用 CC BY 4.0 许可，同时附上指向[许可证](https://creativecommons.org/licenses/by/4.0/)的链接。
2. 将每个再分发的页面链接到其在 `https://orm.drizzle.team` 上的原始页面，例如 `src/content/docs/select.mdx` 的副本应链接到 `https://orm.drizzle.team/docs/select`。
3. 说明你是否修改了内容。
4. 如果你将文档作为网页重新发布，每个此类页面都必须声明原始页面为其规范 URL（canonical URL），以便搜索引擎将 `orm.drizzle.team` 视为来源。仅提供一个可见链接是不够的：

```html
<link rel="canonical" href="https://orm.drizzle.team/docs/select" />
```

Drizzle 名称与徽标不在本许可证的覆盖范围内。
