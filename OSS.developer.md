# Developer 开源软件列表

> [!NOTE]
> 
> 此列表包含开发者/技术爱好者可能感兴趣的知名开源软件项目。

## 应用程序开发相关工具

### 一. 文本编辑器

#### 图形用户页面

1. **Notepad Next**（Qt/C++）：跨平台文本和代码编辑器，旨在替代 Notepad++ 依赖于单一 Windows 平台的特性。

   - GitHub 仓库：https://github.com/dail8859/NotepadNext

2. **Notepad--**（Qt/C++）：跨平台文本和代码编辑器，旨在替代 Notepad++ 依赖于单一 Windows 平台的特性。
   
   - 备注：优先访问 Gitee 仓库以获取最新更新。
   - GitHub 仓库（更新延迟）：https://github.com/cxasm/notepad--
   - Gitee 仓库：https://gitee.com/cxasm/notepad--

3. **wxMEdit**：跨平台文本/十六进制数据编辑器，[MadEdit](http://sourceforge.net/projects/madedit) 的延续版本。

   - 项目主页：https://wxmedit.github.io
   - GitHub 仓库：https://github.com/wxMEdit/wxMEdit

##### 仅支持 Windows 平台

1. **Notepad++**（Win32/C++）：Windows 平台文本和代码编辑器。
   
   - 官网：https://notepad-plus-plus.org
   - GitHub 仓库：https://github.com/notepad-plus-plus/notepad-plus-plus

2. **Notepads**（C#/.NET/UWP）：Windows 平台文本和代码编辑器。
   
   - 官网：https://www.notepadsapp.com
   - GitHub 仓库：https://github.com/0x7c13/Notepads

#### 命令行页面

1. **Vim**：最著名的跨平台命令行文本编辑器，拥有广泛的插件支持。

   - 官网：https://www.vim.org
   - GitHub 仓库：https://github.com/vim/vim

2. **Helix**：使用 Rust 开发的跨平台文本编辑器。

   - 官网：https://helix-editor.com
   - GitHub 仓库：https://github.com/helix-editor/helix

3. **Zep**：嵌入式、轻量级命令行文本编辑器。

   - GitHub 仓库：https://github.com/Rezonality/zep

##### 仅支持 Linux 平台

1. **nano**：Linux 命令行文本编辑器，GNU 项目的一部分。

   - 官网：https://nano-editor.org
   - Git 仓库 1：https://git.savannah.gnu.org/git/nano.git
   - Git 仓库 2：https://git.wh0rd.org/nano-editor.git

### 二. 集成开发环境

1. **Visual Studio Code**（VSCode）：微软使用 TypeScript/Electron 开发的跨平台集成开发环境，拥有广泛的插件支持。

   - 官网：https://code.visualstudio.com
   - GitHub 仓库：https://github.com/microsoft/vscode

2. **VSCodium**：VSCode 的社区支持版本，删除了微软服务相关代码，但仍支持 VSCode 的插件仓库。

   - 官网：https://vscodium.com
   - GitHub 仓库（存储修改和构建脚本）：https://github.com/VSCodium/vscodium

3. **Intellij Platform**（产品：[Intellij IDEA Community](https://www.jetbrains.com/idea)/[PyCharm Community Edition](https://www.jetbrains.com/pycharm)）：JetBrains 使用 Java 开发的 IDE 平台，拥有全平台支持和自定义插件集成功能。

   - JetBrains 官网：https://www.jetbrains.com
   - 项目页面：https://www.jetbrains.com/opensource/idea
   - GitHub 仓库：https://github.com/JetBrains/intellij-community

4. **Code::Blocks**：跨平台 C/C++ IDE，用户页面基于 wxWidgets。

   - 官网：https://www.codeblocks.org
   - SourceForge SVN 仓库：https://svn.code.sf.net/p/codeblocks/code/trunk

> [!WARNING]
>
> Eclipse 基金会的 IDE 项目分散在各个代码托管平台、各个群组/组织的数百个仓库中，详细仓库列表信息等待整理。

5. **Eclipse IDE**：由 Eclipse 基金会维护的多语言 IDE 项目，使用 Java 开发，提供跨平台和插件支持。

   - 项目官网：https://eclipseide.org
   - Eclipse 官网：https://www.eclipse.org
   - 软件下载页面：https://www.eclipse.org/downloads/packages

### 三. 调试器

1. **LLDB**：LLVM/Clang 绑定的命令行调试器。
   
   - LLDB 项目主页：https://lldb.llvm.org
   - LLVM 项目 GitHub 仓库：https://github.com/llvm/llvm-project
   - LLDB 源码目录：`./lldb/*`

2. **GDB**：GCC 绑定的命令行调试器。
   
   - GDB 项目主页：https://sourceware.org/gdb
   - GDB Git 仓库：https://sourceware.org/git/binutils-gdb.git

#### 调试器前端

1. **seer**：GDB 前端。

   - GitHub 仓库：https://github.com/epasveer/seer

#### 仅支持 Windows 平台

1. **x64dbg**：Windows 用户模式应用调试器，拥有图形用户界面。
   
   - 官网：https://x64dbg.com
   - GitHub 仓库：https://github.com/x64dbg/x64dbg
   - SourceForge Snapshots：https://sourceforge.net/projects/x64dbg/files/snapshots

2. **HyperDbg**：针对 Intel 具有 VT-x 虚拟化功能的处理器的 Windows 用户/内核模式调试器。

   - 官网：https://hyperdbg.org
   - GitHub 仓库：https://github.com/HyperDbg/HyperDbg

## 逆向工程相关工具

### 一. 逆向工程平台

#### Windows/MacOS/Linux 平台可执行文件

> [!IMPORTANT]
> 
> 1. 除 Detect It Easy 以外，此处列出的软件包含反汇编、反编译、内存探测和分析等下述列出的几乎所有功能。
> 2. 对于因 Ghidra 的政治中立性问题而引发担忧的用户，建议改用 Cutter 或 Angr，或使用 Binary Ninja Free/IDA Freeware/IDA Free，或自行寻找 Binary Ninja Pro/IDA Pro 的破解版本。

1. **Ghidra**：基于 Java 的软件逆向工程框架，内置丰富的功能插件。由美国国家安全局（National Security Agency，NSA）发起并维护。
   
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

5. **ImHex**（C++）：注重十六进制文本分析编辑的逆向工程平台。
   
   - 官网：https://imhex.werwolv.net
   - GitHub 仓库：https://github.com/WerWolv/ImHex

6. **Detect It Easy (DiE)**：可执行文件信息分析和反汇编工具。
   
   - Horsicq 作者主页：https://horsicq.github.io
   - GitHub 仓库：https://github.com/horsicq/Detect-It-Easy
   - GitHub 发行版页面：https://github.com/horsicq/DIE-engine/releases

#### Android 平台应用程序/Java 字节码和软件包

1. **JADX**：Android/Java 应用程序包分析和逆向工程平台。
   
   - GitHub 仓库：https://github.com/skylot/jadx

2. **Bytecode Viewer**：内置多反编译器的 Android/Java 逆向工程平台。
   
   - 官网：https://bytecodeviewer.com
   - GitHub 仓库：https://github.com/Konloch/bytecode-viewer

#### .NET C#/VB 应用程序

1. **dnSpy**：.NET 程序集逆向工程平台。
   
   - 官网：https://dnspy.org
   - GitHub 原仓库（已存档，不再维护）：https://github.com/dnSpy/dnSpy
   - 仍在维护 GitHub 仓库（非官方分支）：https://github.com/dnSpyEx/dnSpy

2. **ILSpy**：.NET 程序集逆向工程平台。
   
   - GitHub 仓库：https://github.com/icsharpcode/ILSpy

### 二. 可执行文件资源管理工具

#### Windows 可执行文件

1. **RisohEditor**：Windows 可执行文件资源管理工具（查看/编辑可执行文件资源、资源文件编译/反编译），旨在替代 Resource Hacker（支持的平台：Linux/MacOS+Wine、Windows、ReactOS）。
   
   - GitHub 仓库：https://github.com/katahiromz/RisohEditor

### 三. 应用程序脱壳/反混淆工具

#### .NET 应用程序

1. **.NET Reactor Slayer**（C#/.NET）：针对 [.NET Reactor 加壳工具](https://www.eziriz.com/dotnet_reactor.htm)的脱壳工具，基于 de4dot。
   
   - 开发者 SychicBoy 官网主页：https://www.codestrikers.org
   - GitHub 仓库：https://github.com/SychicBoy/NETReactorSlayer

2. **de4dot**（C#/.NET）：.NET 反混淆工具和脱壳工具（命令行）。
   
   - GitHub 仓库（已存档，不再维护）：https://github.com/de4dot/de4dot
   - 仓库分支：
     - 提供对 vanilla ConfuserEx 全面支持的 de4dot 的分支（已存档，不再维护）：https://github.com/ViRb3/de4dot-cex

### 四. 应用程序依赖项分析工具

#### Windows PE 文件导入表分析工具

1. **Dependencies**（C#/.NET）：
   
   - GitHub 仓库：https://github.com/lucasg/Dependencies

2. **WinDepends**（C#/.NET）：（暂未发布正式版本）

   - GitHub 仓库：https://github.com/hfiref0x/WinDepends

## 应用跨平台运行辅助工具和安全性测试工具

### 一. 应用兼容层

1. **Wine**：能在类 Unix 系统上运行大多数 Windows 应用程序的容器，由 WineHQ 社区发起并维护，CodeWeavers 等商业公司/基金会提供项目贡献和资金支持，[CrossOver](https://www.codeweavers.com/crossover) 是 CodeWeavers 在此基础上开发的商业版本。
   
   - 官网：https://www.winehq.org
   - GitLab 仓库：https://gitlab.winehq.org/wine/wine
   - GitHub 镜像仓库：https://github.com/wine-mirror/wine
   - 由第三方维护的 wine-builds 项目（**提供 Wine 已编译的可执行文件**）：
     - [GitHub: Kron4ek/Wine-Builds](https://github.com/Kron4ek/Wine-Builds) 提供 Wine 和 Proton 的 Linux 便携版。
     - [GitHub: Gcenx/macOS_Wine_builds](https://github.com/Gcenx/macOS_Wine_builds) 提供 Wine 的 macOS 便携版。
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
   
   - 开源情况：软件主体开源（GPLv3），可选功能扩展包（VirtualBox Extension Pack）闭源，可访问 [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads) 查看详细的许可协议。
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

## 网络相关工具

### 一. 代理工具

#### 正向代理套件（独立协议实现）

1. **Outline**：提供跨平台的服务端和客户端，适合有自部署需求的用户。

   - 官网：https://getoutline.org
   - Jigsaw 的 GitHub 组织：https://github.com/Jigsaw-Code

#### 正向代理客户端（基于开放、通用的网络加密协议）

1. **v2rayN**：跨平台 PC 端系统代理客户端，基于 v2ray（Project V） 核心。
   
   - 项目主页：https://v2rayn.2dust.link
   - GitHub 仓库：https://github.com/2dust/v2rayN
   - **v2rayNG**：v2rayN 的 Android 版本。
      - 项目主页：https://v2rayng.2dust.link
      - GitHub 仓库：https://github.com/2dust/v2rayNG

2. **sing-box**：跨平台命令行代理客户端。

   - 官网：https://sing-box.sagernet.org
   - GitHub 主仓库：https://github.com/SagerNet/sing-box
   - sing-box for Android 的 GitHub 仓库：https://github.com/SagerNet/sing-box-for-android

##### Clash 系列软件

1. **Clash Verge Rev**：跨平台 PC 端系统代理客户端。
   
   - 官网：https://www.clashverge.dev
   - GitHub 仓库：https://github.com/clash-verge-rev/clash-verge-rev
     
2. **Clash Meta For Android**（CMFA）：Android 系统代理客户端。
   
   - GitHub 仓库：https://github.com/MetaCubeX/ClashMetaForAndroid

#### 反向代理工具

1. **开发者边车（DevSideCar）**（JavaScript/Vue）：针对 GitHub、Stack Overflow 等软件开发相关的特定站点的反代工具。

   - GitHub 仓库：https://github.com/docmirror/dev-sidecar

2. **Watt Toolkit（Steam++、SteamTools）**（C#/.NET）：Steam 游戏加速器，亦提供针对游戏服务和软件开发相关的特定站点的反代功能。

   - 官网：https://steampp.net
   - GitHub 仓库：https://github.com/BeyondDimension/SteamTools
   
#### SNI 伪造工具

1. **Sheas Cealer**：SNI 伪造工具，用于无代理突破特定网站访问限制，适用于 Chromium 内核的浏览器。
   
   - Windows 版本 GitHub 仓库：https://github.com/SpaceTimee/Sheas-Cealer
   - Android 版本 GitHub 仓库：https://github.com/SpaceTimee/Sheas-Cealer-Droid
   - 上游伪造规则存储库：https://github.com/SpaceTimee/Cealing-Host

### 二. 网络/通信协议项目

1. **Tor Project**：影响全球的洋葱网络协议和实现项目，由 Tor Project 基金会维护。

   - 官网：https://www.torproject.org
   - GitLab 实例：https://gitlab.torproject.org

2. **Matrix**：分布式开放通信协议系统，亦提供一个免费的通信服务器。

   - 官网：https://matrix.org
   - GitHub 组织：https://github.com/matrix-org
   - 备注：[matrix.org](https://matrix.org) 通信服务器的账户注册条件：电子邮箱地址。

### 三. 网络嗅探分析工具

1. **Wireshark**：强大的网络协议/数据分析工具。

   - 官网：https://www.wireshark.org
   - GitLab 仓库：https://gitlab.com/wireshark/wireshark
   - GitHub 镜像仓库：https://github.com/wireshark/wireshark

2. **Nmap**：网络扫描和主机发现工具，亦提供图形前端 Zenmap。

   - 官网：https://nmap.org
   - SVN 实例：https://svn.nmap.org
   - GitHub 镜像仓库：https://github.com/nmap/nmap

## 渗透测试/漏洞利用工具

1. **Metasploit Framework**：知名的渗透测试框架/工具集，由 [Rapid7](https://www.rapid7.com) 公司开发，主要开发语言为 Ruby，提供各种命令行应用程序（插件），Metasploit Pro 是基于此框架且附带图形用户页面的闭源商业版本。

   - 官网：https://www.metasploit.com
   - GitHub 仓库：https://github.com/rapid7/metasploit-framework

## 版本控制相关工具

### 一. 代码托管和协作平台

1. **GitLab**：基于 Git 的代码托管和协作平台，支持云托管（Free, Premium 和 Ultimate 计划，可前往 [https://about.gitlab.com/pricing](https://about.gitlab.com/pricing) 了解详细信息）和自托管。

   - 官网：[https://gitlab.com](https://gitlab.com)（如果未登录会重定向到 [https://about.gitlab.com](https://about.gitlab.com)）
   - GitLab 群组：https://gitlab.com/gitlab-org
   - 主开发仓库（包含所有具体的提交记录）：https://gitlab.com/gitlab-org/gitlab
   - GitLab FOSS（去除所有专有代码）仓库：https://gitlab.com/gitlab-org/gitlab-foss
   - GitLab Community Edition 仓库：https://gitlab.com/rluna-gitlab/gitlab-ce
   - GitLab Environment Toolkit 仓库：https://gitlab.com/gitlab-org/gitlab-environment-toolkit

2. **Gitea**：基于 Git 的轻量级代码托管和协作平台，支持云托管（Free 和 Enterprise 计划，可前往 [https://about.gitea.com/pricing](https://about.gitea.com/pricing) 了解详细信息）和自托管。
   
   - 官网：[https://gitea.com](https://gitea.com)（如果未登录会重定向到 [https://about.gitea.com](https://about.gitea.com)）
   - GitHub 仓库：https://github.com/go-gitea/gitea
   - Gitea 镜像仓库：https://gitea.com/gitea/gitea-mirror

3. **Forgejo/Codeberg**：基于 Git 的免费，由社区驱动的轻量级代码托管和协作平台。

   - 官网：https://codeberg.org
   - Codeberg 仓库：https://codeberg.org/forgejo/forgejo

#### 桌面端

> [!WARNING]
>
> 1. 以下软件的服务端不开源。
> 2. GitHub Desktop 亦可作为 Git GUI 桌面端使用。

1. **GitHub Desktop**：GitHub 的桌面端。

   - 官网：[https://desktop.github.com](https://desktop.github.com)，重定向到 [https://github.com/apps/desktop](https://github.com/apps/desktop)
   - GitHub 仓库（提供 Windows 和 macOS 版本）：https://github.com/desktop/desktop
   - 非官方 GitHub 仓库（提供 Linux 版本）：https://github.com/shiftkey/desktop

### 二. 版本控制系统前端

#### Git 桌面端

1. **GitButler**：Git GUI 跨平台桌面端。

   - 官网：https://gitbutler.com
   - GitHub 仓库：https://github.com/gitbutlerapp/gitbutler

## 特定格式文件操作库

### 一. 音视频编解码库

1. **FFmpeg**：跨平台音视频编解码库（GPL）。
   
   - 官网：https://ffmpeg.org
   - Git 仓库：https://git.ffmpeg.org/ffmpeg.git
   - GitHub 镜像仓库：https://github.com/FFmpeg/FFmpeg

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

### 二. WIM/ESD 文件操作库

1. **wimlib**：

   - 官网：https://wimlib.net
   - GitHub 仓库：https://github.com/ebiggers/wimlib
