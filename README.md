# blog-images

个人博客公开图片仓库，通过 jsDelivr 提供 CDN 访问。

## 目录结构

```text
blog-images/
├── 2026/
│   ├── article-a/
│   └── article-b/
└── common/
```

- `YYYY/<article-slug>/`：按年份和文章短名保存正文图片。
- `common/`：保存头像、站点背景等多处复用的公开图片。
- `article-a`、`article-b` 仅为结构示例，使用时替换为真实文章短名。

## CDN 地址

```text
https://cdn.jsdelivr.net/gh/MegumiKato0/blog-images@main/<文件路径>
```

本仓库完全公开，请勿上传隐私图片、凭证、客户资料或未公开商业素材。