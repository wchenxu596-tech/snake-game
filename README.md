# 🐍 贪吃蛇大作战

一个精美的现代贪吃蛇网页游戏，使用纯 HTML + CSS + JavaScript 构建。

## ✨ 特性

- 🎮 **WASD / 方向键** 控制蛇的移动
- ⏸ **空格键** 暂停 / 继续
- 🏆 **分数系统** — 分数越高速度越快（80ms → 45ms），挑战性逐步提升
- 🪙 **金币系统** — 吃金币获取奖励（金币 = 分数 × 1.5）
- 🛍 **皮肤商店** — 多种蛇皮肤可选，使用金币购买和装备
- 💾 **本地存档** — 最高分和金币数据自动保存在浏览器中
- 🌟 **精美 UI** — 玻璃拟态设计、动态渐变背景、粒子效果

## 🚀 快速开始

直接用浏览器打开 `snake.html` 即可开始游玩！

```bash
open snake.html     # macOS
start snake.html    # Windows
xdg-open snake.html # Linux
```

## 🎯 操作说明

| 按键 | 功能 |
|------|------|
| `↑` `↓` `←` `→` | 移动方向 |
| `W` `A` `S` `D` | 移动方向 |
| `Space` | 暂停 / 继续 |

## 🛠 技术栈

- **语言:** HTML5、CSS3、Vanilla JavaScript
- **渲染:** Canvas 2D
- **存储:** localStorage
- **依赖:** 零外部依赖，开箱即用

## 📁 项目结构

```
snake-game/
├── snake.html   # 游戏主文件（含 HTML、CSS、JS）
├── README.md    # 本文件
└── .gitignore   # Git 忽略规则
```

## 📸 运行效果图

<img width="800" alt="游戏主界面 - 贪吃蛇正在游玩中" src="https://github.com/user-attachments/assets/0b419ae6-fcc2-4fda-ba53-0f81417b143e" />
<img width="800" alt="游戏结束界面 - 显示得分与最高纪录" src="https://github.com/user-attachments/assets/88dc3848-0332-4312-a624-1c9e411cd0c8" />
<img width="800" alt="皮肤商店界面 - 可选多种蛇皮肤" src="https://github.com/user-attachments/assets/11b23ee6-2494-440c-81a9-58864695a768" />
