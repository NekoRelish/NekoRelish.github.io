# 我的个人网站

一个使用纯HTML、CSS和JavaScript构建的现代化响应式个人网站，部署在GitHub Pages上。

## 预览

访问 [GitHub Pages](https://yourusername.github.io) 查看在线预览。

## 特点

- 📱 完全响应式设计，适配各种设备
- 🎨 现代化UI设计，美观大方
- ⚡ 纯静态网站，加载速度快
- 🔍 SEO友好，有利于搜索引擎优化
- 🌐 免费托管在GitHub Pages
- 📧 包含联系表单
- 🖼️ 作品集展示区
- 🎯 平滑滚动和动画效果

## 技术栈

- HTML5
- CSS3 (CSS变量、Flexbox、Grid)
- JavaScript (ES6+)
- Font Awesome (图标库)
- Google Fonts

## 文件结构

```
├── index.html          # 主页
├── styles.css          # 样式表
├── script.js           # JavaScript脚本
├── README.md           # 说明文档
└── deploy.bat          # 部署向导
```

## 快速开始

### 1. 克隆或下载文件

```bash
git clone https://github.com/yourusername/yourusername.github.io.git
# 或者直接下载ZIP文件并解压
```

### 2. 自定义内容

编辑 `index.html` 文件，替换以下内容：

- 你的姓名和个人信息
- 个人简介和技能
- 作品集项目
- 联系方式

编辑 `styles.css` 文件，自定义颜色主题：

```css
:root {
    --primary-color: #3f51b5;      /* 主题颜色 */
    --primary-dark: #303f9f;       /* 主题深色 */
    --primary-light: #757de8;      /* 主题浅色 */
    --secondary-color: #ff4081;    /* 次要颜色 */
    /* 更多颜色变量... */
}
```

### 3. 部署到GitHub Pages

#### 方法1: 使用提供的部署向导

运行 `deploy.bat` 文件，按照向导步骤操作。

#### 方法2: 手动部署

1. 在GitHub上创建一个名为 `你的用户名.github.io` 的仓库
2. 将网站文件上传到该仓库
3. 在仓库设置中启用GitHub Pages
4. 选择 `main` 分支和根目录
5. 保存设置，等待几分钟即可访问

## 自定义指南

### 添加新项目

在 `index.html` 的作品集部分添加新的 `portfolio-item`:

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="https://picsum.photos/seed/project4/600/400.jpg" alt="项目4">
    </div>
    <div class="portfolio-content">
        <h3>项目标题</h3>
        <p>项目描述</p>
        <a href="#" class="btn btn-small">查看详情</a>
    </div>
</div>
```

### 更新技能

在技能部分添加或修改技能标签:

```html
<div class="skills-grid">
    <div class="skill-item">新技能</div>
    <!-- 其他技能... -->
</div>
```

### 修改联系方式

在联系部分更新你的联系方式:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div class="contact-details">
        <h3>电子邮箱</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 添加社交媒体链接

在页脚部分更新社交媒体链接:

```html
<div class="social-icons">
    <a href="https://github.com/yourusername" aria-label="GitHub"><i class="fab fa-github"></i></a>
    <a href="https://twitter.com/yourusername" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
    <!-- 更多社交链接... -->
</div>
```

## 自定义域名

如果你有自定义域名，可以：

1. 在仓库根目录创建 `CNAME` 文件
2. 在文件中添加你的域名，例如 `www.yourdomain.com`
3. 在域名提供商处添加DNS记录
4. 在GitHub Pages设置中配置自定义域名

## 性能优化

网站已经进行了以下优化：

- 图片使用CDN服务
- CSS和JavaScript文件压缩
- 使用CSS变量便于主题管理
- 响应式图片加载
- 懒加载和动画优化

## 浏览器支持

- Chrome (最新版本)
- Firefox (最新版本)
- Safari (最新版本)
- Edge (最新版本)

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 贡献

欢迎提交问题和改进建议！

## 联系方式

- 邮箱: your.email@example.com
- GitHub: https://github.com/yourusername

---

**提示**: 如果你在部署过程中遇到问题，请运行 `deploy.bat` 文件获取详细的部署指导。