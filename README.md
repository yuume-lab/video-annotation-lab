# 视频标注维度训练参考站

视频标注维度单页训练参考站，用于解释低质量筛选、视频标签挂载、caption 描述和质检复盘。

公开版本使用脱敏示意素材，不包含内部项目素材、客户信息或飞书图片链接。

## 本地预览 · Local preview

```bash
npm run dev          # python3 -m http.server 5173
# open http://localhost:5173
```

Any static file server works — there is no build step.

## 结构 · Structure

- `index.html` — page markup + inline interaction scripts
- `site.css` — page styles
- `assets/video-annotation-board.png` — generated anonymized training visual
- `assets/dimensions/tags/*.webp` — generated dimension tag examples
- `assets/caption/caption-layup-sample.mp4` — generated caption sample video
- `placeholder.svg` — favicon

## 部署 · Deploy

Zero-config static deploy on Vercel (see `vercel.json`: no build, output = repo root).
