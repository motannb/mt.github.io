# 🚀 快速启动指南

## ⚡ 5分钟上线你的学术主页

### 步骤 1: 准备图片 📸
替换以下两个文件：
- `static/assets/img/photo.png` - 你的个人照片（建议方形，500x500px以上）
- `static/assets/img/background.jpeg` - 背景图片（建议1920x1080px）

### 步骤 2: 提交代码 💾
打开PowerShell，执行：
```powershell
cd d:\Work\HomePage\mt.github.io
git add .
git commit -m "✨ Update my academic homepage"
git push origin main
```

### 步骤 3: 启用GitHub Pages 🌐
1. 访问 https://github.com/motannb/mt.github.io/settings/pages
2. 在 **Source** 选择 **main** 分支
3. 点击 **Save**
4. 等待1-2分钟

### 步骤 4: 访问网站 🎉
打开浏览器访问：
```
https://motannb.github.io/mt.github.io/
```

---

## 📝 可选：进一步自定义

### 更改配色主题
编辑 `static/css/main.css` 第4-11行：
```css
:root{
    --primary-color: #3b82f6;    /* 改成你喜欢的颜色 */
    --secondary-color: #8b5cf6;  /* 改成你喜欢的颜色 */
    --accent-color: #06b6d4;     /* 改成你喜欢的颜色 */
}
```

推荐配色网站：
- [Coolors.co](https://coolors.co/) - 配色生成器
- [Adobe Color](https://color.adobe.com/) - 专业配色工具

### 添加社交媒体链接
编辑 `contents/home.md`，在开头添加：
```markdown
[![GitHub](https://img.shields.io/badge/GitHub-你的用户名-black?logo=github)](https://github.com/你的用户名)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-你的名字-blue?logo=linkedin)](https://linkedin.com/in/你的ID)
[![Email](https://img.shields.io/badge/Email-联系我-red?logo=gmail)](mailto:your.email@example.com)
```

### 添加Google Scholar
编辑 `contents/home.md`，添加：
```markdown
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-blue?logo=google-scholar)](https://scholar.google.com/citations?user=YOUR_ID)
```

---

## 🎨 预览效果

你的新主页将展示：

### 🏠 HOME
- ✨ 个人简介
- 🎓 教育背景（北京科技大学 + 中南大学）
- 🔬 研究方向（4个领域）

### 🏆 AWARDS
- 🥉 湖南省AI创新大赛省级三等奖
- 🥈 中国研究生电子设计竞赛省级二等奖
- 📄 YAC2025最佳中文论文奖

### 💼 EXPERIENCE
- 📚 研究经历（硕士 + 本科）
- 🔬 项目经历（2个主要项目）

### 📝 PUBLICATIONS
- 📖 IEEE TIM期刊论文 × 2
- 📄 YAC2025会议论文 × 1（最佳论文）
- 🔐 授权发明专利 × 1

---

## 🎯 核心特性

✅ **现代设计** - 蓝紫渐变色，专业优雅  
✅ **响应式布局** - 完美适配手机/平板/电脑  
✅ **平滑动画** - 所有交互都有流畅效果  
✅ **清晰展示** - 学术成果一目了然  
✅ **易于维护** - Markdown文件，修改简单  

---

## 🆘 遇到问题？

### 问题1: 图片显示不出来
**解决方案**: 
- 确认图片文件名正确
- 确认图片在 `static/assets/img/` 目录
- 清除浏览器缓存（Ctrl + F5）

### 问题2: 修改没有生效
**解决方案**:
- 确认已执行 `git push`
- GitHub Pages需要1-2分钟更新
- 清除浏览器缓存

### 问题3: 页面样式错乱
**解决方案**:
- 检查CSS文件是否正确保存
- 查看浏览器控制台是否有错误
- 确认没有遗漏任何文件

### 问题4: 想恢复原样
**解决方案**:
```powershell
git checkout HEAD -- .
```

---

## 📚 更多资源

- 📖 [完整文档](./SUMMARY.md)
- 🚀 [部署指南](./DEPLOYMENT.md)
- 📝 [更新日志](./CHANGELOG.md)
- 🎨 [Bootstrap图标](https://icons.getbootstrap.com/)
- 📊 [Shields.io徽章](https://shields.io/)

---

## 💡 小贴士

1. **定期更新**: 及时更新你的学术成果和项目经历
2. **保持简洁**: 突出重点，避免信息过载
3. **专业照片**: 使用高质量的个人照片
4. **检查链接**: 确保所有链接都有效
5. **备份代码**: 定期备份你的网站代码

---

## 🎉 完成！

恭喜！你已经成功创建了一个现代化、专业的学术主页！

**下一步建议**:
- 📱 在手机上查看效果
- 👥 分享给朋友和导师
- 📧 更新简历中的个人网站链接
- 🎯 在学术论文中引用你的主页

**记住**: 保持内容更新，让你的主页始终展示最新的成就！

---

*Made with ❤️ by Mt | 2024*
