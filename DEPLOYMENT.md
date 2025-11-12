# 部署指南 | Deployment Guide

## 📦 提交更改

### 1. 添加所有修改的文件
```powershell
git add .
```

### 2. 提交更改
```powershell
git commit -m "✨ Update academic homepage with new design and content

- Update academic achievements (2 IEEE TIM papers, YAC2025 Best Paper)
- Add education and competition awards
- Redesign UI with modern SuperDesign-style aesthetics
- Enhance CSS with gradients, animations, and responsive design
- Update README and add CHANGELOG"
```

### 3. 推送到GitHub
```powershell
git push origin main
```

---

## 🌐 启用GitHub Pages

1. 进入你的GitHub仓库页面
2. 点击 **Settings** (设置)
3. 在左侧菜单找到 **Pages**
4. 在 **Source** 下拉菜单中选择 **main** 分支
5. 点击 **Save** (保存)
6. 等待几分钟，你的网站将发布在 `https://motannb.github.io/mt.github.io/`

---

## 🔍 本地预览

### 方法1：使用Python
```powershell
python -m http.server 8000
```
然后在浏览器访问 `http://localhost:8000`

### 方法2：使用Node.js
```powershell
npx http-server
```

### 方法3：使用VS Code插件
安装 **Live Server** 插件，右键点击 `index.html`，选择 **Open with Live Server**

---

## ✅ 检查清单

在部署之前，请确认：

- [ ] 已替换 `static/assets/img/photo.png` 为你的个人照片
- [ ] 已替换 `static/assets/img/background.jpeg` 为你喜欢的背景图
- [ ] 已更新 `contents/config.yml` 中的个人信息
- [ ] 已检查所有链接是否有效
- [ ] 已测试响应式布局（手机/平板/桌面）
- [ ] 已在本地预览确认无误

---

## 🎨 自定义主题色

如果你想更改网站配色，编辑 `static/css/main.css` 文件中的颜色变量：

```css
:root{
    --primary-color: #3b82f6;    /* 主色调 */
    --secondary-color: #8b5cf6;  /* 次要色 */
    --accent-color: #06b6d4;     /* 强调色 */
}
```

推荐配色方案：
- 🔵 蓝紫色（当前）：专业、学术
- 🟢 绿色系：`#10b981`, `#059669`, `#14b8a6`
- 🔴 红橙色：`#ef4444`, `#f97316`, `#f59e0b`
- 🟣 紫粉色：`#a855f7`, `#ec4899`, `#f472b6`

---

## 📱 社交媒体链接

在 `index.html` 的 Footer 部分，你可以添加更多社交媒体链接：

```html
<a href="https://github.com/yourusername">
    <i class="bi bi-github"></i> Github
</a>
<span class="mx-1">&middot;</span>
<a href="https://linkedin.com/in/yourprofile">
    <i class="bi bi-linkedin"></i> LinkedIn
</a>
```

---

## 🐛 常见问题

### Q: 网页显示不正常？
A: 清除浏览器缓存后重新加载（Ctrl + F5）

### Q: 图片不显示？
A: 检查图片路径是否正确，确保文件存在于 `static/assets/img/` 目录

### Q: 修改后没有效果？
A: 确保已提交并推送更改，GitHub Pages可能需要几分钟更新

### Q: 如何添加新的板块？
A: 在 `contents/` 创建新的 `.md` 文件，然后在 `index.html` 和 `scripts.js` 中添加相应代码

---

## 📞 需要帮助？

如有问题，请查看：
- 📖 [Bootstrap文档](https://getbootstrap.com/docs/)
- 📝 [Marked.js文档](https://marked.js.org/)
- 🎯 [GitHub Pages文档](https://docs.github.com/pages)
