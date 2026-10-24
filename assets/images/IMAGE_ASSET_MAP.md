# 图片资源管理 / Image Asset Registry

所有图像放在 `assets/images/`，网页通过 Markdown 中的相对路径引用。当前为**原创 SVG 示例图**，无需外部图片服务器。

| 文件路径 | 页面用途 | 引用状态 |
|---|---|---|
| `assets/images/academic-portrait.svg` | 个人主页示例头像（插画，不是真人） | `content/profile.md` 的 `photo:` |
| `assets/images/human-ai-research.svg` | AI 研究项目缩略图 | `content/projects.md` 第一项 `Image:` |
| `assets/images/parametric-fabrication.svg` | 参数化设计项目缩略图 | `content/projects.md` 第二项 `Image:` |
| `assets/images/research-landscape.svg` | 自然风景横幅备用资源 | 暂未引用 |

## 更换图片

1. 在 GitHub 仓库的 `assets/images/` 中上传新图片（建议 WebP/JPG，单张尽量小于 500 KB）。
2. 编辑 `content/profile.md` 中的 `photo:`，或 `content/projects.md` 中对应的 `Image:`，填入路径，例如 `assets/images/new-photo.webp`。
3. 点击 Commit changes，GitHub Pages 部署后刷新网站即可看到新图片。
4. 请勿上传包含个人敏感信息的文件；公开仓库中的图片可被任何人访问。

## 商用及演示说明

这些为虚构示例学术主页的素材，不对应真实科研论文或人物。若使用真人照片或谷歌图片搜索结果，先核对图片授权，不能因为可搜索就认为可以商用。
