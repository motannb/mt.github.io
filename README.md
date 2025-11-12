![Github Forks](https://img.shields.io/github/forks/motannb/mt.github.io?style=flat)
![Github Stars](https://img.shields.io/github/stars/motannb/mt.github.io?style=flat)
![License](https://img.shields.io/github/license/motannb/mt.github.io)

# Mt的学术主页 | Mt's Academic Homepage

## 预览 | Preview
现代化的学术个人主页，展示研究成果、项目经历和学术荣誉。

A modern academic personal homepage showcasing research achievements, project experience, and academic honors.

## 介绍 | Introduction

这是**Mt的学术个人主页**，专注于展示：
- 🎓 教育背景：北京科技大学（本科）、中南大学（硕士）
- 🔬 研究方向：红外测温技术、计算机视觉、智能传感
- 📝 学术成果：IEEE TIM期刊论文、YAC2025最佳论文奖
- 🏆 竞赛获奖：省级竞赛多项奖项

This is **Mt's academic homepage**, focusing on:
- 🎓 Education: USTB (Bachelor), CSU (Master)
- 🔬 Research: Infrared Temperature Measurement, Computer Vision, Intelligent Sensing
- 📝 Publications: IEEE TIM papers, YAC2025 Best Paper Award
- 🏆 Awards: Multiple provincial competition awards

## 特色 | Features

✨ 现代化设计风格，类似SuperDesign  
🎨 渐变色彩方案，视觉效果优雅  
📱 完全响应式布局，适配各种设备  
🚀 平滑动画效果，提升用户体验  
📊 清晰的学术成果展示  

✨ Modern design style, similar to SuperDesign  
🎨 Gradient color scheme with elegant visual effects  
📱 Fully responsive layout for all devices  
🚀 Smooth animations for enhanced UX  
📊 Clear academic achievement presentation  

## 快速开始 | Getting Started

### 1. Fork 该仓库 | Fork this repository
```bash
git clone https://github.com/motannb/mt.github.io.git
cd mt.github.io
```

### 2. 自定义内容 | Customize Content

编辑以下文件以更新您的个人信息：

- `contents/config.yml` - 网站标题和版权信息
- `contents/home.md` - 个人简介和教育背景
- `contents/publications.md` - 学术论文和专利
- `contents/awards.md` - 获奖经历
- `contents/experience.md` - 研究和项目经历
- `static/assets/img/` - 替换背景图片和个人照片

### 3. 本地预览 | Local Preview

使用任何HTTP服务器预览网站，例如：

```bash
# 使用Python
python -m http.server 8000

# 或使用Node.js
npx http-server
```

然后访问 `http://localhost:8000`

### 4. 部署 | Deploy

提交更改并推送到GitHub：

```bash
git add .
git commit -m "Update personal information"
git push origin main
```

在GitHub仓库设置中启用GitHub Pages，选择main分支。

## 技术栈 | Tech Stack

- 🎨 Bootstrap 5 - 响应式框架
- 📝 Marked.js - Markdown渲染
- 🔢 MathJax - 数学公式支持
- ⚙️ JS-YAML - 配置文件解析
- 💅 Custom CSS - 现代化样式

## License

MIT License. 你可以自由使用和修改此模板。

Copyright Mt, 2024-2025.
