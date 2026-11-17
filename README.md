# AutoDL.com 文档中心

AutoDL.com 用户文档。

## 本地预览

```bash
mint dev
```

默认访问 `http://localhost:3000`。

## 校验

```bash
mint validate
mint broken-links --check-anchors
```

## 目录说明

- 页面按栏目存放在对应目录下的 `.mdx` 文件中，导航配置位于 `docs.json`。
- 图片统一存放于 `images/`，按引用页面的目录结构组织；未被引用的文件位于 `images/more/`。
- 旧站 `/docs/...` 路径通过 `docs.json` 中的 `redirects` 重定向到新路径。
