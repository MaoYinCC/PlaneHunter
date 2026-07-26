# ✈️ 炸飞机 / Air Force Battle (Plane Bomber)

一个基于纯前段技术（HTML5 + JavaScript + CSS3 + SVG）构建的经典**“炸飞机 / 击落机头”**策略对战网页游戏。支持单人对战 AI 以及双人对局记分辅助，开箱即用，无需安装任何依赖或构建环境。

---

## 🎮 游戏规则与玩法简介

1. **阵地规则**：双方玩家各自在一个 9×9 的棋盘上隐蔽摆放 **3 架战机**。
2. **战机形状**：每架战机由 1 个机头、3 个机身/机翼节点和 1 个机尾组成（共 5 个格子）。
3. **胜负判定**：
   - 击中**机身/机翼/机尾**：判定为 **“命中 ✖”**；
   - 击中**机头**：直接**“摧毁整架战机 💥**；
   - **率先摧毁敌方全部 3 个机头的一方获得胜利！**

---

## ✨ 核心特色

- 🛠️ **极简交互式布阵**：
  - 点击网格即可顺时针 90° 旋转并放置战机；
  - 摆放满意后通过按键/快捷键锁定，自动切换下一架；
  - 支持一键 **🎲 随机布阵** 与 **🗑️ 清空重摆**。
- 🤖 **智能 PVE 人机对战**：
  - 内置 AI 战术逻辑，AI 击中战机机身时会自动展开对四周邻近区域的追踪探测。
- 👥 **双人 PVP 模拟打靶/记分**：
  - 支持线下双人对战时作为电子记分板使用，右侧棋盘可循环标记 `[空 •] / [机身 ✖] / [机头 💥]`。
- 🎨 **矢量 SVG 动态渲染**：
  - 使用原生 SVG 绘制精致战机模型，支持复盘模式下清晰展示敌我双方的完整战机布局。
- 🎵 **Web Audio API 原生音效**：
  - 基于浏览器原生的音频合成器生成开火、击中、炸毁与胜负音效，无需加载外部音频资源。
- 🌐 **双语支持 (中/英)**：
  - 内置一键切换中文与英文界面。

---

## 🚀 快速开始 / 本地运行

由于本项目为纯前端静态页面，无需任何 Node.js 或后端服务器环境：

打开网页直接开玩：
https://maoyincc.github.io/PlaneHunter/

==

# ✈️ Air Force Battle (Plane Bomber)

A classic "Plane Bomber / Headshot" strategy battle web game built entirely with front-end technologies (HTML5 + JavaScript + CSS3 + SVG). It supports single-player vs. AI mode and peer-to-peer (P2P) online multiplayer, ready to play out of the box with zero dependencies or build steps required.

---

## 🎮 Game Rules & Gameplay

1. **Board Rules:** Both players hide and deploy 3 aircraft on their respective $9 \times 9$ grid.
2. **Plane Structure:** Each plane consists of 1 head, 3 body/wing nodes, and 1 tail (occupying a total of 5 cells).
3. **Victory Condition:**
* Hitting the body, wings, or tail is recorded as a "Hit ✖".
* Hitting the head directly "Destroys the entire plane 💥".
* The first player to destroy all 3 enemy heads wins the game!



---

## ✨ Key Features

* **🛠️ Interactive Deployment:**
* Click the grid to rotate the aircraft 90° clockwise and place it.
* Lock your placement to automatically switch to the next aircraft.
* Supports one-click 🎲 random placement and 🗑️ clearing.


* **🤖 Intelligent PVE AI Battle:**
* Built-in AI tactical logic: when the AI hits a plane body, it automatically tracks and probes surrounding adjacent cells.


* **🌐 P2P Online Multiplayer:**
* Connect directly with friends using room IDs powered by PeerJS for real-time online matches.


* **🎨 Vector SVG Dynamic Rendering:**
* Uses native SVG to render detailed aircraft models, clearly displaying complete player and enemy formations in review mode.


* **🎵 Native Web Audio API Sound Effects:**
* Generates firing, hit, explosion, and victory/defeat sound effects using the browser's built-in audio synthesizer without external audio files.


* **🌐 Bilingual Support (CN / EN):**
* Built-in one-click switching between Chinese and English interfaces.



---

## 🚀 Quick Start / Local Execution

Since this project is a purely static front-end page, it requires no Node.js or backend server environment:

Open the link to play directly:

[https://maoyincc.github.io/PlaneHunter/](https://maoyincc.github.io/PlaneHunter/)
