# 🍃 Epub Transverter | 极简 ePUB 繁简转换器

一个专为高品质阅读打造的、无损、高效、纯净的 ePUB 电子书繁简转换工具。

👉 **[立即使用在线版](https://your-project-name.vercel.app)** *(更换为你的 Vercel 实际网址)*

---

## ✨ 核心特性 (Features)

* **🔒 100% 隐私安全 (Privacy First)**：所有文件解析、繁简转换、重新打包均在**用户浏览器本地本地（Client-Side）**完成。文件无需上传至任何服务器，彻底杜绝书籍资产泄露的风险。
* **⚡ 秒级无感响应 (Blazing Fast)**：得益于纯前端处理架构，省去了网络上传和下载的等待时间，即便是数十兆的大部头小说也能瞬间完成转换并自动触发下载。
* **🎨 文艺排版优化 (Typography Reborn)**：自动拦截原书中可能导致乱码、补丁字的旧繁体字体样式，强制无损重置为现代全平台高品质无衬线黑体组合（苹果/微软系统级优化），并科学固定行高（1.625），保障极致的阅读舒适度。
* **🔤 全方位转换 (Full Conversion)**：使用高精度 `opencc-js` 引擎，不仅对书籍正文、目录进行词汇级高精度转换，同时自动将**输出文件名**一并转换为简体中文。
* **🌿 纯净无暇 (Pure Experience)**：全站零广告、零追踪、零弹窗，秉承极简主义（Minimalism）设计哲学，只为阅读本身服务。

---

## 🛠️ 技术栈 (Tech Stack)

项目采用高度敏捷、轻量化的现代化前端技术栈构建：

* **Style**: Tailwind CSS 4 & Stone (暖石色) 现代自然视觉系统
* **Core Engine**: [opencc-js](https://github.com/fengkx/opencc-js) (高精度繁简转换)
* **Zip Handler**: [JSZip](https://github.com/Stuk/jszip) (本地解压与无损再封装)
* **Deployment**: Vercel Global CDN (边缘网络加速)

---

## 📦 本地开发与运行 (Local Setup)

由于项目采用 Pure JavaScript 架构，无需任何复杂的 Node.js 环境配置：

1. 克隆本项目到本地：
   ```bash
   git clone [https://github.com/你的用户名/epub-transverter.git](https://github.com/你的用户名/epub-transverter.git)