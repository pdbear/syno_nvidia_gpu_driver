# Attention
请慎重使用该驱动，如果您使用该驱动导致了数据损毁，系统故障等问题，本人概不负责。

Please use this driver with caution. If you encounter data loss, system malfunction or any other issues caused by the use of this driver, I will not be responsible for any damages.


# 介绍 - Introduction

One of the important uses of Synology NAS is to set up a home media server, and transcoding plays a crucial role in home media services. The hardware decoder integrated in GPUs provides this capability.

群晖的重要用途之一就是搭建家庭媒体服务器，而家庭媒体服务中的转码显得尤为重要，GPU中集成的硬件解码器能够提供该能力。

In order to enable Synology NAS to utilize Nvidia GPUs, I have conducted relevant adaptations. Currently, full support is available for GPU and GRID vGPU, including Offcial Synology + GPU, Physical Xpenology + GPU, Virtual Machine Xpenology + GPU passthrough, and Virtual Xpenology + GRID vGPU.

为了让群晖能够使用Nvidia的GPU，本人为此进行相关的适配，目前可以完整支持GPU和GRID vGPU，同时支持白群晖 + GPU，物理黑群晖 + GPU，虚拟黑群晖 + 直通GPU，虚拟黑群晖 + GRID vGPU。

# 特性 - Feature
- Base GPU Driver Version: 510.108.03 -> 525.105.17 -> 535.154.05 -> 550
- Most DSM support：all x86_64 platform with 7.2+ version.
- Most vGPU support：Tesla P4, P40, T4， and 40HX/2080Ti/2060(vgpu_unlock).
- Most GPU support: from 750Ti to 40+.


# 教程 - Usage

- 中文简体: https://blog.kkk.rs/archives/12 (full)
- English: https://blog.kkk.rs/archives/17

---

xxxx-sign.spk need with https://github.com/XPEnology-Community/SimplePermissionManager (thansks @jim3ma )

xxxx-unsign.spk need with ssh `vgpuDaemon fix`

---

# 相关仓库 - Related repo
Thanks a lot for the contributions of all the predecessors.

- ARPL-i18n(Xpenology): https://github.com/wjz304/arpl-i18n
- FastApi-DLS(vGPU auth): https://hub.docker.com/r/collinwebdesigns/fastapi-dls
- vGPU Driver archive: https://github.com/justin-himself/NVIDIA-VGPU-Driver-Archive
- vGPU unlock: [Origin verison](https://github.com/DualCoder/vgpu_unlock)     [Rust version](https://github.com/mbilker/vgpu_unlock-rs)


# 关于作者 - About
> 作者：皮蛋熊(pdbear)

> Q群： 存于网站 [关于蔚然小站](https://blog.kkk.rs/about) 关于页面中

> Telegram: Synology Nvidia GPU [join group](https://t.me/+FJef7el3Q_M1MjY1)

