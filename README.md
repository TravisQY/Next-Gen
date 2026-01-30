

# 🚀 Next-Gen Tech Coming Soon Page

一个极简主义、高性能的科技感“网站建设中”单页面。通过增强的动态神经网络粒子背景和霓虹发光视觉，为您的项目提供震撼的初次印象。采用全 CDN 依赖设计，无需任何构建流程，即传即用。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Style](https://img.shields.io/badge/style-minimalist-050508)
![Performance](https://img.shields.io/badge/performance-smooth-3b82f6)

![image](https://github.com/TravisQY/Next-Gen/blob/master/Preview.png)

## ✨ 项目亮点

- **高强度视觉冲击**：
  - **神经网络粒子背景**：升级版 `tsParticles` 配置，线条更清晰，带点亮闪烁效果。
  - **霓虹数字倒计时**：使用 `Orbitron` 科技字体，配合双重发光滤镜（Glow Filter）。
  - **动态系统状态栏**：具备呼吸灯效果的实时状态指示器。
- **极致极简**：
  - **0 本地依赖**：全部功能通过 CDN 在线加载，无需安装任何 `node_modules`。
  - **单文件架构**：代码完全集中在 `index.html` 中，加载速度极快。
- **强交互性**：
  - 粒子背景支持鼠标跟随、吸附及点击扩散效果。
  - 完美适配移动端、平板与 PC。

## 🛠️ 核心驱动

- **排版引擎**: [Tailwind CSS](https://tailwindcss.com/)
- **粒子物理**: [tsParticles (Slim)](https://particles.js.org/)
- **图标系统**: [Lucide Icons](https://lucide.dev/)
- **数字美学**: [Google Fonts (Orbitron)](https://fonts.google.com/)

## 🚀 一键部署到 GitHub Pages

1. **新建仓库**：在 GitHub 上创建一个新的仓库（例如 `tech-page`）。
2. **上传文件**：将本项目中的 `index.html` 上传到仓库根目录。
3. **开启服务**：
   - 进入 **Settings** (设置) -> **Pages**。
   - 在 **Branch** 选项中选择 `main` (或 `master`) 分支。
   - 点击 **Save**。
4. **即刻访问**：大约 1 分钟后，您的网站将通过 `https://<用户名>.github.io/<仓库名>/` 开启。

## ⚙️ 个性化配置

### 1. 修改上线日期
在 `index.html` 的末尾脚本中修改 `targetDate`：
```javascript
// 默认设置为当前日期后 14 天
const targetDate = new Date();
targetDate.setDate(targetDate.getDate() + 14);

// 设置为特定日期示例:
// const targetDate = new Date('2025-10-01T00:00:00');
```

### 2. 调整粒子强度
在 `tsParticles.load` 配置项中寻找：
- `particles.number.value`: 调整粒子密度（默认 100）。
- `particles.line_linked.opacity`: 调整连线清晰度（默认 0.4）。
- `particles.move.speed`: 调整粒子漂移速度。

### 3. 修改品牌名称
定位到 HTML 中的 `<h1>` 标签，更改 `CORE` 与 `ALPHA` 为您的品牌词。

## 📄 许可证

本项目采用 **MIT License**。您可以自由地使用、修改并分发该模板，甚至用于商业用途。

---

**💡 开发建议**: 建议在静态文件服务器（如 Live Server）下运行以获得最佳预览效果。如果这对你有帮助，别忘了点一个 ⭐️！
