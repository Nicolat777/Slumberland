![Slumberland — Prelude to the Long Banquet](docs/banner.png)

一款 Unity 制作的 2D 像素风俯视角动作 Demo。在安静的像素世界里走动，挥剑、冲刺，把一切看起来能交互的东西都戳一遍——门、箱子、祭坛。

<p>
  <a href="README.md">English</a> · <b>简体中文</b>
</p>

![Unity](https://img.shields.io/badge/Unity-2022.3.57f1-000000?logo=unity&logoColor=white)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-0078D6?logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/version-v0.1.0-orange)
![Status](https://img.shields.io/badge/status-demo-blue)
![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red)

---

## 截图

**标题界面**

![标题界面](docs/screenshots/01-title.jpg)

**探索** —— 俯视角移动，左上角 HP / MP，底部经验条

![探索](docs/screenshots/02-exploration.jpg)

**对话** —— 角色立绘与对白

![对话](docs/screenshots/03-dialogue.jpg)

---

## 下载游玩

前往 **[Releases](https://github.com/Nicolat777/Slumberland/releases/latest)** 下载 `Slumberland-v0.1.0-win64.zip`（约 234 MB），解压后双击 `Slumberland/SL_Game.exe` 即可开始。

- **系统**：Windows 10 / 11，64 位
- **显卡**：支持 DirectX 11 / 12 的显卡
- 无需安装，绿色免安装版

> macOS / Linux 目前没有原生构建，需借助 Wine 等兼容层运行。

## 操作

| 按键 | 动作 |
|:--|:--|
| `W` `A` `S` `D` | 移动 |
| `Left Shift` | 冲刺（有冷却） |
| `鼠标左键` | 攻击 |
| `E` | 与场景物件交互（门、箱子、祭坛等） |

## 技术栈

- **引擎**：Unity 2022.3.57f1 LTS
- **渲染**：Universal Render Pipeline（2D Renderer）
- **美术**：像素风 Tilemap + Sprite Animation
- **输入**：Unity Legacy Input Manager

## 关于本仓库

本仓库用于分发游戏的**可运行构建**，源码不在其中。每次发版会在 Releases 里附上对应平台的压缩包，构建说明与更新记录见 [CHANGELOG](CHANGELOG.md)。

## 素材致谢

| 素材 | 作者 |
|:--|:--|
| [Pixel Art Top Down - Basic](https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605) | Cainos |
| [Hero Knight - Pixel Art](https://assetstore.unity.com/packages/2d/characters/hero-knight-pixel-art-165188) | Sven Thole |
| Unity Engine & URP | Unity Technologies |

第三方素材版权归各自作者所有，本项目仅以学习 / 演示为目的使用。

---

## 授权

**保留所有权利** —— 本仓库未授予任何开源许可。完整条款见 [LICENSE](LICENSE)，第三方素材见 [THIRD-PARTY-NOTICES](THIRD-PARTY-NOTICES.md)。

| 可以做 | 不可以 |
|:--|:--|
| 下载发行版并游玩（个人非商业） | 复制、修改、再分发代码 |
| 浏览仓库、分享链接 | 重新上传构建包 / 提取素材 |
| 评论、评测时引用短片段 | 用于其他产品或商业用途 |

任何超出上述范围的使用，需事先取得作者书面许可。

> 仓库内容 © 2026 Nicolat777。第三方美术素材（Cainos、Hero Knight）与 Unity 引擎**不包含**在授权范围内，详见 [THIRD-PARTY-NOTICES](THIRD-PARTY-NOTICES.md)。
