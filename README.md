# 🍃 Epub Transverter

极简 ePUB 电子书繁简转换工具。无损、高效、纯净。

👉 **[立即使用在线版](https://epub-converter-one.vercel.app/)**

---

## ✨ 核心特性

* **🔒 100% 隐私安全**：纯前端运行。文件完全在本地浏览器解析与转换，绝不上传服务器。
* **⚡ 秒级无感响应**：无需经历网络上传与下载，瞬间完成转换并自动触发下载。
* **🎨 现代排版重置**：自动抹去原书杂乱字体，统一重置为现代系统级黑体，固定 1.625 舒适行高。
* **🔤 文件名同步**：使用高精度 OpenCC 引擎，正文、目录以及输出的文件名同步转换为简体。
* **🌿 极致纯净**：全站零广告、零追踪、零弹窗，只为阅读服务。

---

## 🛠️ 技术栈

* **样式**: Tailwind CSS 4 (Stone 暖石视觉系统)
* **核心**: [opencc-js](https://github.com/fengkx/opencc-js) (高精度繁简转换)
* **解压**: [JSZip](https://github.com/Stuk/jszip) (本地解压与无损封装)
* **托管**: Vercel (全球边缘网络加速)

---

## 📦 本地运行

无需配置任何环境：
1. 克隆项目：`git clone https://github.com/你的用户名/epub-transverter.git`
2. 双击 `index.html` 即可在本地浏览器运行。

---

## 📄 许可证

[MIT License](LICENSE)