# 辨证云（R）中医 AI 数智平台 · 产品介绍

静态产品介绍页，通过 GitHub Pages 发布。

## 站点结构

```
.
├── index.html      # 单页产品介绍（自包含样式与交互）
├── images/         # 30 张页面截图（WebP, quality 95）
└── .nojekyll       # 跳过 Jekyll 构建，加快发布
```

## 发布说明

- 纯静态站点，无后端依赖、无构建步骤，克隆后直接打开 `index.html` 即可查看。
- 图片统一转为 WebP（quality 95，PSNR 45–47.6 dB，视觉无损），体积由 75 MB 降至 14 MB。
- 图片均启用 `loading="lazy"` 与 `decoding="async"`，滚动到可视区域才加载，避免首屏卡顿。
- 点击任意截图可放大查看；放大后可通过链接跳转对应演示视频。

## 本地预览

```bash
python3 -m http.server 8089
# 浏览器访问 http://127.0.0.1:8089/
```

## 内容指标

- 覆盖 400+ 病症
- 95% 符合率（经双盲验证）
