# 🚀 GitHub Pages 部署指南

## 步骤 1：创建 GitHub 仓库

1. 访问 [GitHub.com](https://github.com)
2. 点击右上角的 "+" 号，选择 "New repository"
3. 仓库名称输入：
   - `portfolio` (推荐)
   - 或者 `你的用户名.github.io` (如果想要自定义域名)
4. 设置为 **Public** (GitHub Pages 免费版需要公开仓库)
5. 不要勾选 "Add a README file"
6. 点击 "Create repository"

## 步骤 2：上传网站文件

### 方法 A：通过 GitHub 网页界面上传

1. 在新创建的仓库页面，点击 "uploading an existing file"
2. 将 `static-website` 文件夹中的所有文件拖拽到页面中：
   - `index.html`
   - `assets/` 文件夹（包含你的照片）
   - `README.md`
3. 在底部的提交信息中输入："Add personal portfolio website"
4. 点击 "Commit changes"

### 方法 B：使用 Git 命令行

```bash
# 1. 克隆仓库到本地
git clone https://github.com/你的用户名/仓库名.git
cd 仓库名

# 2. 复制网站文件到仓库文件夹
# 将 static-website 文件夹中的所有内容复制到这里

# 3. 添加并提交文件
git add .
git commit -m "Add personal portfolio website"
git push origin main
```

## 步骤 3：启用 GitHub Pages

1. 在你的仓库页面，点击 "Settings" 标签
2. 在左侧菜单中找到 "Pages"
3. 在 "Source" 部分：
   - 选择 "Deploy from a branch"
   - Branch: 选择 "main"
   - Folder: 选择 "/ (root)"
4. 点击 "Save"

## 步骤 4：访问你的网站

几分钟后，你的网站将在以下地址上线：
- `https://你的用户名.github.io/仓库名`

GitHub 会显示网站地址，点击即可访问。

## 🎯 验证网站内容

访问网站后，确认以下内容显示正确：
- ✅ 你的个人照片显示正常
- ✅ InterBridge 项目信息准确
- ✅ Bay Area Founders Club Batch 25 信息正确
- ✅ 联系表单工作正常
- ✅ 移动端显示良好

## 🔧 常见问题解决

### 图片不显示
- 确保 `assets` 文件夹已上传
- 检查图片文件名是否正确：`headshot.jpg`, `meeting.png`, `venture.jpg`

### 网站未更新
- GitHub Pages 更新可能需要 5-10 分钟
- 尝试清除浏览器缓存
- 检查仓库的 Actions 标签查看部署状态

### 404 错误
- 确保仓库是 Public
- 确保 GitHub Pages 已启用
- 确保 `index.html` 在仓库根目录

## 🌐 自定义域名（可选）

如果你有自己的域名：

1. 在仓库根目录创建 `CNAME` 文件
2. 文件内容写入你的域名：`www.你的域名.com`
3. 在域名提供商处设置 DNS：
   - CNAME 记录：`www` 指向 `你的用户名.github.io`
   - A 记录：`@` 指向 GitHub Pages IP 地址

## 📱 移动端优化

网站已经过移动端优化：
- 响应式设计适配所有屏幕尺寸
- 触屏友好的导航
- 快速加载时间
- 移动端表单体验良好

## 🔄 更新网站

要更新网站内容：
1. 修改 `index.html` 文件
2. 重新上传到 GitHub 仓库
3. 或者直接在 GitHub 网页上编辑文件
4. 几分钟后更改就会生效

## ✅ 部署完成！

你的专业个人作品集网站现在已经在线，包含：
- 专业的设计和布局
- 你的真实照片和经历
- InterBridge 项目展示
- Bay Area Founders Club 信息
- 工作联系方式

网站地址：`https://你的用户名.github.io/仓库名`

分享给朋友、同事和潜在合作伙伴吧！