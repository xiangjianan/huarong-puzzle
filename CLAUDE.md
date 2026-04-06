# 任务
开发一个精美的数字华容道（15-puzzle）游戏，输出到 index.html 单文件。

## 要求
1. 纯 HTML/CSS/JS 单文件
2. 支持 3x3、4x4、5x5 多种难度
3. 计步器和计时器
4. 流畅的滑动动画
5. 现代美观的 UI（渐变色、圆角、阴影、深色主题）
6. 移动端触摸滑动支持
7. 完成时有庆祝动画（粒子/烟花效果）
8. 响应式布局

## 技术约束
- 不要使用任何外部 CDN 或框架
- 所有代码在单个 index.html 文件中
- 代码注释用中文

## 完成后
1. git init && git add -A && git commit -m "init: 数字华容道游戏"
2. 用 gh repo create huarong-puzzle --public --source=. --push 创建仓库并推送
3. 启用 GitHub Pages: gh api repos/xiangjianan/huarong-puzzle/pages -X POST -f source.branch=main -f source.path=/
