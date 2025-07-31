# Jason G. You - 个人作品集网站

这是一个完整的静态 HTML 网站，可以直接部署到 GitHub Pages。

## 🚀 如何部署到 GitHub Pages

### 方法 1：直接上传文件
1. 在 GitHub 创建新仓库（命名如 `portfolio` 或你的用户名.github.io）
2. 将 `static-website` 文件夹中的所有文件上传到仓库根目录
3. 在仓库设置中启用 GitHub Pages，选择 `main` 分支
4. 你的网站将在 `https://你的用户名.github.io/仓库名` 上线

### 方法 2：使用 GitHub Desktop
1. 下载并安装 GitHub Desktop
2. 克隆你的仓库到本地
3. 将 `static-website` 中的文件复制到仓库文件夹
4. 提交并推送更改

## 📁 文件结构

```
static-website/
├── index.html          # 主网站文件
├── assets/            # 图片资源
│   ├── headshot.jpg   # 你的头像
│   ├── meeting.png    # 会议照片
│   └── venture.jpg    # 投资相关图片
└── README.md          # 说明文档
```

## ✨ 网站特性

- **响应式设计**：适配手机、平板、桌面
- **单页应用**：流畅的滚动导航
- **个人照片**：使用你的真实照片
- **专业内容**：展示你在 InterBridge 的工作
- **联系表单**：访客可以通过邮件联系你
- **Berkeley 主题**：使用加州大学伯克利分校的配色

## 🎨 自定义网站

### 更改颜色
在 `index.html` 中找到这段代码并修改：
```javascript
colors: {
    'berkeley-blue': '#003262',    // 主色调
    'berkeley-gold': '#FDB515',   // 强调色
}
```

### 更新内容
- 个人介绍：搜索 "Hi, I'm Jason Guowei You"
- 项目信息：搜索 "InterBridge" 部分
- 联系信息：搜索 "jason7@berkeley.edu"

### 替换图片
- `assets/headshot.jpg` - 你的头像照片
- `assets/meeting.png` - 会议或工作照片
- `assets/venture.jpg` - 商业相关照片

## 📧 联系表单

联系表单会打开用户的默认邮件客户端发送邮件到 jason7@berkeley.edu。如果需要更高级的表单功能，可以集成：
- Formspree
- Netlify Forms
- EmailJS

## 🔧 技术栈

- **HTML5** - 网页结构
- **Tailwind CSS** - 样式框架
- **Vanilla JavaScript** - 交互功能
- **响应式设计** - 移动端优化

## 📱 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

网站已经过测试，在所有现代浏览器中都能正常工作。

## 🚀 立即部署

1. 创建 GitHub 仓库
2. 上传 `static-website` 文件夹中的所有文件
3. 启用 GitHub Pages
4. 你的专业作品集网站就上线了！

需要帮助？请联系 jason7@berkeley.edu