# Ruoran Xu — Academic Homepage

静态 HTML/CSS 主页，采用 Jon Barron 的 800px 居中布局、Lato 字体与蓝色链接，参考 Bohan Lyu 的 News 区域。Publications 采用类似 Yilun Zhao 的纯文字列表，移除配图栏，放在 440px 高的独立滚动区中（手机端 420px），支持鼠标、触摸和键盘滚动；打印时自动展开全文。

## 预览

直接打开 `index.html`，或在本目录运行：

```sh
python -m http.server 8000
```

然后访问 http://localhost:8000 。不需要安装依赖或构建。

## 更新

- 在 `index.html` 中编辑个人介绍、联系链接、News、论文与项目。
- 在 `stylesheet.css` 中调整布局；图片放入 `images/`。
- 字体已保存在 `assets/fonts/`，本地预览无需连接 Google Fonts。
- 新增 News 时，在 `#news` 列表最前面添加一条，保持时间倒序。

## 发布到 GitHub Pages

把 `index.html`、`stylesheet.css`、`.nojekyll`、`images/` 和 `assets/` 放入 `RuoranXu/RuoranXu.github.io` 的发布目录。GitHub Pages 选择对应分支的根目录即可。旧 Jekyll 工作流如仍启用，需要改用静态 Pages 发布。

发布仓库为 `RuoranXu/RuoranXu.github.io`；旧版保留在 `RuoranXu/RuoranXu2.github.io`。

## 迁移记录

内容来源：https://github.com/RuoranXu/RuoranXu.github.io ，读取于 2026-09-29。

以仓库当前 `_pages/about.md` 和 `_config.yml` 为准，迁移个人介绍、6 条 News、5 篇公开论文、2 个项目和联系方式。原站已注释的内容不展示。仓库比搜索缓存多两篇 workshop 论文；ICML News 时间采用仓库中的 2026.04。

另按本人提供的信息，在 Publications 最后追加 Evidence Bypass 与 OC-OPD 两篇论文，均标为 Under review at ICLR。联系方式移除 ORCID、ResearchGate，并增加显示 `Rowan_Xu1` 的微信弹窗，可通过关闭按钮、Esc 或点击遮罩关闭。

两篇 workshop 论文的 Paper 链接为空，因此仅提供有效的 Code 链接。所有论文统一为无图布局。PhysElite 的 Hugging Face 链接标为 Dataset。原站无有效地址的 CV、Blog、项目笔记入口不生成空链接。

`reference/` 保存迁移时读取的原始内容和排版参考，便于核对，不需要上传。字体许可证见 `assets/fonts/OFL.txt`。

布局参考：https://github.com/jonbarron/jonbarron.github.io 与 https://bohanlyu.com/ 。
