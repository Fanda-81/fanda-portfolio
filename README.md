<h1 align="center">
  <br>
  <img src="assets/fanda.png" alt="Fanda Zeng" width="120" style="border-radius: 50%;">
  <br>
  Fanda Zeng
  <br>
</h1>

<h4 align="center">个人作品集网站 · AI 产品经理 / 数据产品经理</h4>

<p align="center">
  <a href="#-项目简介">项目简介</a> ·
  <a href="#-功能特性">功能特性</a> ·
  <a href="#-技术栈">技术栈</a> ·
  <a href="#-快速开始">快速开始</a> ·
  <a href="#-部署上线">部署上线</a> ·
  <a href="#-文件结构">文件结构</a> ·
  <a href="#-自定义指南">自定义指南</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/ECharts-AA344D?style=for-the-badge&logo=apacheecharts&logoColor=white" alt="ECharts">
</p>

---

## 📖 项目简介

这是我的个人作品集网站，展示我的**简历**、**数据分析项目**和**核心能力**。网站从一个前端零基础的初学者起步，边学边做，最终完成这个单文件作品集。

> 💡 **背景**：具备经济学与统计学复合背景，兼具数据分析能力与产品思维。这个网站就是「数据思维 + 前端技能」结合的成果。

---

## ✨ 功能特性

- 🏠 **单文件应用**：全部 HTML/CSS/JS 封装在一个 `index.html`，零依赖、零构建
- 📱 **响应式设计**：桌面 / 平板 / 手机三端自适应
- 📊 **数据可视化**：集成 ECharts 图表，直观展示项目成果
- 🔥 **GitHub 热力图**：展示代码贡献活跃度
- 🎨 **设计系统**：CSS 变量统一定义配色，品牌黄色主题
- 🌊 **丝滑交互**：平滑滚动、滚动高亮导航、毛玻璃效果
- 🌐 **Google Fonts**：Playfair Display + Inter 专业字体搭配

---

## 🛠 技术栈

| 类别 | 技术 |
|------|------|
| 结构 | HTML5（语义化标签） |
| 样式 | CSS3（Flexbox、Grid、CSS 变量、媒体查询） |
| 交互 | 原生 JavaScript（DOM、事件监听） |
| 图表 | ECharts 5 |
| 字体 | Google Fonts（Playfair Display + Inter） |

---

## 🚀 快速开始

无需安装任何依赖，直接用浏览器打开即可：

```bash
# 克隆仓库
git clone https://github.com/Fanda-81/fanda-portfolio.git

# 进入目录
cd fanda-portfolio

# 双击 index.html，或用任意静态服务器
python -m http.server 8000
# 浏览器访问 http://localhost:8000
```

---

## ☁️ 部署上线

### 方式一：GitHub Pages（免费，推荐）

1. 在 GitHub 新建仓库（如 `fanda-portfolio`）
2. 上传本文件夹所有文件
3. 进入 `Settings → Pages → Source`，选择 `main` 分支
4. 等待几分钟，访问 `https://<用户名>.github.io/fanda-portfolio/`

### 方式二：Vercel / Netlify（免费，自动部署）

1. 注册 [vercel.com](https://vercel.com) 或 [netlify.com](https://netlify.com)
2. 拖拽本文件夹到部署界面，或连接 GitHub 仓库
3. 自动完成部署，获得线上地址

### 方式三：任意静态服务器

上传到 Nginx / Apache / 云存储，确保 `index.html` 为默认入口即可。

---

## 📁 文件结构

```
fanda-portfolio/
├── index.html              # 主页面（单文件，包含全部 HTML/CSS/JS）
├── Fanda-Zeng-CV.docx      # 简历文件（Download CV 按钮指向此文件）
├── README.md               # 本说明文件
├── 学习教案-前端作品集.md    # 学习过程教案（可导入飞书/Notion）
└── assets/                 # 图片资源目录
    ├── fanda.png               # [可替换] Hero 区域个人头像
    ├── about-photo.png         # [可替换] About 区域个人照片
    ├── work-1-ecommerce.png    # [可替换] 作品1封面图
    ├── work-2-research.png     # [可替换] 作品2封面图
    ├── work-3-community.png    # [可替换] 作品3封面图
    ├── testimonial-avatar.png  # [可替换] 引言区域头像
    └── skills-photo.png        # [可替换] Skills 区域配图
```

---

## 🎨 自定义指南

### 修改文字内容

所有文字直接写在 `index.html` 中，用编辑器打开，搜索关键词定位：

| 想改什么 | 搜索关键词 |
|----------|-----------|
| 姓名 / 职位 | `Fanda Zeng` 或 `AI Product Manager` |
| 联系邮箱 | `zengfanda8147@163.com` |
| GitHub 链接 | `Fanda-81` |
| 区块标题 | `section-label` 或 `section-title` |

### 替换图片

1. 准备图片，按建议尺寸裁剪：
   - 头像/人像类：`600×600px`（正方形）
   - 作品封面类：`800×500px`（横向）
2. 用同名文件覆盖 `assets/` 目录下的对应图片
3. 刷新浏览器即可

> 代码中每张可替换图片前有 `[可替换图片]` 注释，搜索即可定位。

### 修改配色

在 `index.html` 顶部的 `:root` 里改 CSS 变量，一处修改全站生效：

```css
:root {
  --bg-primary: #FAF7F2;      /* 背景色 */
  --accent-yellow: #F4C430;   /* 品牌色 */
  --dark-section: #211F1C;    /* 深色区块 */
}
```

---

## 📈 项目亮点数据

| 指标 | 数据 |
|------|------|
| 处理业务数据量 | 10 万+ 条 |
| 数据监控效率提升 | 60%+ |
| ROI 提升 | 约 15% |
| 社群用户增长 | 0 → 500+（4 个月） |
| 学术项目评级 | HD（High Distinction） |

---

## 📄 许可证

本项目为个人作品集，代码可自由参考学习。如需整体复用，请注明出处。

---

## 📬 联系方式

- 📧 Email: [zengfanda8147@163.com](mailto:zengfanda8147@163.com)
- 💻 GitHub: [@Fanda-81](https://github.com/Fanda-81)
- 📱 Phone: 15564163107

---

<p align="center">Made with ❤️ by Fanda Zeng · 从零开始学前端</p>
