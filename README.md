# 🌍 World Footprint Map — 便携版

一个可以放在 U 盘里随身携带的旅行足迹地图。

## 📂 文件结构

```
WorldFootprintMap-Portable/
├── index.html           ← 主页面
├── start.bat            ← 双击用浏览器打开
├── libs/
│   ├── leaflet.min.css  ← 地图样式
│   ├── leaflet.min.js   ← 地图引擎
│   └── globe.gl.min.js  ← 3D 地球
└── data/
    └── footprints.json  ← 你的足迹数据
```

## 🚀 使用方法

1. 将整个 `WorldFootprintMap-Portable` 文件夹拷贝到 U 盘
2. 双击 `start.bat`，浏览器会自动打开页面
3. 选择「📂 打开数据文件」加载已有数据，或「✨ 新建空白数据」从头开始
4. 在地图上点击添加足迹，支持城市、国家、日期、笔记、照片

## 💾 数据说明

- 所有足迹数据保存在 `data/footprints.json` 中
- 照片以 base64 格式内嵌在 JSON 里，一个文件包含全部数据
- **Chrome / Edge**：支持自动保存（File System Access API）
- **其他浏览器**：每次修改后自动下载 JSON 文件，手动替换即可
- 也可使用页面上的「📤 Export / 📥 Import」按钮手动备份和恢复

## ✨ 功能

- 🗺️ 2D 地图（OpenStreetMap）
- 🌐 3D 地球视图
- 🔍 城市搜索
- 📸 照片上传（自动压缩）
- 🌏 中英文切换
- 📤 数据导出 / 导入
- 💡 扉页致谢动画

## ⚠️ 注意

- 地图瓦片需要联网加载（OpenStreetMap），代码和数据完全便携
- 建议使用 Chrome 或 Edge 获得最佳体验（自动保存功能）
- 数据文件是纯 JSON，可以用任何文本编辑器查看和修改

## 💝 致谢

献给耐心、善良、博学、乐观的 Sara 老师 ❤️
