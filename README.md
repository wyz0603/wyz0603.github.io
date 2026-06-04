# 吴杨智 · 个人主页

> 机器人 & ROS 开发工程师的个人介绍网站 —— 单文件、零依赖、离线可用。

🔗 **在线预览**:[https://wyz0603.github.io](https://wyz0603.github.io)

---

## ✨ 特性

- **纯静态单文件**:全部 HTML / CSS / JavaScript 内联在一个 `index.html` 里,无框架、无构建、无外部库,断网也能打开。
- **响应式布局**:桌面、平板、手机自适应,移动端带汉堡菜单。
- **暗色科技风**:冷白渐变标题、双色发光头像光环、各板块独立的科技纹理背景(电路 / 蜂巢 / 雷达 / 点阵 / 蓝图 / 斜线,均为矢量 SVG)。
- **动效**:
  - 首屏 Canvas 粒子星座背景(尊重系统「减少动态效果」设置)
  - 打字机轮播头衔
  - 技能熟练度进度条滚动填充
  - 数据高亮数字滚动(count-up)
  - 滚动渐入(IntersectionObserver)
- **荣誉证书展示**:13 张真实证书横向无缝跑马灯,悬停暂停、点击放大(灯箱支持 ← / → 切换、Esc 关闭)。
- **作品展示**:实物作品图,点击放大查看。
- **隐私保护**:证书中同组同学姓名已做背景填充隐去;不公开手机号等敏感信息。

## 🧩 页面板块

`关于我` · `专业技能` · `实习经历` · `项目经历` · `作品展示` · `荣誉证书` · `联系方式`

## 📁 目录结构

```
.
├── index.html          # 全部页面(结构 / 样式 / 脚本内联)
├── assets/
│   ├── certs/          # 获奖证书图片(13 张)
│   ├── works/          # 作品实物图
│   └── bg/             # 科技纹理背景(SVG,可平铺)
└── README.md
```

## 🚀 本地预览

任选其一:

```bash
# 方式一:直接用浏览器打开
open index.html          # macOS
xdg-open index.html      # Linux

# 方式二:起一个本地服务器(推荐,图片路径更稳)
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 🌐 部署

本项目托管于 **GitHub Pages**,仓库名为 `wyz0603.github.io`,推送到 `main` 分支后自动发布到 [https://wyz0603.github.io](https://wyz0603.github.io)。

```bash
git add .
git commit -m "update"
git push          # 约 1 分钟后线上自动更新
```

## 🛠️ 技术栈

| 类别 | 使用 |
|------|------|
| 结构/样式/逻辑 | 原生 HTML5 / CSS3 / Vanilla JavaScript |
| 动画 | CSS Animations + Canvas 2D + IntersectionObserver |
| 图形 | 内联 SVG 矢量纹理 |
| 托管 | GitHub Pages |

> 设计上刻意保持「零依赖、单文件」,便于长期维护与离线分发。

---

© 吴杨智 · Robotics & ROS Developer
