## 2025-08-08

- 更新 `hugo.toml`：新增 `publishDir = 'docs'`，将生成目录从 `public` 改为 `docs`。
- 提示：GitHub Pages 可在 Settings → Pages 中选择 Branch `main`，Folder `/docs`。
- 后续：运行 `hugo` 重新生成站点，输出将位于 `docs/`。

- 更新 `folder-alias.json`：补充/完善目录与文件注释（新增 `assets/`、`archetypes/`、`content/docs`、`content/posts`、`layouts/`、`resources/`、`static/`、`themes/` 等条目），用于在编辑器中快速了解各路径用途。

- 再次更新 `folder-alias.json`：为 `content/` 下各示例与博客 Markdown 文件逐一添加中文注释（包含 `example/`、`shortcodes/`、`table-of-contents/` 及 `posts/` 全部示例文件）。

- 本地化 `content.en/global/folder-alias.md`：改为全英文说明与示例。
- 本地化 `content.zh/global/folder-alias.md`：改为全中文说明与示例（补充中文使用步骤）。


- 更新 `content/_index.md`：将列表改为层级有序列表，并将第二项改为指向文档页面的链接：`[folder-alias](/docs/global/folder-alias/)`。
