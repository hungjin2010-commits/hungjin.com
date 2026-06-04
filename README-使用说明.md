# 厦门泓劲贸易官网 - 部署包 v2024.06.04

## 📦 版本信息
- **版本号**: v2024.06.04
- **发布日期**: 2026-06-04
- **更新内容**:
  - ✅ 优化手机端界面（导航栏、Banner、欢迎区域）
  - ✅ 优化电脑端表单界面（现代风格、渐变按钮）
  - ✅ 修复表单提交功能（mailto方案）
  - ✅ 域名替换：popsouq.com → xmhungjin.com
  - ✅ 统一中英文版样式

## 🚀 快速使用

### 方法1：直接打开（最简单）
1. 解压压缩包
2. 双击 `index.html` 即可在浏览器中打开
3. 所有链接都是相对路径，可以离线浏览

### 方法2：本地服务器（推荐，避免跨域问题）
```bash
# Python 3
cd popsouq.com
python3 -m http.server 8000

# 然后访问：http://localhost:8000
```

```bash
# PHP
cd popsouq.com
php -S localhost:8000

# 然后访问：http://localhost:8000
```

### 方法3：部署到Web服务器
将整个 `popsouq.com` 文件夹上传到服务器即可。

## 📂 文件结构
```
popsouq.com/
├── index.html              # 中文首页
├── index-en.html          # 英文首页
├── about.html             # 关于我们（中文）
├── about-en.html         # 关于我们（英文）
├── products.html         # 产品展示（中文）
├── products-en.html     # 产品展示（英文）
├── contact.html          # 联系我们（中文）
├── contact-en.html      # 联系我们（英文）
├── knowledge.html        # 面料知识（中文）
├── knowledge-en.html    # 面料知识（英文）
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # JavaScript脚本
├── images/              # 图片资源
└── knowledge/           # 知识文章图片
```

## ⚙️ 配置说明

### 表单提交
当前使用 `mailto:` 方案，用户提交表单时会打开默认邮件客户端。
- **收件邮箱**: qy125100@xmhungjin.com
- 如需修改，编辑 `contact.html` 和 `contact-en.html` 中的邮箱地址

### 域名配置
如果部署到其他域名：
1. 批量替换所有HTML文件中的 `xmhungjin.com` 为新域名
2. 更新 `CNAME` 文件（如果使用GitHub Pages）

## 🌐 部署建议

### GitHub Pages（免费）
1. 创建GitHub仓库
2. 上传所有文件到 `main` 分支
3. 在仓库设置中启用GitHub Pages
4. 访问 `https://你的用户名.github.io/仓库名`

### 其他静态托管
- **Vercel**: 拖拽上传，自动部署
- **Netlify**: 拖拽上传，自动部署
- **Cloudflare Pages**: 免费CDN加速

## 📱 浏览器兼容性
- ✅ Chrome/Edge (推荐)
- ✅ Firefox
- ✅ Safari
- ✅ 手机浏览器（响应式设计）

## 📞 技术支持
- 邮箱: qy125100@xmhungjin.com
- 电话: (86) 592-5986779
- WhatsApp: +52 15510217089

---
**打包时间**: 2026-06-04 15:27
**文件版本**: CSS v127, JS v79
