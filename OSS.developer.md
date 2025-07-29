> [!WARNING]
>
> 程序开发/逆向工程软件列表不分平台。


## 逆向工程工具/平台

### 一. 逆向工程平台/工具集

#### Windows/MacOS/Linux 平台可执行文件

1. **Ghidra**：由美国国家安全局创建和维护的软件逆向工程（SRE）框架，内置丰富的程序逆向插件。
   
   - GitHub 仓库：https://github.com/NationalSecurityAgency/ghidra

2. **Radare2**：基于命令行的逆向工程平台
   
   - GitHub 仓库：https://github.com/radareorg/radare2
   
   - 官网：https://rada.re
   
   - **iaito**：Radare2 官方提供的 GUI
     
     - GitHub 仓库：https://github.com/radareorg/iaito

3. **Cutter**：基于 [Rizin](https://github.com/rizinorg/rizin)（Radare2 的分支）项目、Ghidra C 语言反编译器等开源项目的逆向工程平台
   
   - 官网：https://cutter.re
   - GitHub 仓库：https://github.com/rizinorg/cutter

4. **Detect It Easy (DiE)**：可执行文件信息分析和反汇编工具。
   
   - Horsicq 作者主页：https://horsicq.github.io
   - GitHub 仓库：https://github.com/horsicq/Detect-It-Easy

#### Android 平台应用程序/Java 字节码和软件包

1. **jadx**：Android/Java 应用程序包分析和逆向工具套件
   
   - GitHub 仓库：https://github.com/skylot/jadx

#### .NET C#/VB 应用程序

1. **dnSpy**：.NET 程序集逆向和调试工具集。
   
   - 官网：https://dnspy.org
   - GitHub 原仓库（已存档，不再维护）：https://github.com/dnSpy/dnSpy
   - 非官方维护 GitHub 仓库：https://github.com/dnSpyEx/dnSpy

2. **ilSpy**：.NET 程序集浏览器和反编译器。
   
   - GitHub 仓库：https://github.com/icsharpcode/ILSpy

### 二. 应用程序资源提取器和编辑器

1. **RisohEditor**：Windows PE 文件资源反编译器、编译器和编辑器（支持的平台：Linux/MacOS+Wine、Windows、ReactOS）。
   
   - GitHub 仓库：https://github.com/katahiromz/RisohEditor

### 三. 应用程序调试/内存探查工具

1. **x64dbg**：Windows 用户模式调试工具集（GUI）。
   
   - 官网：https://x64dbg.com
   - GitHub 仓库：https://github.com/x64dbg/x64dbg
   - SourceForge Snapshots：https://sourceforge.net/projects/x64dbg/files/snapshots

### 四. 应用程序脱壳工具

#### .NET 应用程序

1. **.NET Reactor Slayer**：针对 [.NET Reactor 加壳工具](https://www.eziriz.com/dotnet_reactor.htm)的脱壳工具
   
   - 开发者 SychicBoy 官网主页：https://www.codestrikers.org
   - GitHub 仓库：https://github.com/SychicBoy/NETReactorSlayer

## 应用跨平台运行辅助工具和安全性测试工具

### 一. 应用兼容层

1. **Wine**：能在类 Unix 系统上运行大多数 Windows 应用程序的容器，由 WineHQ 社区发起并维护，CodeWeavers 提供项目贡献和资金支持，[CrossOver](https://www.codeweavers.com/crossover) 是其专业版本。
   
   - 官网：https://www.winehq.org
   
   - CodeWeavers 官网：https://www.codeweavers.com
   
   - GitHub 镜像仓库：https://github.com/wine-mirror/wine
   
   - GitLab 仓库：https://gitlab.winehq.org/wine/wine
   
   - 由第三方维护的 wine-builds 项目 **（提供 Wine 已编译的可执行文件）**：
     
     - https://github.com/Kron4ek/Wine-Builds
   
   - **Proton**：由 Value 维护的基于 Wine 等开源软件的 Windows 游戏运行平台，用于 SteamOS。
     
     - GitHub 仓库：https://github.com/ValveSoftware/Proton
       

### 二. 虚拟机

1. **QEMU**：计算机模拟器（可和 KVM 结合使用以达到和实体机几乎同样的运行效率）
   
   - 官网：https://www.qemu.org
   - GitLab 仓库：https://gitlab.com/qemu-project/qemu
   - GitHub 镜像仓库：https://github.com/qemu/qemu
   - 官方源码包镜像站：https://download.qemu.org

2. **VirtualBox**：由 Oracle 维护的虚拟机管理工具和计算机模拟器，用户页面使用 Qt 编写。
   
   - 官网：https://www.virtualbox.org
   - VirtualBox 官方发行版与源代码包镜像站：https://download.virtualbox.org/virtualbox
   - VirtualBox SVN 仓库：https://www.virtualbox.org/svn/vbox/trunk

### 三. 沙盒

#### Windows

1. **Sandboxie**：用于 Windows 的应用隔离操作环境（分为社区和商业分支，社区分支开源，商业分支闭源收费）
   
   - GitHub 仓库：https://github.com/sandboxie-plus/Sandboxie
   - 官网：https://sandboxie-plus.com

2. **Firejail**：用于 Linux 的轻量级应用隔离操作环境

   - GitHub 仓库：https://github.com/netblue30/firejail
   - 项目主页：https://firejail.wordpress.com


## 网络相关工具

### 正向代理客户端

1. **v2rayN**：系统代理管理工具，基于 v2ray 核心

   - GitHub 仓库：https://github.com/2dust/v2rayN
   - 项目主页：https://v2rayn.2dust.link

2. **Clash Meta For Android**（CMFA）：Android 系统代理管理工具

   - GitHub 仓库：https://github.com/MetaCubeX/ClashMetaForAndroid

3. **Clash Verge**：Windows/MacOS/Linux 系统代理管理工具

   - GitHub 仓库：https://github.com/clash-verge-rev/clash-verge-rev
   - 官网：https://www.clashverge.dev

