# Fanda Zeng — Personal Resume Website

## 文件结构

```
fanda-portfolio/
├── index.html              # 主页面（单文件，包含全部 HTML/CSS/JS）
├── Fanda-Zeng-CV.docx     # 简历文件（Download CV 按钮指向此文件）
├── README.md               # 本说明文件
└── assets/                 # 图片资源目录
    ├── hero-portrait.png       # [可替换] Hero 区域个人头像
    ├── about-photo.png         # [可替换] About 区域个人照片
    ├── work-1-ecommerce.png    # [可替换] 作品1封面图
    ├── work-2-research.png     # [可替换] 作品2封面图
    ├── work-3-community.png    # [可替换] 作品3封面图
    ├── testimonial-avatar.png  # [可替换] 引言区域头像
    └── skills-photo.png        # [可替换] Skills 区域配图
```

## 本地预览

直接用浏览器打开 `index.html` 即可，无需安装任何依赖。

## 部署上线

### 方式一：GitHub Pages（免费）
1. 在 GitHub 创建一个新仓库（如 `fanda-portfolio`）
2. 将本文件夹所有文件上传到仓库
3. 进入仓库 Settings → Pages → Source 选择 `main` 分支
4. 等待几分钟后访问 `https://<用户名>.github.io/fanda-portfolio/`

### 方式二：Vercel / Netlify（免费）
1. 注册 vercel.com 或 netlify.com
2. 拖拽本文件夹到部署界面，或连接 GitHub 仓库
3. 自动部署完成，获得线上地址

### 方式三：任意静态服务器
将本文件夹上传到任意 Web 服务器（Nginx / Apache / 云存储），确保 `index.html` 为默认入口文件即可。

## 如何替换图片

1. 准备你的图片，按以下建议尺寸裁剪：
   - 头像/人像类：600×600px，正方形
   - 作品封面类：800×500px，横向比例
2. 用同名文件覆盖 `assets/` 目录下的对应图片
3. 刷新浏览器即可看到新图片

源代码中每张可替换图片前均有注释标注，搜索 `[可替换图片]` 即可快速定位。

## 如何修改文字内容

所有文字内容直接写在 `index.html` 中，用文本编辑器打开即可修改。搜索关键词找到对应区块：

- 姓名/职位：搜索 `Fanda Zeng` 或 `AI Product Manager`
- 联系邮箱：搜索 `zengfanda8147@163.com`
- GitHub 链接：搜索 `Fanda-81`
- 各区块标题：搜索 `section-title` 或 `section-label`

## 技术说明

- 纯静态单页应用，无后端依赖
- GitHub 贡献热力图数据为 2025-08 至 2026-08 的真实数据（来自 Fanda-81 账号）
- 字体使用 Google Fonts 在线加载：Playfair Display + Inter
- 响应式设计，支持桌面和移动端浏览
