# 🐱 猫猫接小鱼 (Cat Catch)

一个用 Phaser + TypeScript + Vite 做的猫猫主题接物小游戏（单文件自包含，引擎+图片全内嵌）。

## 🎮 在线试玩
- GitHub Pages：https://888miao888.github.io/cat-game/standalone.html
- jsDelivr CDN（仅下载用，不能直接渲染）：https://cdn.jsdelivr.net/gh/888miao888/cat-game@main/standalone.html

## 玩法
- 左右方向键 / A D 或鼠标拖动移动猫猫（手机触屏也可以）
- 接小鱼 +10 分，金鱼 +50 分，连击有加成（x2 +5、x3 +10...）
- 盲盒 🎁：50% 变大 / 50% 加速（持续 8 秒）
- 难度递增：等级越高，掉得越快、炸弹越多
- 3 条命，生命归零游戏结束；排行榜记录最高分（本机）

## 📦 版本记录
- **v2（当前）**：猫猫皮肤 + 难度递增 + 最高纪录排行榜 + 盲盒道具
- **v1**：连击加分 + 音效 + 结算文案

## ↩️ 想回退版本？
- 网页版：把 `versions/v1.html` 的内容复制覆盖到仓库根目录 `standalone.html`（或让我帮你切回）
- 本地版：`versions/` 目录里有 v1.html / v2.html，双击即可玩任意版本

## 技术栈
Phaser 3.90 · TypeScript · Vite · DOM 覆盖层 HUD
