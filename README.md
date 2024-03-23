<img src="https://geysermc.org/img/geyser-1760-860.png" alt="Geyser" width="600"/>

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/613163671870242838.svg?color=%237289da&label=discord)](https://discord.gg/geysermc)
[![Crowdin](https://badges.crowdin.net/geyser/localized.svg)](https://translate.geysermc.org/)

Geyser是 Minecraft: 基岩版 和 Minecraft: Java版 之间的桥梁，缩小了那些想要玩真正跨平台游戏的人之间的差距。
Geyser是[CubeCraft Games]（https://cubecraft.net）的开放式合作项目。

## 什么是Geyser？
Geyser是一个代理，弥合了 Minecraft: 基岩版 和 Minecraft：Java版 服务器之间的差距。
该项目的最终目标是让 Minecraft：基岩版 用户尽可能无缝地加入 Minecraft: Java 版 服务器。但是，由于Geyser通过两个不同游戏的网络转换数据包的性质，*不要指望一切都能完美运行！

特别感谢DragonProxy项目成为协议翻译的开拓者，并感谢所有加入我们的团队成员！

### 目前支持基岩版 1.20.40-1.20.72 Java版 1.20.4

## 开始设置
看看 [这里]（https://wiki.geysermc.org/geyser/setup/） 如何设置Geyser。

[![YouTube Video](https://img.youtube.com/vi/U7dZZ8w7Gi4/0.jpg)](https://www.youtube.com/watch?v=U7dZZ8w7Gi4)

大陆地区无法访问。

## 友情链接：
- 网站: https://geysermc.org
- 文档: https://wiki.geysermc.org/geyser/
- 下载: https://geysermc.org/download
- Discord: https://discord.gg/geysermc
- 赞助: https://opencollective.com/geysermc
- 测试服务器: `test.geysermc.org`Java版端口`25565`基岩版端口`19132`
- Java版无需输入端口就能连接，因为默认就是25565
- 基岩版端口为默认的19132

## 还有待添加/修复的内容
- 近乎完美的运动（以至于大型服务器上的反作弊不太可能禁止您）
- 一些实体标志
- 结构块 UI

## 我们无法修复的内容
由于 Minecraft Bedrock 和 Java 之间的各种差异，Geyser 无法支持一些事情。有关这些限制的列表，请参阅 [当前限制]（https://wiki.geysermc.org/geyser/current-limitations/） 页面。

## 构建/编译
1. 将存储库克隆到计算机
3. 导航到 Geyser 根目录并运行“git submodule update --init --recursive”。此命令下载间歇泉所需的所有子模块，是此过程中的关键步骤。
4. 运行“gradlew build”并找到“bootstrap/build”文件夹。

## 贡献
任何贡献都是值得赞赏的。如果出现以下情况，请随时在 [Discord]（http://discord.geysermc.org/） 上与我们联系
如果你有兴趣帮助间歇泉。

## 使用的库：
- [Adventure Text Library](https://github.com/KyoriPowered/adventure)
- [NukkitX Bedrock Protocol Library](https://github.com/NukkitX/Protocol)
- [Steveice10's Java Protocol Library](https://github.com/Steveice10/MCProtocolLib)
- [TerminalConsoleAppender](https://github.com/Minecrell/TerminalConsoleAppender)
- [Simple Logging Facade for Java (slf4j)](https://github.com/qos-ch/slf4j)
