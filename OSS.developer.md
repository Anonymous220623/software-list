# Developer 开源软件列表

> [!NOTE]
> 
> 此列表包含开发者/技术爱好者可能感兴趣的知名开源软件项目。

## 逆向工程工具/平台

### 一. 逆向工程平台/工具集

#### Windows/MacOS/Linux 平台可执行文件

> [!IMPORTANT]
> 
> 除 Detect It Easy 以外，此处列出的软件包含反汇编、反编译、内存探测和分析等下述列出的几乎所有功能。

1. **Ghidra**：基于 Java 的软件逆向工程框架，内置丰富的功能插件。该项目由 NSA 发起。
   
   - GitHub 仓库：https://github.com/NationalSecurityAgency/ghidra

2. **Radare2**：跨平台的 Linux 风格命令行逆向工程平台。
   
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

1. **Jadx**：Android/Java 应用程序包分析和逆向工程平台。
   
   - GitHub 仓库：https://github.com/skylot/jadx

2. **Bytecode Viewer**：内置多反编译器的 Android/Java 逆向工程平台。
   
   - 官网：https://bytecodeviewer.com
   
   - GitHub 仓库：https://github.com/Konloch/bytecode-viewer

#### .NET C#/VB 应用程序

1. **dnSpy**：.NET 程序集逆向工程平台。
   
   - 官网：https://dnspy.org
   - GitHub 原仓库（已存档，不再维护）：https://github.com/dnSpy/dnSpy
   - 仍在维护 GitHub 仓库（非官方分支）：https://github.com/dnSpyEx/dnSpy

2. **ilSpy**：.NET 程序集逆向工程平台。
   
   - GitHub 仓库：https://github.com/icsharpcode/ILSpy

### 二. 可执行文件资源管理工具

#### Windows 可执行文件

1. **RisohEditor**：Windows 可执行文件资源管理工具（查看/编辑可执行文件资源、资源文件编译/反编译），旨在替代 Resource Hacker（支持的平台：Linux/MacOS+Wine、Windows、ReactOS）。
   
   - GitHub 仓库：https://github.com/katahiromz/RisohEditor

2. **XN Resource Editor**：同 Resource Hacker 的早期版本，已停止维护。
   
   - GitHub 仓库：https://github.com/stefansundin/xn_resource_editor

### 三. 应用程序调试/内存探查工具

1. **x64dbg**：Windows 用户模式调试工具集合【GUI】。
   
   - 官网：https://x64dbg.com
   - GitHub 仓库：https://github.com/x64dbg/x64dbg
   - SourceForge Snapshots：https://sourceforge.net/projects/x64dbg/files/snapshots

### 四. 应用程序脱壳工具/反混淆工具

#### .NET 应用程序

1. **.NET Reactor Slayer**（C#/.NET）：针对 [.NET Reactor 加壳工具](https://www.eziriz.com/dotnet_reactor.htm)的脱壳工具。
   
   - 开发者 SychicBoy 官网主页：https://www.codestrikers.org
   - GitHub 仓库：https://github.com/SychicBoy/NETReactorSlayer

2. **de4dot**（C#/.NET）：.NET 反混淆工具和脱壳工具（命令行）。
   
   - GitHub 仓库（已存档，不再维护）：https://github.com/de4dot/de4dot
   - 仓库分支：
     - 提供对 vanilla ConfuserEx 全面支持的 de4dot 的分支（已存档，不再维护）：https://github.com/ViRb3/de4dot-cex

### 五. 十六进制文本编辑器

1. **ImHex**（C++）：跨平台十六进制文本分析器和编辑器。
   
   - 官网：https://imhex.werwolv.net
   - GitHub 仓库：https://github.com/WerWolv/ImHex

### 六. 应用程序依赖项分析工具

1. **Dependencies**：Windows 可执行文件依赖项分析工具【貌似已停止维护】
   
   - GitHub 仓库：https://github.com/lucasg/Dependencies

## 应用跨平台运行辅助工具和安全性测试工具

### 一. 应用兼容层

1. **Wine**：能在类 Unix 系统上运行大多数 Windows 应用程序的容器，由 WineHQ 社区发起并维护，CodeWeavers 等商业公司/基金会提供项目贡献和资金支持，[CrossOver](https://www.codeweavers.com/crossover) 是 CodeWeavers 在此基础上开发的商业版本。
   
   - 官网：https://www.winehq.org
   - GitLab 仓库：https://gitlab.winehq.org/wine/wine
   - GitHub 镜像仓库：https://github.com/wine-mirror/wine
   - 由第三方维护的 wine-builds 项目（**提供 Wine 已编译的可执行文件**）：
     - [GitHub: Kron4ek/Wine-Builds](https://github.com/Kron4ek/Wine-Builds) 提供 Linux 的 Wine 和 Proton 版本
     - [GitHub: Gcenx/macOS_Wine_builds](https://github.com/Gcenx/macOS_Wine_builds) 提供 macOS 的 Wine 版本
     - [清华大学开源软件镜像站的 wine-builds 仓库](https://mirrors.tuna.tsinghua.edu.cn/help/wine-builds)（APT 镜像，推荐大陆用户访问以提升下载速度）
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
   - GitHub 仓库（非镜像，由 Oracle 官方维护，可能存在更新延迟【5 ~ 7 天同步一次】）：https://github.com/VirtualBox/virtualbox

3. **Xen**：轻量级 Linux 虚拟机运行环境。
   
   - GitHub 镜像仓库：https://github.com/xen-project/xen
   - Xen Git 镜像站：https://xenbits.xen.org
   - 官网：http://xenproject.org

### 三. 沙盒

#### Windows

1. **Sandboxie**：用于 Windows 的应用隔离操作环境（项目完全开源，但个人非商业用途免费许可证的功能受限，通过给该项目贡献代码、修复漏洞或购买贡献许可证可使用全部功能）。
   
   - GitHub 仓库：https://github.com/sandboxie-plus/Sandboxie
   - 官网：https://sandboxie-plus.com

#### Linux

1. **Firejail**：用于 Linux 的轻量级应用隔离操作环境。
   
   - GitHub 仓库：https://github.com/netblue30/firejail
   - 项目主页：https://firejail.wordpress.com

## 应用程序开发相关工具

### 一. 文本编辑器

#### 图形用户页面

1. **Notepad++**（Win32/C++）：Windows 平台文本和代码编辑器。
   
   - GitHub 仓库：https://github.com/notepad-plus-plus/notepad-plus-plus
   - 官网：https://notepad-plus-plus.org

2. **Notepad Next**（Qt/C++）：跨平台文本和代码编辑器，旨在替代 Notepad++ 依赖于单一 Windows 平台的特性。

   - GitHub 仓库：https://github.com/dail8859/NotepadNext

3. **Notepad--**（Qt/C++）：跨平台文本和代码编辑器，旨在替代 Notepad++ 依赖于单一 Windows 平台的特性。
   
   - 备注：优先访问 Gitee 仓库以获取最新更新。
   - GitHub 仓库（更新延迟）：https://github.com/cxasm/notepad--
   - Gitee 仓库：https://gitee.com/cxasm/notepad--

4. **Notepads**（C#/.NET/UWP）：Windows 平台文本和代码编辑器。
   
   - GitHub 仓库：https://github.com/0x7c13/Notepads
   - 官网：https://www.notepadsapp.com

#### 命令行页面

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

### 二. 反向代理/SNI 伪造客户端

1. **Sheas-Cealer**：SNI 伪造工具，用于无代理突破特定网站访问限制，适用于 Chromium 内核的浏览器。
   
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

5. **vvenc**/**vvdec**：H.266 视频编解码库（BSD 3 Clause Clear 许可证）
   
   - vvenc GitHub 仓库：https://github.com/fraunhoferhhi/vvenc
   - vvdec GitHub 仓库：https://github.com/fraunhoferhhi/vvdec
