![Slumberland — Prelude to the Long Banquet](docs/banner.png)

A 2D pixel-art, top-down action demo built with Unity. Wander a quiet pixel world, slash, dash, and poke at everything that looks interactive — doors, chests, altars.

<p>
  <a href="#中文">中文说明</a> · <a href="#english">English</a>
</p>

![Unity](https://img.shields.io/badge/Unity-2022.3.57f1-000000?logo=unity&logoColor=white)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-0078D6?logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/version-v0.1.0-orange)
![Status](https://img.shields.io/badge/status-demo-blue)
![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red)

---

## 截图 / Screenshots

**标题界面 · Title screen**

![Title screen](docs/screenshots/01-title.jpg)

**探索 · Exploration** — 俯视角探索，左上角 HP / MP，底部经验条

![Exploration](docs/screenshots/02-exploration.jpg)

**对话 · Dialogue** — 角色立绘与对白

![Dialogue](docs/screenshots/03-dialogue.jpg)

---

## 中文

### 下载游玩

前往 **[Releases](../../releases/latest)** 下载 `Slumberland-v0.1.0-win64.zip`（约 234 MB），解压后双击 `Slumberland/SL_Game.exe` 即可开始。

- **系统**：Windows 10 / 11，64 位
- **显卡**：支持 DirectX 11 / 12 的显卡
- 无需安装，绿色免安装版

> macOS / Linux 目前没有原生构建，需借助 Wine 等兼容层运行。

### 操作

| 按键 | 动作 |
|:--|:--|
| `W` `A` `S` `D` | 移动 |
| `Left Shift` | 冲刺（有冷却） |
| `鼠标左键` | 攻击 |
| `E` | 与场景物件交互（门、箱子、祭坛等） |

### 技术栈

- **引擎**：Unity 2022.3.57f1 LTS
- **渲染**：Universal Render Pipeline（2D Renderer）
- **美术**：像素风 Tilemap + Sprite Animation
- **输入**：Unity Legacy Input Manager

### 关于本仓库

本仓库用于分发游戏的**可运行构建**，源码不在其中。每次发版会在 Releases 里附上对应平台的压缩包，构建说明与更新记录见 [CHANGELOG](CHANGELOG.md)。

### 素材致谢

| 素材 | 作者 |
|:--|:--|
| Pixel Art Top Down - Basic | [Cainos](https://assetstore.unity.com/publishers/45656) |
| Hero Knight - Pixel Art | Sven Thole |
| Unity Engine & URP | Unity Technologies |

第三方素材版权归各自作者所有，本项目仅以学习 / 演示为目的使用。

---

## English

### Download & Play

Grab `Slumberland-v0.1.0-win64.zip` (~234 MB) from the **[latest release](../../releases/latest)**, unzip it, and run `Slumberland/SL_Game.exe`.

- **OS**: Windows 10 / 11, 64-bit
- **GPU**: anything with DirectX 11 / 12 support
- Portable build — no installation required

> No native macOS / Linux build yet; you'd need a compatibility layer such as Wine.

### Controls

| Input | Action |
|:--|:--|
| `W` `A` `S` `D` | Move |
| `Left Shift` | Dash (on cooldown) |
| `Left Mouse Button` | Attack |
| `E` | Interact with doors, chests, altars, etc. |

### Tech Stack

- **Engine**: Unity 2022.3.57f1 LTS
- **Rendering**: Universal Render Pipeline (2D Renderer)
- **Art**: pixel-art tilemaps & sprite animation
- **Input**: Unity Legacy Input Manager

### About This Repository

This repository ships **playable builds**, not the source project. Each version is attached to a release as a platform-specific archive — see [CHANGELOG](CHANGELOG.md) for build notes.

### Credits

| Asset | Author |
|:--|:--|
| Pixel Art Top Down - Basic | [Cainos](https://assetstore.unity.com/publishers/45656) |
| Hero Knight - Pixel Art | Sven Thole |
| Unity Engine & URP | Unity Technologies |

Third-party assets remain the property of their respective authors and are used here for demo / learning purposes.

---

### License / 授权

**All rights reserved / 保留所有权利** — 本仓库未授予任何开源许可。完整条款见 [LICENSE](LICENSE)，第三方素材见 [THIRD-PARTY-NOTICES](THIRD-PARTY-NOTICES.md)。

| 可以做 / Allowed | 不可以 / Not allowed |
|:--|:--|
| 下载发行版并游玩（个人非商业） | 复制、修改、再分发代码 |
| 浏览仓库、分享链接 | 重新上传构建包 / 提取素材 |
| 评论、评测时引用短片段 | 用于其他产品或商业用途 |

任何超出上述范围的使用，需事先取得作者书面许可。<br>
Any use beyond the above requires prior written permission from the author.

> Repository contents © 2026 Nicolat777. Third-party art assets (Cainos, Hero Knight) and the Unity engine are **not** covered by this notice — see [THIRD-PARTY-NOTICES](THIRD-PARTY-NOTICES.md).
