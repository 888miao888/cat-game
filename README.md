# 猫猫接小鱼 (Cat Catch)

一个用 Phaser + TypeScript + Vite 做的猫猫主题接物小游戏（单文件自包含，引擎+图片全内嵌）。

## 在线试玩
上传本包到 GitHub 并开启 Pages 后：
- GitHub Pages：https://888miao888.github.io/cat-game/standalone.html
- jsDelivr CDN（国内更快）：https://cdn.jsdelivr.net/gh/888miao888/cat-game@main/standalone.html

## 玩法
- 左右方向键 / A D 或鼠标拖动移动猫猫（手机触屏也可以）
- 接小鱼 +10 分，金鱼 +50 分，躲开炸弹
- 3 条命，生命归零游戏结束

## 本地运行
直接双击 standalone.html 即可离线玩，无需安装任何东西。

## 目录说明
- standalone.html —— 游戏本体（上传 GitHub Pages 必需，放仓库根目录）
- .nojekyll —— 防止 Jekyll 处理（上传必需）
- screenshots/ —— 游戏截图
- source/ —— TypeScript 源码与素材生成脚本（开发参考）

## 技术栈
Phaser 3.90 · TypeScript · Vite · DOM 覆盖层 HUD
