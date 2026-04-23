# Shrub New Media Proposal

这是“灌木文化新媒体部门宣传网站需求提案”的静态网站版本，可部署到 GitHub Pages、Cloudflare Pages、Netlify、Vercel 或任意静态托管服务。

## 目录结构

- `index.html`：对外访问的首页。
- `assets/logo/`：公司 logo 素材。
- `assets/references/`：网站风格参考图。
- `assets/videos/`：短视频案例，已改为适合网页发布的英文文件名。
- `assets/videos/MEDIA_MANIFEST.md`：视频文件名与原始文件名映射表。
- `docs/proposal.md`：可编辑的文字版需求提案。

## GitHub Pages 发布方式

1. 在 GitHub 新建一个公开仓库，建议名称：`shrub-new-media-proposal`。
2. 将本目录下的全部文件上传到仓库根目录。
3. 进入仓库 `Settings > Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. `Branch` 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub 生成访问地址。

默认外部访问地址通常为：

```text
https://你的用户名.github.io/shrub-new-media-proposal/
```

## 维护方式

- 修改页面设计：编辑 `index.html`。
- 替换参考图片：替换 `assets/references/` 下同名文件。
- 替换 logo：替换 `assets/logo/` 下同名文件。
- 替换视频：替换 `assets/videos/` 下同名文件，并同步更新 `MEDIA_MANIFEST.md`。

## 注意事项

当前视频总量约 0.25GB，适合做评审演示。GitHub Pages 不适合长期承载大量高清视频；如果后续视频数量继续增加，建议将视频放到对象存储或视频平台，再在网页中嵌入链接。
