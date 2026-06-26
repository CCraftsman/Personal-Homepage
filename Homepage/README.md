# Personal Homepage

这是我的个人主页项目，用于展示我的教育背景、研究方向、项目经历、荣誉奖项、技术技能以及联系方式。

主页默认显示简体中文，并支持在右上角点击 `English` 切换到英文版；英文模式下可以点击 `简体中文` 切换回来。

## 项目内容

- 个人简介
- 教育背景
- 研究与项目经历
- 荣誉奖项
- 技术技能
- 邮箱与 GitHub 联系方式
- 中英文切换功能

## 文件结构

```text
homepage/
├── index.html
└── README.md
```

## 如何预览

直接用浏览器打开 `index.html` 即可查看网页。

如果部署到 GitHub Pages，建议仓库结构保持为：

```text
homepage/index.html
```

然后在 GitHub 仓库的 `Settings` -> `Pages` 中选择对应分支和目录进行发布。

## 如何修改内容

主要内容都在 `index.html` 里：

- 修改个人信息：搜索 `蒋呈彦` 或 `Chengyan Jiang`
- 修改邮箱：搜索 `123090225@link.cuhk.edu.cn`
- 修改 GitHub 链接：搜索 `https://github.com/CCraftsman`
- 修改中文文案：在 `translations.zh` 中编辑
- 修改英文文案：在 `translations.en` 中编辑
- 修改颜色和布局：编辑 `<style>` 标签中的 CSS 变量和样式

## 技术说明

本项目使用纯 HTML、CSS 和 JavaScript 编写，不依赖额外框架或构建工具。

语言切换通过 JavaScript 字典实现，页面不会跳转，也不需要额外的英文版 HTML 文件。

## Author

Chengyan Jiang  
GitHub: [CCraftsman](https://github.com/CCraftsman)
