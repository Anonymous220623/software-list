## 逆向工程工具/平台

### 一. 逆向工程平台/工具集

#### Windows/MacOS/Linux 平台可执行文件

> [!IMPORTANT]
> 
> 此处列出的软件包含反汇编、反编译 (除了 Detect It Easy)、内存探测和分析等下述列出的几乎所有功能。

1. **Ghidra**：由美国国家安全局创建和维护的软件逆向工程框架，内置丰富的功能插件。
   
   - GitHub 仓库：https://github.com/NationalSecurityAgency/ghidra

2. **Radare2**：基于命令行的逆向工程平台。
   
   - GitHub 仓库：https://github.com/radareorg/radare2
   
   - 官网：https://rada.re
   
   - **iaito**：Radare2 官方提供的 GUI。
     
     - GitHub 仓库：https://github.com/radareorg/iaito

3. **Cutter**：基于 [Rizin](https://github.com/rizinorg/rizin)（Radare2 的分支）项目、Ghidra C 语言反编译器等开源项目的逆向工程平台。
   
   - 官网：https://cutter.re
   - GitHub 仓库：https://github.com/rizinorg/cutter

4. **Angr**：使用 Python 开发的逆向工程平台。
   
   - GitHub 仓库：https://github.com/angr/angr
   - 官网：http://angr.io

5. **Detect It Easy (DiE)**：可执行文件信息分析和反汇编工具。
   
   - Horsicq 作者主页：https://horsicq.github.io
   - GitHub 仓库：https://github.com/horsicq/Detect-It-Easy

#### Android 平台应用程序/Java 字节码和软件包

1. **jadx**：Android/Java 应用程序包分析和逆向工具套件。
   
   - GitHub 仓库：https://github.com/skylot/jadx

#### .NET C#/VB 应用程序

1. **dnSpy**：.NET 程序集逆向工具集。
   
   - 官网：https://dnspy.org
   - GitHub 原仓库（已存档，不再维护）：https://github.com/dnSpy/dnSpy
   - 非官方维护 GitHub 仓库：https://github.com/dnSpyEx/dnSpy

2. **ilSpy**：.NET 程序集逆向工具集。
   
   - GitHub 仓库：https://github.com/icsharpcode/ILSpy

### 二. 应用程序资源提取器和编辑器

1. **RisohEditor**：Windows 可执行文件资源反编译器、编译器和编辑器（支持的平台：Linux/MacOS+Wine、Windows、ReactOS）。
   
   - GitHub 仓库：https://github.com/katahiromz/RisohEditor

### 三. 应用程序调试/内存探查工具

1. **x64dbg**：Windows 用户模式调试工具集（GUI）。
   
   - 官网：https://x64dbg.com
   - GitHub 仓库：https://github.com/x64dbg/x64dbg
   - SourceForge Snapshots：https://sourceforge.net/projects/x64dbg/files/snapshots

### 四. 应用程序脱壳工具

#### .NET 应用程序

1. **.NET Reactor Slayer**：针对 [.NET Reactor 加壳工具](https://www.eziriz.com/dotnet_reactor.htm)的脱壳工具。
   
   - 开发者 SychicBoy 官网主页：https://www.codestrikers.org
   - GitHub 仓库：https://github.com/SychicBoy/NETReactorSlayer

## 应用跨平台运行辅助工具和安全性测试工具

### 一. 应用兼容层

1. **Wine**：能在类 Unix 系统上运行大多数 Windows 应用程序的容器，由 WineHQ 社区发起并维护，CodeWeavers 等商业公司/基金会提供项目贡献和资金支持，[CrossOver](https://www.codeweavers.com/crossover) 是 CodeWeavers 在此基础上开发的商业版本。
   
   - 官网：https://www.winehq.org
   
   - GitHub 镜像仓库：https://github.com/wine-mirror/wine
   
   - GitLab 仓库：https://gitlab.winehq.org/wine/wine
   
   - 由第三方维护的 wine-builds 项目 **（提供 Wine 已编译的可执行文件）**：
     
     - https://github.com/Kron4ek/Wine-Builds
   
   - **Proton**：由 Value 维护的基于 Wine 等开源软件的 Windows 游戏运行平台，用于 SteamOS。
     
     - GitHub 仓库：https://github.com/ValveSoftware/Proton

2. **Cygwin**：将 Linux 应用程序重编译以支持在 Windows 上运行的工具链。
   
   - 官网：https://cygwin.com
   - GitHub 仓库：https://github.com/cygwin/cygwin

### 二. 虚拟机

1. **QEMU**：跨平台虚拟机运行环境。
   
   - 官网：https://www.qemu.org
   - GitLab 仓库：https://gitlab.com/qemu-project/qemu
   - GitHub 镜像仓库：https://github.com/qemu/qemu
   - 官方源码包镜像站：https://download.qemu.org

2. **VirtualBox**：由 Oracle 维护的虚拟机管理工具。
   
   - 开源情况：软件核心部分开源，功能扩展包闭源。
   - 官网：https://www.virtualbox.org
   - VirtualBox 官方发行版与源代码包镜像站：https://download.virtualbox.org/virtualbox
   - VirtualBox SVN 仓库：https://www.virtualbox.org/svn/vbox/trunk

3. **Xen**：轻量级 Linux 虚拟机运行环境。
   
   - GitHub 镜像仓库：https://github.com/xen-project/xen
   - Xen Git 镜像站：https://xenbits.xen.org
   - 官网：http://xenproject.org

### 三. 沙盒

#### Windows

1. **Sandboxie**：用于 Windows 的应用隔离操作环境（分为社区和商业分支，社区分支开源，商业分支闭源收费）。
   
   - GitHub 仓库：https://github.com/sandboxie-plus/Sandboxie
   - 官网：https://sandboxie-plus.com

#### Linux

1. **Firejail**：用于 Linux 的轻量级应用隔离操作环境。
   
   - GitHub 仓库：https://github.com/netblue30/firejail
   - 项目主页：https://firejail.wordpress.com

## 应用程序开发相关工具

### 一. 文本编辑器

### 二. 集成开发环境

### 三. 调试器

#### 命令行/后端

1. **LLDB**：LLVM/Clang 官方命令行调试器。
   
   - LLDB 项目主页：https://lldb.llvm.org
   
   - LLVM 项目 GitHub 仓库：https://github.com/llvm/llvm-project
   
   - LLDB 源码目录：`./lldb/*`

2. **GDB**：GCC 官方命令行调试器。
   
   - GDB Git 仓库：https://sourceware.org/git/binutils-gdb.git
   
   - GDB 项目主页：https://sourceware.org/gdb

## 网络相关工具

### 一. 正向代理客户端

1. **v2rayN**：系统代理管理工具，基于 v2ray 核心。
   
   - GitHub 仓库：https://github.com/2dust/v2rayN
   - 项目主页：https://v2rayn.2dust.link

2. **Clash Meta For Android**（CMFA）：Android 系统代理管理工具。
   
   - GitHub 仓库：https://github.com/MetaCubeX/ClashMetaForAndroid

3. **Clash Verge**：跨平台桌面系统代理管理工具。
   
   - GitHub 仓库：https://github.com/clash-verge-rev/clash-verge-rev
   - 官网：https://www.clashverge.dev

### 二. 反向代理客户端

1. **Sheas-Cealer**：SNI 伪造工具，用于无代理突破特定网站访问限制。
   
   - Windows 版本 GitHub 仓库：https://github.com/SpaceTimee/Sheas-Cealer
   - Android 版本 GitHub 仓库：https://github.com/SpaceTimee/Sheas-Cealer-Droid
   - 上游伪造规则存储库：https://github.com/SpaceTimee/Cealing-Host

## 音视频编解码库

1. **FFmpeg**：跨平台音视频编解码库（GPL）。
   
   - Git 仓库：https://git.ffmpeg.org/ffmpeg.git
   - GitHub 镜像仓库：https://github.com/FFmpeg/FFmpeg
   - 官网：https://ffmpeg.org

2. **x265**：H.265 视频编解码库（GPL & 商业许可）。
   
   - 官网：https://www.x265.org
   - BitBucket 仓库：https://bitbucket.org/multicoreware/x265_git

3. **x262**：H.262 视频编解码库（GPL）。
   
   - Git 仓库：
     
     - [https://git.videolan.org/?p=x262.git;a=summary](https://git.videolan.org/?p=x262.git;a=summary)（浏览器访问）
     - [http://git.videolan.org/git/x262.git](http://git.videolan.org/git/x262.git)（Git 访问）

4. **x264**：H.264 视频编解码库（GPL & 商业许可）。
   
   - VideoLan x264 项目主页：https://www.videolan.org/developers/x264.html
   - GitLab 仓库：https://code.videolan.org/videolan/x264.git
