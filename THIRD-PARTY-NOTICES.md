# Third-Party Notices

Slumberland bundles third-party art, engine and library components. These are
**not** covered by [LICENSE](LICENSE) and remain under their own terms. Nothing
in this repository grants you rights to them.

## Art & sprites

| Component | Author / Source | Terms |
|---|---|---|
| [Pixel Art Top Down - Basic](https://assetstore.unity.com/packages/2d/environments/pixel-art-top-down-basic-187605) v1.2.3 (tilesets, props, characters, demo scripts under `Cainos/`) | Cainos — Unity Asset Store, free | Standard Unity Asset Store EULA, **Extension Asset**. Used under the license granted to the downloader. |
| [Hero Knight - Pixel Art](https://assetstore.unity.com/packages/2d/characters/hero-knight-pixel-art-165188) v1.2 (character sprites, animations, `HeroKnight.cs` demo) | Sven Thole — Unity Asset Store, free | Standard Unity Asset Store EULA, **Extension Asset**. Used under the license granted to the downloader. |

The Unity Asset Store EULA generally permits use of these assets **inside your
own finished products** but restricts redistributing the raw asset files
themselves. Both packages are licensed as **Extension Asset**, which under the
Standard EULA means they may be embedded in a build you ship but may not be
redistributed as standalone source files. The compiled builds under Releases
contain these assets in packaged form; do not extract or re-use them separately.

Being free on the Asset Store does not place them in the public domain — they
remain under the Standard EULA and the authors retain copyright.

## Engine & libraries

| Component | Terms |
|---|---|
| Unity Engine 2022.3.57f1 LTS, UnityPlayer, Mono runtime | [Unity Terms of Service](https://unity.com/legal/terms-of-service) / Unity Companion License |
| Universal Render Pipeline (URP) | Unity Companion License |
| TextMeshPro, Input System, Visual Scripting, 2D Animation, Burst, Collections, Timeline, Newtonsoft.Json | Respective Unity package / MIT licenses as shipped with the Unity Editor |

## Build output

`Slumberland-v0.1.0-win64.zip` is a compiled Unity Standalone build. It embeds
the engine runtime and the packaged art listed above; its distribution is
subject to those licenses in addition to [LICENSE](LICENSE).

---

如对某项素材的授权有疑问，请优先查阅 Unity Asset Store 上对应素材包的 EULA 原文。
若你是素材作者并认为此处使用不当，请通过仓库 Issues 联系，我会立即处理。
