<p align="center">
  <img src="assets/banner.svg" alt="空情心白 · heartpain-kong — Legged Locomotion, Embedded Control, RoboCon" width="100%">
</p>

<p align="center">
  <sub>把控制理论写进固件，让机器真正跑起来</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/方向-四足运控_%2F_嵌入式底层-150B18?style=flat-square&logoColor=F9A8D4" alt="focus">
  <img src="https://img.shields.io/badge/栈-C_%2F_C%2B%2B_%2F_Python-150B18?style=flat-square&logoColor=C084FC" alt="stack">
  <img src="https://komarev.com/ghpvc/?username=heartpain-kong&label=主页访问&color=150B18&style=flat-square" alt="profile views">
</p>

## 🧭 关于我

- 🔧 **嵌入式底层**：STM32H7（H723 / DM-MC02-H7）平台开发，CAN-FD、RS485、DMA 与 Cache 一致性、USB 设备
- 🤖 **机器人运控**：四足步态与运动控制，持续跟进 HIM / H∞ 一类基于学习的运控方法
- 🏁 **RoboCon**：赛题与场地建模（XML），舵轮 / 麦轮底盘控制例程
- 📚 **乐于沉淀**：把调试时踩过的坑写成能复现的文档，顺手整理运控学习资料
- 🎯 **当前重心**：完善 DM02 开源代码里的电机驱动与底盘例程，让新队伍少走弯路

> 我相信好的开源不只是"能跑"，而是"别人照着文档也能跑起来"。

## 🛠 技术栈

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32">
  <img src="https://img.shields.io/badge/CAN--FD-1F6FEB?style=flat-square" alt="CAN-FD">
  <img src="https://img.shields.io/badge/RS485-1F6FEB?style=flat-square" alt="RS485">
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

## 📦 精选项目

| 项目 | 简介 | 技术 |
| :--- | :--- | :--- |
| **[DM02_control](https://github.com/heartpain-kong/DM02_control)** <br> ![stars](https://img.shields.io/github/stars/heartpain-kong/DM02_control?style=flat-square&color=F472B6&labelColor=150B18) | 达妙 DM-MC02-H7 开发板开源代码：宇树 / 灵足 / 达妙 / DJI 电机驱动库、大疆遥控器例程、舵轮与麦轮底盘控制，附 RS485 时隙、Cache 与 DMA、CAN-FD 分频等实战说明 | `C` `STM32H7` |
| **[LGRobotSystem](https://github.com/heartpain-kong/LGRobotSystem)** <br> ![stars](https://img.shields.io/github/stars/heartpain-kong/LGRobotSystem?style=flat-square&color=F472B6&labelColor=150B18) | 基于 STM32H723 的机器人控制系统固件：CubeMX + CMake 工程、USB 设备栈，含 DAPLink / ST-Link 烧录配置 | `C` `STM32H723` `USB` |
| **[rc2027_field](https://github.com/heartpain-kong/rc2027_field)** <br> ![stars](https://img.shields.io/github/stars/heartpain-kong/rc2027_field?style=flat-square&color=F472B6&labelColor=150B18) | RoboCon 2027 场地 XML 文件，供仿真与场地建模直接复用 | `Python` `XML` |
| **[LocoWiki](https://github.com/heartpain-kong/LocoWiki)** <br> ![stars](https://img.shields.io/github/stars/heartpain-kong/LocoWiki?style=flat-square&color=F472B6&labelColor=150B18) | 机器人运控学习指南：赛题拆解、知识库、论文学习资源，在线版见 [locowiki.github.io](https://locowiki.github.io/) | `Docs` |

## 📊 GitHub 数据

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=heartpain-kong&show_icons=true&hide_title=true&hide_border=true&bg_color=150B18&title_color=F9A8D4&icon_color=C084FC&text_color=E8D5E2&ring_color=F472B6&card_width=480" alt="GitHub 统计" width="480">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=heartpain-kong&layout=compact&hide_border=true&bg_color=150B18&title_color=F9A8D4&text_color=E8D5E2&langs_count=6&card_width=480&exclude_repo=LocoWiki,HIMLoco,damiao_mc02_bsp,the_past_of_curc-robocon,LeggedWiki.github.io" alt="主要语言" width="480">
</p>

## 📚 学习与分享

- **[LocoWiki](https://locowiki.github.io/)** — 四足运控入门路线：从基础理论到论文复现的索引
- **[HIMLoco](https://github.com/heartpain-kong/HIMLoco)** — Hybrid Internal Model 与 H∞ 运控的官方实现（跟进中）
- **[damiao_mc02_bsp](https://github.com/heartpain-kong/damiao_mc02_bsp)** — 达妙 DM-MC02-H7 底层库参考

## 📫 联系我

<p>
  <a href="https://github.com/heartpain-kong"><img src="https://img.shields.io/badge/GitHub-heartpain--kong-150B18?style=flat-square&logo=github&logoColor=F9A8D4" alt="GitHub"></a>
  <a href="https://github.com/heartpain-kong/DM02_control/issues"><img src="https://img.shields.io/badge/提问-DM02_control_Issues-150B18?style=flat-square&logo=github&logoColor=C084FC" alt="issues"></a>
</p>

欢迎交流机器人、运控与嵌入式方面的任何问题；提 Issue 或直接开 PR 都很快回复。

---

<p align="center">
  <sub><b>In brief</b> — I build legged-robot motion control and embedded firmware (STM32H7, CAN-FD, motor drivers), and write down what I learn along the way.</sub>
</p>

<p align="center">
  <sub>如果这些仓库帮到了你，一个 ⭐ 就是最好的鼓励 · Built with ❤️ and a lot of oscilloscope traces</sub>
</p>
