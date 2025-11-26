# Ziyu Xu - Personal Website

个人学术网站，展示机器人研究、项目经历和技术技能。

## 🌐 网站链接

访问: [https://ziyu-xuuuu.github.io](https://ziyu-xuuuu.github.io)

## ✨ 功能特点

- **响应式设计** - 适配桌面端和移动端
- **详细项目展示** - 每个研究项目包含图片、技术细节和GitHub链接
- **CV下载** - 一键下载PDF格式简历
- **定量结果展示** - 展示具体的技术指标和研究成果
- **出版物列表** - 包含已发表和投稿中的论文

## 📂 文件结构

```
.
├── index.html              # 主页面（包含所有内容）
├── profile.jpg             # 个人照片
├── Curly_1.*.jpg          # Curly Lab ASV项目图片
├── Curly_2.*.png          # 多无人机项目图片
├── CV_Ziyu Xu.pdf         # 简历PDF文件
└── README.md              # 本文档
```

## 📋 包含的内容板块

1. **About** - 教育背景和研究兴趣
2. **Research Projects** - 三个主要研究项目：
   - Curly Lab ASV控制系统
   - 多无人机资源感知协调
   - 手术计算机视觉检测
3. **Publications** - 已发表和投稿中的论文
4. **Experience** - 实习经历
5. **Skills** - 技术技能分类展示

## 🔧 如何更新网站

### 更新个人信息

编辑 `index.html` 中的Hero Section (第445-462行):
```html
<h1>你的名字</h1>
<p class="subtitle">你的职位</p>
<a href="mailto:你的邮箱">📧 Email</a>
```

### 添加新项目

在 `index.html` 的Research Section (第484-553行) 中添加新的research-card:
```html
<div class="research-card">
  <img src="项目图片.jpg" alt="项目描述" class="research-image">
  <div class="research-content">
    <h3>项目标题</h3>
    <p class="affiliation">机构 | 时间</p>
    <ul>
      <li>项目要点1</li>
      <li>项目要点2</li>
    </ul>
    <div class="research-links">
      <a href="GitHub链接" target="_blank">🔗 GitHub</a>
    </div>
  </div>
</div>
```

### 更新CV

1. 将新的PDF文件命名为 `CV_Ziyu Xu.pdf`
2. 替换现有文件
3. 确保文件名与index.html中的链接一致

## 🎨 设计特点

- **配色方案**: GitHub深色主题风格
  - 背景: `#0d1117`
  - 卡片: `#161b22`
  - 强调色: `#58a6ff`

- **字体**: Segoe UI / -apple-system

- **响应式断点**: 768px (移动端优化)

## 📱 移动端优化

网站已针对移动设备优化：
- 自适应导航栏
- 灵活的网格布局
- 触摸友好的按钮尺寸

## 🚀 部署到GitHub Pages

1. 确保仓库名为: `你的用户名.github.io`
2. 将所有文件推送到main分支
3. 在仓库Settings > Pages中启用GitHub Pages
4. 选择main分支作为源
5. 网站将自动部署到 `https://你的用户名.github.io`

## 📧 联系方式

- Email: ziyuxu@umich.edu
- GitHub: [@Ziyu-Xuuuu](https://github.com/Ziyu-Xuuuu)

## 📄 许可证

© 2025 Ziyu Xu