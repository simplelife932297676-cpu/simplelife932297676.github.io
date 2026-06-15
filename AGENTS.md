# AGENTS.md

> 此文件帮助 AI 助手快速理解项目约定，避免常见错误。

## 项目概述

儿童游戏乐园网站，包含三个面向2-12岁儿童的游戏：
- 益智游戏：记忆配对游戏，锻炼思维能力
- 角色扮演游戏：装扮游戏，发挥想象力
- 教学游戏：数学学习游戏，边玩边学

另有课程心得页面，供用户记录学习心得。

技术栈：纯 HTML/CSS/JavaScript，无构建工具

## 项目结构

```
├── index.html          # 首页
├── notes.html          # 课程心得页面
├── css/
│   ├── style.css       # 全局样式
│   ├── game.css        # 游戏通用样式
│   ├── roleplay.css    # 角色扮演游戏样式
│   ├── educational.css # 教学游戏样式
│   ├── notes.css       # 心得页面样式
│   └── language.css    # 语言切换样式
├── js/
│   ├── main.js         # 主脚本
│   ├── game.js         # 益智游戏逻辑
│   ├── roleplay.js     # 角色扮演游戏逻辑
│   ├── educational.js  # 教学游戏逻辑
│   ├── notes.js        # 心得管理逻辑
│   └── translations.js # 多语言翻译
├── games/
│   ├── puzzle.html     # 益智游戏页面
│   ├── roleplay.html   # 角色扮演游戏页面
│   └── educational.html # 教学游戏页面
└── assets/
    ├── images/         # 图片资源
    └── sounds/         # 音效资源
```

## 开发方式

纯前端静态网站，直接在浏览器中打开 `index.html` 即可运行

## 注意事项

- 所有游戏使用 localStorage 保存进度
- 心得页面支持保存、编辑、删除功能
- 支持繁体中文/英文双语切换
- 响应式设计，支持移动端
- 颜色使用明亮的渐变色，适合儿童审美
