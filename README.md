# FabricUI Physics Receipt (2.5D Interactive Cloth Simulation)

一个可交互的小票 UI Demo：
- 鼠标拖拽小票时，会像布料一样产生拉扯形变
- 带有动态褶皱（SVG turbulence + displacement）效果
- 使用 Canvas + 质点网格（Verlet 思路）实现实时变形

## Preview

打开 `receipt_ui_demo.html` 即可本地预览。

## Features

- 🧵 布料感拖拽交互（鼠标拖拽）
- 📄 小票纹理与排版风格
- 🌊 动态褶皱强度随拖拽变化
- ⚡ 单文件实现，开箱即用

## Quick Start

1. 克隆仓库
2. 直接用浏览器打开 `receipt_ui_demo.html`

或使用本地静态服务器（可选）：

```bash
python -m http.server 8000
```

然后访问：`http://localhost:8000/receipt_ui_demo.html`

## Tech Stack

- HTML5
- CSS3
- JavaScript (Canvas API)
- SVG Filter (`feTurbulence`, `feDisplacementMap`)

## Notes

- 建议使用 Chrome / Edge 最新版本获得最佳性能。
- 若拖拽时感觉过于“软”或“硬”，可调整脚本中的网格与阻尼参数。

## License

MIT
