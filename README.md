# 🎮 坦克大战 (Tank Battle)

经典 FC 风格的坦克大战网页游戏，使用 HTML5 Canvas 实现。

## 🕹️ 玩法

- **移动**: `↑ ↓ ← →` 或 `W A S D`
- **射击**: `空格` 或 `J`
- **暂停**: `P`

## ✨ 特性

- 🎯 经典 Battle City 风格画面
- 🧱 可破坏砖墙 + 不可破坏钢墙
- 🌊 水域地形，阻挡坦克但不阻挡子弹
- 🌲 树林掩护
- 🦅 保护基地（鹰），基地被毁则游戏结束
- 🤖 多种敌人类型：基础型、快速型、装甲型（2条命）、强力型
- 💎 5种道具：升级★、加命♥、全屏炸弹💣、护盾🛡、冻结⏰
- 📈 3个关卡，难度递增
- 🔊 音效反馈
- 📱 支持触屏操作
- 🎨 侧边信息面板

## 🚀 快速开始

直接用浏览器打开 `index.html` 即可游戏。

或者使用任意 HTTP 服务器：

```bash
python -m http.server 8000
# 访问 http://localhost:8000
```

## 🖼️ 预览

![screenshot](screenshot.png)

## 🛠️ 技术栈

- HTML5 Canvas
- 原生 JavaScript (ES6)
- Web Audio API

## 📄 License

MIT
